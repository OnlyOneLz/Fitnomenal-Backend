# Fitnomenal-Backend

Description

This project is a workout generator that dynamically creates fresh workouts upon a button click. Users can target specific areas like upper body, lower body, full body, and cardio. Additionally, the application features a profile page allowing users to edit personal details and a progress page displaying weight goals and completed workouts with graphical representations.
Deployment

The project is deployed at .https://fitnomenal-workouts.vercel.app/ 


Getting Started/Code Installation

To access the code, follow these steps:
Clone the repository to your local machine.
Install the necessary dependencies by running npm install.
Run the application using npm start.
Access the application at http://localhost:3000.


Timeframe & Working Team

Timeframe: Completed during 1 Week.

Working Team: Collaborated with Sofia and Aisha.


Technologies Used

React
Next.js
Express
MongoDB
Node.js


Brief

The project aimed to create a dynamic workout generator with the ability to target specific body areas. It also included profile management, progress tracking, and a workout history feature.


Planning

During the planning stage, we:
Created wireframes for the front end and UI.
Developed an ERD for the database.
Utilised project management tools for sprint planning.
Collaboratively assigned tasks and responsibilities.
We assigned each task using a trello board, there were lists for incomplete , working on and finished tasks.
We used Excalidraw to plan out our database, pages and components.
We used a Trello board to assign individual tasks, we did this because it allows us to track what each of us was working on at a given time and meant that nothing overlapped. 


Build/Code ProcessWireframe

Workout Generation:

In this code snippet it shows part of my very large fetch to the external api that i was in charge of. Here i am generating 70 exercises with each fetch made up of different muscles, which later i would go onto separate and create a full upper body workout.

This was the second part of my api fetch, where i randomise the exercises and select either 2 or 1 from each array and then send that back in the response, creating a random upper body workout.
Profile Page:

In these code snippets i am allowing the user to update their profile details and based on the updates the bmi function will calculate the users bmi. On top of that i am updating the state, the changes made by the user are shown instantly. 



Challenges

Asynchronous Operations: Managing asynchronous operations during data fetching from the external API posed a challenge. Ensuring that the data was processed correctly and efficiently within the React and Next.js framework required careful consideration.

State Synchronisation: Coordinating state updates between different components proved to be challenging. Maintaining consistency in the application's state across various sections, such as the workout generator and profile page, required close attention to detail.


Wins

Workout Generation Algorithm: The successful implementation of a dynamic workout generation algorithm was a significant achievement. Creating a system that could generate diverse and effective workouts based on user preferences demonstrated a high level of technical proficiency.

Effective Collaboration: The team's collaborative efforts were a key win. Successfully meeting project goals and deadlines was a testament to effective communication, task delegation, and a well-organised workflow.


Key Learnings/Takeaways

React and Next.js Proficiency: The project contributed to an enhanced proficiency in React and Next.js. Handling complex state management, component interactions, and asynchronous operations deepened the team's understanding of these technologies.

Database Interaction with MongoDB: The project provided an opportunity to improve understanding and skills in interacting with databases, specifically MongoDB. Managing user profiles, progress tracking, and workout history involved effective utilisation of database functionalities.


Bugs

No major bugs to report.


Future Improvements

Implement a social sharing feature for generated workouts.
Enhance user authentication and authorization.
Integrate a recommendation engine based on user preferences.
