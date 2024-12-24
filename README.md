---
### **Project Name: Tic Tac Toe Multiplayer App**

**Tic Tac Toe Multiplayer App** is a full-stack web application allowing users to play Tic Tac Toe in real-time with another player while chatting simultaneously. It features authentication, multiplayer functionality, and a built-in chat system powered by the Stream API.

---

### **Mission and Objectives**

---

### **Mission:**
To develop an interactive multiplayer Tic Tac Toe game with seamless real-time gameplay and chat functionality, providing users with a competitive and social gaming experience.

---

### **Objectives:**
1. **User Authentication:**
   - Implement secure user login and signup using cookies.
   - Manage sessions efficiently.

2. **Real-Time Gameplay:**
   - Enable users to invite and play against others in real time.
   - Synchronize game states across players seamlessly.

3. **Chat System:**
   - Integrate real-time chat between players during gameplay.

4. **Responsive Design:**
   - Ensure compatibility across devices for an optimal user experience.

5. **Deployment:**
   - Deploy the application for public access.

---

### **Technology Stack**

#### **Frontend**
1. **React.js**
   - **Why?**: Simplifies building dynamic user interfaces.
   - **Use Case**: Handles game UI, login/signup forms, and chat interface.

2. **CSS**
   - **Why?**: Styles the application for better user experience.
   - **Use Case**: Adds layout, spacing, and styling for components.

---

#### **Backend**
1. **Node.js**
   - **Why?**: Enables scalable server-side development.
   - **Use Case**: Manages APIs and real-time connections.

2. **Express.js**
   - **Why?**: Simplifies API creation.
   - **Use Case**: Defines routes for authentication, game logic, and chat.

3. **Stream API**
   - **Why?**: Provides real-time chat and WebSocket connections.
   - **Use Case**: Manages chat and player communication.

---

#### **Database**
1. **MongoDB**
   - **Why?**: Flexible schema for managing user and game data.
   - **Use Case**: Stores user profiles, game states, and chat messages.

---

#### **Deployment**
1. **Frontend Hosting: Netlify or Vercel**
   - **Why?**: Optimized platforms for React app hosting.
   - **Use Case**: Deploys the client-side application.

2. **Backend Hosting: Heroku or AWS**
   - **Why?**: Reliable platforms for backend services.
   - **Use Case**: Hosts APIs and manages database connections.

---

## **Workflow Overview**

The application workflow involves users signing up or logging in, inviting another player to a game, and playing Tic Tac Toe in real-time. The integrated chat system enhances interaction during gameplay.

### **FlowChart**

![image](https://github.com/user-attachments/assets/4e946d49-76bf-446a-a0cc-f5ab229b84b2)


---

### **Project Structure for Feature Implementation**
This project is structured to ensure a systematic and incremental development process. Each week builds upon the previous deliverables, enabling a smooth transition from basic to advanced functionalities.

**NOTE:** Participants are encouraged to customize the design and functionality to make the application unique.

---

## **Week-by-Week Learning Plan**

---

### **Week 1: Project Setup and UI Design**
- **Goal:** Set up the foundational structure and design the app UI.
- **Tasks:**
  1. Initialize a **React.js** project and structure folders.
     - **Reading:** [React.js Official Docs](https://reactjs.org/docs/getting-started.html)
     - **Video:** [React.js Crash Course](https://www.youtube.com/watch?v=w7ejDZ8SWv8)
  2. Design login and signup forms.
     - **Reading:** [CSS Basics](https://developer.mozilla.org/en-US/docs/Web/CSS)
     - **Video:** [CSS Crash Course](https://www.youtube.com/watch?v=1Rs2ND1ryYc)

- **Deliverables:**
  - Responsive login and signup pages.

---

### **Week 2: User Authentication**
- **Goal:** Implement secure user authentication.
- **Tasks:**
  1. Set up user schema with Mongoose.
     - **Reading:** [MongoDB Schema Design](https://mongoosejs.com/docs/guide.html)
     - **Video:** [Mongoose Models Tutorial](https://www.youtube.com/watch?v=DZBGEVgL2eE&t=30s)
  2. Build authentication APIs with JWT.
     - **Reading:** [JWT Basics](https://jwt.io/introduction/)
     - **Video:** [JWT Authentication Guide](https://www.youtube.com/watch?v=mbsmsi7l3r4)
  3. Integrate cookies for session management.
     - **Reading:** [Managing Cookies in JavaScript](https://developer.mozilla.org/en-US/docs/Web/API/Document/cookie)
     - **Video:** [Cookies in JavaScript](https://www.youtube.com/watch?v=5o25hvgZ6No)

- **Deliverables:**
  - Fully functional login/signup system with session management.

---

### **Week 3: Game Functionality**
- **Goal:** Develop core gameplay features.
- **Tasks:**
  1. Build game board and logic in React.
     - **Reading:** [React State Management](https://reactjs.org/docs/hooks-state.html)
     - **Video:** [React Tic Tac Toe Tutorial](https://www.youtube.com/watch?v=Zmo5k3MmaMg)
  2. Integrate real-time gameplay using WebSocket connections.
     - **Reading:** [WebSocket API](https://developer.mozilla.org/en-US/docs/Web/API/WebSockets_API)
     - **Video:** [WebSocket in React](https://www.youtube.com/watch?v=NEtB6v7zmZQ)

- **Deliverables:**
  - Functional Tic Tac Toe game with real-time synchronization.

---

### **Week 4: Chat System Integration**
- **Goal:** Add real-time chat functionality.
- **Tasks:**
  1. Set up Stream API for chat integration.
     - **Reading:** [Stream API Documentation](https://getstream.io/chat/docs/)
     - **Video:** [Stream Chat Integration](https://www.youtube.com/watch?v=UUddpbgPEJM)
  2. Build chat interface in React.
     - **Reading:** [React Component Design](https://reactjs.org/docs/components-and-props.html)
     - **Video:** [React Chat App](https://www.youtube.com/watch?v=SEkfzqIgvTo)

- **Deliverables:**
  - Fully functional chat system integrated with gameplay.

---

### **Week 5: Deployment and Testing**
- **Goal:** Deploy the application and ensure it’s production-ready.
- **Tasks:**
  1. Test all features using Postman and React Testing Library.
     - **Reading:** [API Testing with Postman](https://learning.postman.com/docs/testing/)
     - **Video:** [Postman Tutorial](https://www.youtube.com/watch?v=VywxIQ2ZXw4)
  2. Deploy frontend and backend.
     - **Reading:** [Deploying React Apps](https://vercel.com/docs)
     - **Video:** [Full-Stack Deployment Guide](https://www.youtube.com/watch?v=KKyag6t98g8)

- **Deliverables:**
  - Deployed application accessible via a public URL.

---
### Screenshots

![Screenshot (431)](https://github.com/user-attachments/assets/0698ea24-acf6-4042-a13d-ff8c3f396e98)
![Screenshot (432)](https://github.com/user-attachments/assets/89671108-9ca8-4a7c-8be3-01a17d88f085)
![Screenshot (433)](https://github.com/user-attachments/assets/9875c059-dbc4-4a4e-8bb7-30e796ea033b)
![Screenshot (434)](https://github.com/user-attachments/assets/2705ca83-42f4-48f2-8d9e-394a421b6bc8)
![Screenshot (429)](https://github.com/user-attachments/assets/198f9b66-35f6-4048-b11e-ac99bcc32156)
![Screenshot (430)](https://github.com/user-attachments/assets/18870841-3873-465c-a31e-325c602cf3bc)


---

### **References**
1. [React Documentation](https://reactjs.org/docs/getting-started.html)
2. [MongoDB Documentation](https://www.mongodb.com/docs/manual/)
3. [Stream API Documentation](https://getstream.io/chat/docs/)
4. [WebSocket API](https://developer.mozilla.org/en-US/docs/Web/API/WebSockets_API)
5. https://github.com/machadop1407/Multiplayer-Tic-Tac-Toe-React
6. https://www.youtube.com/watch?v=Iw1YmBoOYb4

