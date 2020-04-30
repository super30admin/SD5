# System Design 5


**Designing Twitter**

**What to be designed?**

1. URL shortening is used to create shorter aliases for long URLs. Shorter URLs take up less space and can save mistakes through typos in longer URLs.
2. Play around with shortening of URLs on tinyurl.com to understand the use case of shortened URLs.
3. URL shortening is used for optimizing links across devices, tracking individual links to analyze audience and campaign performance, and hiding affiliated original URLs.

1. Twitter is a social networking service used to post and read messages of length 140 characters. Users of the service should be able to post tweets, favorite them and follow people. 
2. Tweets can be posted and read by the registered users, where as anonymous users can only read them.  
3. Twitter could be accessed through website interface, mobile app or SMS. 

**Feature Requirements**

Primary Features:

1. Users should be able to post tweets, follow other users and mark tweets as favorites. 
2. Timeline of the user should consist of top tweets of the user and people the user follows. 
3. The service should support posting tweets with multi-media content like photos and videos. 

Secondary Requirements:

1. Service should be highly available.
2. Latency cannot exceed 200ms for generation of user-timeline.
3. Consistency can sometimes be affected in the interest of availability; So, if a user doesn't see a tweet for sometime, it is fine.


Extended Features:
Searching for tweets and replying to a tweet.
Currently trending topics/searches.
Tagging other users in tweets.
Tweet notifications.
Suggestions on whom to follow?
Moments

**TO DO : Follow the below framweork to design System. Mandatory upload of hand drawn photos of design.**

**Capacity Estimation and Constraints**

What will your estimations of scale? As a system design student you should be able to make intelligent assumptions based on real life systems. 

**System APIs**

**Database Design**

**Basic System Design and Algorithm**

**Data Partitioning and Replication**

**Caching**

**Load Balancing**

**Timeline Generation**

**Monitoring**

**Handling Edge cases in given system**



