# CS-230-Operating-Platforms

8-2 portfolio

1. Briefly summarize The Gaming Room client and their software requirements. Who was the client? What type of software did they want you to design?

The client, The Gaming Room, currently offers an Android-based game called Draw It or Lose It. They’re looking to grow their reach by making the game accessible on more platforms, including web browsers, desktop systems (Mac, Windows, and Linux), and mobile devices. To support this, the game will follow a client-server setup. One important requirement is that only one instance of a game can be active in memory at a time, so the singleton design pattern will be used to enforce that. The game also needs to support multiple teams and multiple players per team, and both game names and team names must be unique.

2. What did you do particularly well in developing this documentation?

One thing I feel I handled well was keeping an overall view of the entire project. I stayed focused on how the different parts of the system needed to work together and made solid recommendations regarding things like storage solutions, how to handle data, and what the backend and client sides would need to function smoothly.

3. What about the process of working through a design document did you find helpful when developing the code?

Working on the design document made me think through every part of the application in detail, which was really useful. It helped me plan the structure of the app before jumping into the code. The Development Requirements section especially pushed me to be thoughtful and deliberate, making sure I didn’t overlook important technical needs.

4. If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?

If I had the chance to go back and make changes, I’d focus on the Recommendations section. After getting more feedback and digging into more research, I realized there are better ways to handle certain aspects—especially when it comes to application security. With what I know now, I’d suggest more up-to-date methods to keep user data safe and the system more secure overall.

5. How did you interpret the user’s needs and implement them into your software design? Why is it so important to consider the user’s needs when designing?

Understanding what the users wanted was a major part of this project, and I took it seriously. I used my background in development to figure out how to meet their goals and did some extra research when something wasn’t clear. It’s so important to focus on the user when designing software because if the final product doesn’t solve their problems or make their experience better, it really doesn’t matter how well it’s built.

6. How did you approach designing software? What techniques or strategies would you use in the future to analyze and design a similar software application?

I approached the design by creating a clear plan to guide the process. I broke the project down into smaller pieces so I could focus on each part individually—like how data would be handled, how players would interact with the game, and how everything would connect on the backend. In future projects, I’d use a similar strategy: plan carefully, focus on user needs, and tackle development step by step so nothing important gets overlooked.
