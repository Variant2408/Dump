# Dump
1. Transactional annotation in springboot, diff between put and post , IOC in springBoot
2. Functional interface ..its specifications and explain it with examples ..running code
(Ruannable, callable can give examples with running code)
3. Streams -> Given a use case to sort an Employee list and collect it in map ..first do it without stream then by using stream …what’s the difference in both (need to explain)
Stream parallel
4.  What are the ways to create multithreading env ?
    Approaches need to impelemt all : 1 using normal three, 2 using Executor
5.  I want to submit task and we want to use the output for further calls ..how will u do it? Ans : Future object
    *Running code , modular code
6. What are the drawbacks of this Future object approach? How can u modify it ? Ans Async calls ,using Completable Future)
    Working and wrote code but not runnable
7. ORM tool
8. MongoDB query to get the list of employees by first name , last name and age filter
9.  How will u implement joins in ORM ???
10.  Design Distributed logger-
LLD (needs to come with classes and java code to implement that classes ) ….no need to run..rough idea
11. Why u did out of the box in your company
12. Question regarding microservice -> about circuit breaker
13. What your goal
14. internal working of hashmap
15. The Reservation system should contain the following features:
The Railway Reservation System will provide the available Train-list between stations, and Seat-availability, via-details.
After successful payment of the ticket fare the System will generate the ticket with seat allocation will be given to the passenger.
The Reservation system should store all train details, fare details, PNR no.
16. Design your own library which can invoke rest calls to external systems
functional requirement:
provide clients to invoke post and get calls
ability to select choice of implementation during the invocation-> Spring rest template/apache gttp client/ ok http client etc..
17. when do we use factory and when strategy
18. There is a interface which has 3 abstract methods. now already there is a production running code which has 2 concrete implementations implementing this interface. Now i have a new implementation which have to just implement 2 abstract methods in the interface, how to handle this
19. Given a LLD problem to design a Retail POS system to evaluate the balance to be provided back to the customer during the billing, had to take into consideration different currencies ( as in balance can be provided back in multiple type of currencies) and denominations for each kind of currency, design should follow SOLID principles and have good performance.    
20. Given an incoming stream of requests which contain the order_id, order_date, completion_date, process each request based on some condition. Priority for processing should be given in the order of order_date and completion_date. What data structure should be used here ? Also, I was asked to write the compare logic for this.
21. I was asked to write the entire code for a message delivery system. Had to explain all the classes and their interactions. Also, had to apply design patterns like strategy, factory etc, while implementing the code. The interviewer was expecting a working code for the above problem. Also, he wanted me to design the API for this which I did using Springboot.
22. Singleton classes – Explained their real-life use cases and wrote the code.
23. Keywords (final, static, transient) – I wasn’t familiar with transient at the time.
24. How to make a class immutable?
25. Error handling – Discussed checked and unchecked exceptions.
26. Can you leave a catch block empty? Can this be used in a static method?
27. Given an attribute that needs to be incremented by two threads until its value reaches 5000, I was asked to write the code.
28. What is AtomicInteger? What is the String pool?
29. Difference between Hashtable and ConcurrentHashMap
30. I was prepared for HashMap vs. Hashtable but didn’t know this difference.
31. How to optimize an API that makes multiple API calls, then checks the cache, and finally queries the database?
32. how to handle dependency injeciton in case of circular dependencies in springboot
33.  How to change port number of a spring app
34.  @Controller vs @RestController
35.  Design a system that explains how audio streaming works in Alexa when a user asks it to perform an operation like playing music.
36.  Retry Pattern with Resilience4j
37.  Round 3: System Design - Notification Service:
Requirements: Multiple channels, scheduled notifications, priority delivery, retries, status tracking, scale to 10M/day.
38. How Authentication and Authorization works .
39. PATCH Vs PUT http methods
40. What is sharding , how it is useful , and what is celebrity problem , what happends if no. of servers changes how do you handle that .
41. What is partitioning and how it is diff to sharding
42. what is indexing how it helps in query optimization / how it works internally .
43. Do you review PR's and how you will provide the review comments to your collegues .
44. If you are facing the 504 gateway timeout , what are the cases and how you will figure out and how u will solve the issues .
45. Design a HLD for whatsapp like chat system -- I wasn't went throught the system design , but told him about the web sockets and message queues for notifications . He asked me to look back how the websocket works .
46. Given a Music streaming service like spotify, you need to add a feature to return top K songs in last 7 days.I gave a solution with taking a 7 day window, for each day we will store (song : count), and keep a sliding window, on each new day we will add data for new day, and remove the data of last day. And put all of it in minheap of size k.And return the minheap data.I said this we will do everyday.HLD I only had a DB, for song data, cache to store this count, and a playback server, and this topK song server, api gateway and Load balancer. He had asked to keep only components related to the new feature.I discussed concurrency a bit, said we will use redis redlock.
47. 
