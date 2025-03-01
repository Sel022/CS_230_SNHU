# GameAuth

How to start the GameAuth application
---

1. Run `mvn clean install` to build your application
1. Start application with `java -jar target/gameauth-0.0.1-SNAPSHOT.jar server config.yml`
1. To check that your application is running enter url `http://localhost:8080`

Health Check
---

To see your applications health enter url `http://localhost:8081/healthcheck`


"The Gaming Room" is a client company that wanted a software design for a multi-platform gaming platform, aiming to improve the functionality of their existing Android game "Draw It or Lost It" and expand its availability to other devices, requiring a comprehensive client-side application that would allow users to access and play their game across various platforms. 

Key points about the client and their needs:
- **Client name:** The Gaming Room 
- **Existing game:** "Draw It or Lost It" (currently only on Android) 
- **Desired functionality:**
    - Multi-platform access to the game (across different operating systems) 
    - Improved user interface and gameplay features 
    - Potential for future game additions to the platform 
- **Software type needed:** A cross-platform gaming client application 
To develop documentation for "The Gaming Room" clients and their software requirements, start by clearly outlining the client's needs, desired functionalities, and technical specifications for their gaming platform, then break down these requirements into distinct sections like system overview, user roles, features, performance criteria, and compatibility, ensuring detailed descriptions and clear language throughout the document. 

Key Steps:

1. Introduction and Client Overview:
    - **Client Information:** Briefly introduce "The Gaming Room" client, their business focus, and target audience (gamers).
    - **Project Goal:** Clearly state the primary objective of the software development project (e.g., creating a web-based gaming platform, mobile app, etc.).
2. System Overview:
    - **System Architecture:** Provide a high-level overview of the system architecture, including components like front-end, back-end, database, and any relevant APIs.
    - **Key Functionalities:** List the core functionalities of the gaming platform (e.g., user registration/login, game selection, matchmaking, leaderboards, in-game chat).
3. User Roles and Requirements:
    - **User Types:** Defining different user roles as a casual gamer, pro gamer, administrator and their access levels.
    - **Feature Requirements:**
    - **Core Gameplay Features:** Detailed descriptions of each game mode, mechanics, and rules. Specific requirements for game customization options (if applicable).
    - **Social Features:** 
            - Friend management system (adding, viewing, messaging)
            - Clan or group creation (if applicable)
            - In-game communication features (chat, voice)
            - User Interface (UI) 
    - **Requirements:**
            - Design guidelines and aesthetics
            - Navigation structure
            - Visual feedback mechanisms
4. Technical Requirements:
    - **Platform Compatibility:** Specify the target platforms (web browser, mobile devices, PC) and their minimum supported versions.
    - **Server Requirements:**
            - Server technology (e.g., Node.js, Python, etc.)
            - Database considerations (e.g., MySQL, MongoDB)
            - Scalability needs
    - **Development Tools and Frameworks:**
            - Front-end frameworks (React, Angular, Vue.js)
            - Back-end frameworks (Express, Django, Laravel)
            - Version control system (Git)
5. Performance and Security Requirements:
    - **Latency and Response Time:** Define acceptable performance metrics for gameplay and server responsiveness.
    - **Data Security:** Outline data protection measures for user information and sensitive data.
    - **Anti-Cheat Mechanisms:** If applicable, specify requirements for preventing cheating behaviors.
6. Testing and Quality Assurance:
    - **Testing Strategy:** Describe the testing approach (unit, integration, system, user acceptance)
    - **Acceptance Criteria:** Define clear criteria for considering a feature complete and ready for release.
    - Important Considerations:
    - Prioritization: Clearly indicate which features are essential, desirable, or optional based on project scope and timeline.
    - Revision and Updates: Design the documentation to be easily updated as project requirements evolve.
    - Collaboration: Ensure all stakeholders (developers, designers, QA team) have access to and contribute to the documentation.
    
    By following these steps, you can create a comprehensive and well-organized document that effectively captures all "The Gaming Room" client's software requirements, facilitating smooth development and project execution.

    Key steps involved:
    - User Research:
    - Gather data: Conduct interviews, surveys, usability testing, and user observations to collect information about users' goals, tasks, pain points, and preferred workflows. 
    - Create user personas: Develop fictional user profiles based on research findings to represent different user segments and their needs. 
    - Need Analysis:
    - Identify key needs: Analyze the collected data to identify the most critical user needs and prioritize them based on importance and frequency of use. 
    - Formulate user stories: Translate user needs into concise statements describing what a user wants to achieve within the software ("As a [user type], I want to [action] so that [benefit]"). 
    - Design Implementation:
    - Feature prioritization: Decide which features directly address the most important user needs and align with the overall product vision. 
    - Interface design: Create a user interface that is intuitive, easy to navigate, and visually appealing, considering user feedback and accessibility needs. 
    - Prototyping and testing: Build interactive prototypes to test with users and gather feedback on the design's effectiveness in meeting their needs. 
    - Iteration and refinement:
    - Incorporate feedback: Continuously refine the design based on user feedback, making adjustments to features, layout, and functionality as needed. 
    Monitor usage data: Track how users interact with the software to identify areas for further improvement and optimization. 
    - Important considerations:
    - User-centered design:
    Always prioritize the user's needs and perspective throughout the design process. 
    - Accessibility: Design the software to be usable by people with disabilities, including those with visual impairments or motor difficulties.


