# 5th-Semester Summer Intership at Izonnet Web Solution Pvt.Ltd #

This repository documents my summer internship experience during the 5th semester at Izonnet Web Solution Pvt.Ltd. The primary project was focused on developing an chatting Website Using MERN stack. This README provides a summary of the work completed each day during my summer internship.

**Company: Izonnet Web Solution Pvt.Ltd**

## Week_1 (13/05/2024 – 18/05/2024): ##

 **Introduction to React**:

- **Initial Setup**:
  - Set up the development environment using Create React App.
  - Configured ESLint and Prettier for code quality and consistency.
- **Basic Concepts**:
  - Understood the virtual DOM and its benefits over the traditional DOM.
  - Reviewed JSX syntax and its role in creating React elements.

 **React Components**:

- **Functional Components**:
  - Created several functional components to understand their stateless nature.
  - Practiced returning JSX from functional components.
- **Class Components**:
  - Developed class components to manage local state.
  - Implemented lifecycle methods such as componentDidMount and componentWillUnmount.
  - Compared and contrasted functional and class components.

 **State and Props**:

- **Props**:
  - Passed data between components using props.
  - Validated props using PropTypes.
- **State**:
  - Managed state within class components using this.state.
  - Updated state using this.setState.
  - Demonstrated state-driven UI updates by building a simple counter application.

 **Event Handling**:

- Handled events in React, such as onClick and onChange.
- Implemented methods to update state based on user interactions.
- Built interactive components such as buttons and forms.

 **Conditional Rendering**:

- Used conditional statements to render different UI elements.
- Practiced ternary operators and short-circuit evaluation for conditional rendering.

 **Hands-On Projects**:

- **To-Do List Application**:
  - Created a to-do list app to reinforce concepts of components, state, and props.
  - Added features like adding, deleting, and marking tasks as complete.
- **Static Site**:
  - Built a static site with multiple components to practice component composition.

## Week_2 (20/05/2024 – 25/05/2024): ##

1.  **React Array Map and Digital Clock Project:**
    - **Array Mapping:**
        - Learned how to use the map function in JavaScript to iterate over arrays and generate React components dynamically.
        - Created a simple React component to display a list of items. This involved understanding the concept of keys in React to ensure each list item is uniquely identified, which is crucial for performance optimization and avoiding rendering issues.
        - The task reinforced my understanding of how React handles lists and the importance of efficient rendering.
    - **Digital Clock with Date:**
        - Developed a digital clock component that displays the current time and date. This project involved using the JavaScript Date object to fetch the current time and date.
        - Implemented setInterval to update the clock every second, providing real-time updates. This involved understanding the lifecycle of React components and how to properly clean up intervals to avoid memory leaks.
        - Styled the clock to ensure it was visually appealing and easy to read, focusing on both functionality and user experience.
2. **Advanced React Concepts:**
    - **React Hooks:**
        - Delved deeper into React hooks, especially useState and useEffect. useState was used to manage state within functional components, and useEffect was employed to handle side effects like fetching data and setting up intervals.
        - Explored creating custom hooks to encapsulate reusable logic. This helped in understanding the principles of DRY (Don't Repeat Yourself) in code and how hooks can enhance code modularity and readability.
        - Implemented several small projects and examples to reinforce the understanding of hooks and their practical applications in real-world scenarios.
3. **Introduction to Node.js:**
    - **Setting Up Node.js Environment:**
        - Installed Node.js and npm (Node Package Manager) on the development machine.
        - Learned how to initialize a new Node.js project using npm init and understood the purpose of the package.json file for managing project dependencies and scripts.
    - **Basic Node.js Server:**
        - Created a simple Node.js server using the http module to handle HTTP requests and responses. This involved understanding the basics of server-side programming and how to handle different types of requests (GET, POST, etc.).
        - Explored the asynchronous nature of Node.js and how it handles I/O operations, which is fundamental for building efficient, non-blocking web applications.
    - **npm Packages:**
        - Learned how to install and use npm packages. This included understanding the difference between local and global installations, and how to manage dependencies for a Node.js project.
        - Experimented with a few popular npm packages to get a feel for how third-party libraries can be integrated and utilized in Node.js projects.

## Week_3 (27/05/2024 – 01/06/2024): ##

 **Advanced Node.js Development:**

- **Express.js Framework:**
  - Set up a basic Express server to understand its workings.
  - Created various endpoints to handle different HTTP requests (GET, POST, PUT, DELETE) for building RESTful APIs.
  - Explored middleware in Express.js for error handling, logging, and serving static files.
- **Building RESTful APIs:**
  - Designed and built a RESTful API using Express.js to handle CRUD operations.
  - Connected the API to a MongoDB database using Mongoose for schema-based data modeling.
  - Added data validation and error handling to make the API robust.
- **Asynchronous Programming:**
  - Improved understanding of asynchronous programming in Node.js using callbacks, promises, and async/await.
  - Refactored code to use async/await for readability and ease of management.
  - Learned to avoid callback hell and promise chaining by properly structuring code.

 **Basic Node.js Concepts:**

- **File System Module:**
  - Worked with the Node.js fs module for basic file operations (creating, reading, updating, deleting).
  - Created scripts to automate tasks like logging data to files and processing file contents.
- **Event Emitter:**
  - Explored the Event Emitter class to handle and trigger custom events, showcasing an understanding of event-driven programming.
- **Modules and NPM:**
  - Deepened knowledge of creating and using Node.js modules for modular and reusable code.
  - Explored npm (Node Package Manager) for managing project dependencies and extending functionality with various npm packages.

## Week \_4 (03/06/2024 – 09/06/2024) ##

 **Chatting Website Development**

- **Project Setup**:
  - Set up the project repository on GitHub.
  - Configured development environment with necessary tools (e.g., Node.js, npm).
- **Core Features Defined**:
  - Identified core functionalities: user authentication, real-time messaging using WebSockets, and user profiles.

 **Backend Development**

- **Real-Time Communication**:
  - Implemented real-time messaging using Socket.io.
  - Established a WebSocket server in Node.js to handle connections and message events.
  - Managed events like message sending, receiving, and user presence.
- **Database Integration**:
  - Designed MongoDB schema for efficient data storage of user profiles, messages, and chat rooms.
  - Integrated Mongoose for MongoDB operations, ensuring smooth database interactions.
- **RESTful APIs**:
  - Developed REST endpoints:
    - User registration and login.
    - Retrieval of chat history for users.

 **Frontend Development**

- **React Components**:
  - Created modular React components for various parts of the chat interface:
    - Chat window for displaying messages.
    - Message input component for sending messages.
    - User list for displaying online users.
    - User profile component.
  - Implemented state management using React's hooks (useState, useEffect) for managing component state and data flow.
- **Styling and UX**:
  - Designed responsive UI using CSS, Bootstrap, and Material-UI to ensure accessibility across different devices.
  - Focused on usability to provide an intuitive and visually appealing chat experience

## Week _ 5 (10/06/2024 – 18/06/2024) ##

 **Final Touches and Completion**

- **Final Features**:
  - Completed implementation of all planned features for the chatting website.
  - Verified functionality of core features such as user authentication, real-time messaging, and user profiles.
  - Conducted thorough testing to ensure all features worked as expected.
  - Addressed any remaining issues or bugs to ensure a stable release.
- **UI Polishing**:
  - Made final adjustments to the user interface:
    - Refined layout to enhance usability and aesthetics.
    - Improved design elements for a more modern and visually appealing look.
    - Optimized user interactions to ensure intuitive navigation and seamless user experience.

 **Documentation**

- **Project Documentation**:
  - **Technical Documentation**:
    - Detailed the project's architecture, including backend (Node.js, MongoDB) and frontend (React) components.
    - Provided insights into how different modules interact and the overall system design.
  - **User Guides**:
    - Created comprehensive user guides covering registration, login, messaging, and profile management.
    - Included step-by-step instructions and screenshots to assist users in navigating the application.
  - **API Documentation**:
    - Documented RESTful API endpoints used for user management, messaging, and other functionalities.
    - Specified request/response formats, authentication requirements, and example use cases.
  - **Clarity and Accessibility**:
    - Ensured all documentation was clear, concise, and accessible to both technical and non-technical audiences.
    - Used diagrams, examples, and explanatory text to facilitate understanding.

 **Reflection and Learning**

- **Internship Summary**:
  - Reflected on the internship experience:
    - Identified and documented personal growth in technical skills (e.g., JavaScript, MongoDB), project management, and teamwork.
    - Analyzed challenges faced during development and how they were resolved.
    - Summarized insights gained about software development best practices and real-world application of theoretical knowledge.
  - **Key Learnings**:
    - Documented specific lessons learned:
      - Effective use of WebSocket technology for real-time communication.
      - Importance of thorough testing and bug fixing in ensuring software quality.
      - Strategies for UI/UX improvement based on user feedback and usability testing.
      - Experience with documentation as a critical part of software development lifecycle.

# Project Repo:  https://github.com/shrey3456/mern-chat-app**
# Installation

To run the project locally, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/shrey3456/mern-chat-app.git

2. Navigate to the project directory:
    ```bash
   cd mern-chat-app
   cd frontend
   cd backend

3. Install dependencies:
    ```bash
    npm i

4. Start the Frontend:
    ```bash
    npm run dev

5. Start the  backend:

    ```bash
    npm run server

