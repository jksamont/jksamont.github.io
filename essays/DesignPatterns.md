---
layout: essay
type: essay
title: "Design Patterns: Looking to the Past to Build Our Futures"
# All dates must be YYYY-MM-DD format!
date: 2024-12-05
published: true
labels:
  - Design Patterns
  - Programming
  - Solutions
---

<img src="../img/design_patterns.webp">

## Looking to the Past

In everything in life, the more experiences we go through, the more problems we encounter. The beautiful thing is that more often than not, people in the past have typically run into similar problems and found solutions/patterns for them. The new generations are able to use this knowledge to guide them to build solid foundations in whichever endeavor they choose to conquer. These solutions can act as structures and a base for larger and more complex things to be built upon. This is very prevalent in the world of programming. A term that encapsulates this idea are called “Design Patterns”.

## Guidance
	
Design patterns in programming act as not hard set rules but rather blueprints to create efficient and reliable code best suited for the tasks at hand. They are tried-and-true solutions to reccuring problems in the past. While these patterns provide an idea of solutions in which to implement, it also provides the designer the opportunity for their own spin or twist on it while still working in the confinments of proven successful designs.
	
## Application

For my group and I’s final project we are creating an application that aims to connect students within the same classes to have study sessions. Essentially, one of the components in order for this to happen is that students need to register the class they are taking. This will include the course name, course instructor, year, etc. Essentially we have it so that if that class is not yet created or logged into the database, it is then created. To ensure there is no duplication, if that class is already created, it will use that data and instance instead. This is an example of factory design pattern because the process of creating course objects is centrealized in a factory and ensures consistency for instances within the structure listed before. 

Another example we plan to implement soon if time allows, falls under the observer design pattern. Essentially currently we have it so that if you are enrolled in a class you will be able to see all the current study sessions that are available to join. However, we want to have it so that whenever a new session is created all the people that are taking that class will get that notification. Essentially the study session will act as the subject and the students will be the observers. The observers will be able to get updates about sessions without having to constantly checking. Both these examples help to ensure that our code is clean, standardized, and able to maintain its usability when scaling up.

## Conclusion

Design patterns are very useful and provide the foundation in code in order for our generation to build upon by using tried-and-true solutions to problems. Design patterns are not just very useful in programming but also serve as an example that can be applied to all different areas of our lives. It is just a prime example of using guidance and structure from what others were able to figure out in the past to help us shape a successful, reliable, and more triumphant future.
