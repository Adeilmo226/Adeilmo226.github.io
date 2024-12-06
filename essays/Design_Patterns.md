---
layout: essay
type: essay
title: "Lessons from Design Patterns"
date: 2024-12-05
published: true
labels:
  - Software Engineering
  - Design Patterns
---

When I first learned about design patterns in software engineering, I struggled to grasp what they really meant. But I’m someone who loves breaking things down into relatable ideas. One day, while working out at the gym, it finally clicked. Design patterns, I realized, are like workout plans for code. Just like a well-thought-out training program helps you build strength, endurance, or flexibility, design patterns help you write cleaner, more efficient, and scalable code. They are like flexible blueprints that have been tested over time, offering solutions to common programming challenges.
When I thought about them this way, it started to make a lot more sense. They became tools in my programming toolkit and using them felt like following a solid workout plan. Instead of winging it every time I wrote code, I could rely on these structured solutions to tackle recurring problems with confidence. Design patterns don’t just help your code grow stronger; they also make it more agile, just like a good gym program makes you more athletic.
One of the projects where I used my design pattern was a project called SpotMeBro, a gym web portal I worked on recently. This platform connects students with gym partners based on their fitness levels, workout goals, and experience. Behind its user-friendly interface, SpotMeBro relies on some heavy-lifting code powered by design patterns. For example, we used the Observer Pattern to keep users’ profiles, matches, and app updates in sync. In SpotMeBro, when users update their profiles, the Observer Pattern kicks in, recalculating matches in real-time to ensure they’re always paired with the best gym partners.
But SpotMeBro wasn’t the only project where I got to see the magic of design patterns in action. In another project, a dynamic simulation of the University of Minnesota campus, we created a drone delivery system that incorporated design patterns to solve real-world problems. This project wasn’t just about delivering packages, it included weather systems, porch pirates, and more, all interacting in a simulated environment.
For instance, we used the Observer Pattern again in a feature called the Porch Pirate Extension. A drone drops off a package on campus, but it’s a race against time: a robot must retrieve the package before wandering porch pirates “steal” it. The Observer Pattern kept the simulation running smoothly. The robot and porch pirates (Observers) stayed in sync with the package’s state (the Subject). Also, users on the front end were notified of any notable action that was taking place in the simulation on the side dashboard. (As seen below)

![Picture of drone simulation](../img/drone.png)

Another key part of this project was the Weather Extension, which used the Singleton Pattern to manage dynamic weather conditions affecting the simulation. The Singleton ensured there was only one instance of the weather controller at a time, keeping things consistent. For example, when rain or snow started, the speed of drones, robots, and porch pirates all adjusted automatically based on the weather. This added a new layer of complexity to the simulation, just like real-world weather impacts delivery systems.



In both SpotMeBro and the drone simulation, these design patterns helped me write code that was easier to maintain and scale. Using design patterns on these projects really helped me understand the value of design patterns and see the reason as to why it is so widely used throughout the industry. In the same way exercising can make you ready for any physical challenge, learning and using design patterns has made me more prepared to handle complex coding challenges in the future.
