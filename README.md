**Briefly summarize The Gaming Room client and their software requirements**

The Gaming Room is a company that creates online multiplayer games. For this project, they wanted to expand their popular game, Draw It or Lose It, so it could run on more than just Android. Their goal was to build a version that works on the web, on mobile devices, and on desktop computers. To do that, they needed a system that was secure, scalable, and supported lots of teams and players joining different game sessions at the same time.

To support this transition, the system needed to meet several key requirements:
•	Multiplayer Support: The platform must allow multiple users to join and play in the same game session at the same time.
•	Cross Platform Play: Players should be able to participate no matter what device they use: desktop, laptop, or mobile.
•	Singleton Pattern: The system must ensure that game managers and session trackers remain unique so data stays consistent and does not conflict across the application.

**What did you do particularly well in developing this documentation?**

I did a good job explaining the system’s design and using patterns like Singleton and Iterator to show how the game could stay consistent while handling multiple players and teams. I also researched different operating systems to make sure my recommendations matched what the client needed. Defining the requirements early helped keep everything organized, and using a clear template made the documentation easy to read and understand.

**What about the process of working through a design document did you find helpful when developing the code?**

The design document worked like a blueprint that cleared up confusion during development. It helped me define how the system should work, how data should move, and how different parts should interact, making it much easier to start writing code that matched what the client needed.

**If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?**



**How did you interpret the user’s needs and implement them into your software design? Why is it so important to consider the user’s needs when designing?**

I understood what users needed by reviewing the project details and user stories, then building features like user roles, secure sessions, and support for multiple teams. I also made sure the game worked the same on any device, with progress carried over, by keeping most of the important logic on the server instead of on each device. Focusing on real life user situations, like slow internet or different screen sizes, helped ensure the final product was easy to use, reliable, and met their expectations. Taking the user's needs into account guarantees that the software is user-friendly, effective, and aligns with client expectations.

**How did you approach designing software? What techniques or strategies would you use in the future to analyze and design a similar software application?**

I approached the design by breaking the project into smaller parts, identifying the main classes, and mapping out how they connected. I used UML diagrams to show how everything would interact and applied design patterns to make the system easier to scale and reuse. In the future, I’d get more feedback from others earlier on and run simple usability tests to make sure the design actually fits what users expect before jumping into coding.

