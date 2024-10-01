# Lab 01: Timetabled

## Overview

This project involves building a **grid-style calendar** with one-hour events that plan out a single week. The calendar was created for a specific person—real or imagined—where the timetable reflects their activities for the week. 

The calendar can be informative, humorous, or exploratory. In this project, I designed a schedule for [insert who the calendar is for and why, if relevant]. 

Some examples of possible calendars include:
- Planning a vacation for a friend, family member, or pet
- A week in the life of a historical figure
- Adapting to a polyphasic sleep cycle
- The week before a famous crime

## Completed Features

### Required Features:
- A one-week calendar with one-hour time blocks.
- Each event on the calendar has a unique title.
- Events are color-coded based on the type of activity, making it easier to distinguish between them at a glance.

### Stretch Features:
- Event blocks include additional details such as **descriptions** and **locations**.

## Screenshots

Here are screenshots of the completed calendar with all required and stretch features:

![Calendar View](./assets/Screenshot%202024-10-01%20at%209.03.47%20AM.png)

## Technologies Used

- **Vite**: For project scaffolding and development server.
- **ReactJS**: For building the user interface and handling component-based logic.
- **CSS**: For styling the calendar and events, including the color-coding of activities.

## How the Project Was Built

1. The project was initialized using **Vite** to quickly scaffold a React project.
2. A grid structure was implemented in the **Calendar component**, with table rows representing one-hour blocks and columns representing each day of the week.
3. **Event components** were created, each representing an individual event. Events were passed as props to dynamically render different activities for different time slots.
4. **Props** were also used to pass custom colors to each event, allowing for easy identification of event types.
5. **Additional details** like descriptions and locations were implemented for the stretch goals, further customizing the timetable for the intended user.

## How to Run This Project

1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo-url.git
   ```

2. Navigate to the `lab-01` folder:
   ```bash
   cd lab-01
   ```

3. Install the dependencies:
   ```bash
   npm install
   ```

4. Run the application in developer mode:
   ```bash
   npm run dev
   ```

5. Open the project in your browser. Vite will provide a local URL to access the project (e.g., `http://127.0.0.1:5173`).

## Reflection

This lab was a great opportunity to practice creating reusable components in React, working with props, and building a structured, color-coded UI. The stretch goals provided additional complexity by adding descriptions and locations to events, demonstrating how to pass and manage more detailed information across components.

## License

This project is for educational purposes only.
