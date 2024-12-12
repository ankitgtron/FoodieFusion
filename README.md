---

## FoodieFusion
FoodieFusion is a food delivery application built using the MERN stack. The app includes user-friendly features such as secure authentication, dynamic menus, cart functionality, payment integration, and responsive design.

---

## **Mission and Objectives**

### **Goal:**
Create a seamless food delivery app with real-time features, allowing users to explore menus, place orders, and track deliveries efficiently.

### **Objectives:**
1. Build a React-based frontend with a responsive UI.
2. Develop a Node.js and Express.js backend for APIs.
3. Use MongoDB to manage data such as users, menus, and orders.
4. Integrate secure payment gateways and cart functionality.

---

## **Technology Stack**

### **Frontend:**
1. **React.js**
   - **Why:** React is ideal for building dynamic and interactive UIs.
   - **Use Case:** Used for components such as home, login, menu display, and cart management.

2. **CSS/Bootstrap**
   - **Why:** Simplifies the styling and ensures responsiveness across devices.
   - **Use Case:** Styling navigation bars, buttons, and grids for a polished look.

3. **Axios**
   - **Why:** Axios is a promise-based HTTP client for handling API requests.
   - **Use Case:** Fetching data from backend APIs and posting user inputs securely.

---

### **Backend:**
1. **Node.js**
   - **Why:** Node.js is lightweight, efficient, and ideal for asynchronous operations.
   - **Use Case:** Handles server logic for user authentication, orders, and payments.

2. **Express.js**
   - **Why:** A minimal web framework that simplifies routing and middleware handling.
   - **Use Case:** Manages routes such as login, signup, menu, and cart.

---

### **Database:**
1. **MongoDB**
   - **Why:** MongoDB offers flexible schema design, making it ideal for dynamic app requirements.
   - **Use Case:** Storing data for users, menu items, and orders.

---

### **Deployment:**
1. **Heroku/AWS**
   - **Why:** Provides scalable hosting for web applications.
   - **Use Case:** Deploying the backend, frontend, and database services to a live environment.

   ![image](https://github.com/user-attachments/assets/515e6bb7-2e14-4996-a4d2-9483919104e4)
![image](https://github.com/user-attachments/assets/1d55b4c2-c6b0-4c02-a3f1-f981bf6fc558)
![image](https://github.com/user-attachments/assets/dfb7afa3-c459-4797-b6dd-589b1d11c7da)
![image](https://github.com/user-attachments/assets/bafbbcd1-9cd7-4aa0-b0ad-fa9552bafa17)
![image](https://github.com/user-attachments/assets/30b881c6-93cd-4dd8-91f7-dcc7b2101c58)
![Screenshot (124)](https://github.com/user-attachments/assets/b245e1ae-40cd-4bf3-9a85-3bde77efa796)


---

### **Workflow Overview**
This section illustrates the complete workflow for users, restaurants, and admins in the **FoodieFusion** application, covering all major functionalities such as food ordering, cart management, payment integration, and content administration.

---

### **Flowchart**
This section provides a visual representation of the overall flow of the **FoodieFusion** application, including user registration, menu browsing, order placement, payment processing, and admin management.
![diagram-export-12-12-2024-3_06_55-PM](https://github.com/user-attachments/assets/e7f0d782-aa04-4d60-b998-9504faba4093)


---

### **System Architecture**
This section demonstrates the high-level architecture of the **FoodieFusion** app, showcasing the interaction between the frontend, backend, database, and external services like payment gateways for transactions and cloud services for menu images.
![diagram-export-12-12-2024-3_05_21-PM](https://github.com/user-attachments/assets/35a33902-081e-40a3-a1dd-bd49fc781706)


---

### **Sequence Diagram**
This section presents the sequence of interactions between the different components of the **FoodieFusion** application, including users, restaurants, the backend system, and the payment gateway.
![diagram-export-12-12-2024-3_09_13-PM](https://github.com/user-attachments/assets/9bf438aa-b110-47e1-908c-38758ff26608)


---

### **Database Design**
This section presents the database schema, highlighting the following:
- The structure of **Users**, **Restaurants**, **Orders**, **Menus**, and **Payments** collections.
- Relationships between collections (e.g., **userID** in Orders links to the Users collection, **restaurantID** links to the Restaurants collection).
- ![diagram-export-12-12-2024-3_07_34-PM](https://github.com/user-attachments/assets/2f1f2761-93b3-45da-8aeb-69c386aa4ada)


---

# Project Structure for Feature Implementation
This project is structured to ensure a systematic and incremental development process. Each week builds upon the previous deliverables, enabling a smooth transition from basic functionalities to advanced features.

---

**NOTE:**
Participants are encouraged to customize the user interface and incorporate additional features into the application. These modifications allow participants to demonstrate creativity, improve usability, and enhance the functionality of the project. Such enhancements align with the project’s objective of fostering innovative thinking while providing a personalized learning experience.

---

## **Week-by-Week Plan**

---

### **Week 1: Project Setup and Basic Structure**
- **Goal:** Set up the foundational structure for FoodieFusion.
- **Tasks:**
  1. Install and set up Node.js and MongoDB.
     - **Reading:** [Install Node.js](https://nodejs.org/en/download/) | [MongoDB Setup](https://docs.mongodb.com/manual/installation/)
     - **Video:** [Node.js Basics](https://www.youtube.com/watch?v=fBNz5xF-Kx4)  
  2. Initialize a React project.
     - **Reading:** [React Official Docs](https://react.dev/learn)  
     - **Video:** [React App Setup Guide](https://www.youtube.com/watch?v=nTeuhbP7wdE)
  3. Set up basic Express server with routing.
     - **Reading:** [Express.js Introduction](https://expressjs.com/en/starter/installing.html)
     - **Video:** [Learn Express.js Basics](https://www.youtube.com/watch?v=L72fhGm1tfE)

- **Deliverables:**  
  - Working Express server.  
  - Basic React app rendering a placeholder homepage.

---

### **Week 2: User Authentication System**
- **Goal:** Build secure user login and signup functionality.
- **Tasks:**
  1. Design login and signup forms in React.
     - **Reading:** [React Forms Tutorial](https://react.dev/reference/react/forms)
     - **Video:** [Creating Forms in React](https://www.youtube.com/results?search_query=creating+forms+in+react+js)  
  2. Implement JWT-based authentication in Express.
     - **Reading:** [Understanding JWT]([https://jwt.io/introduction/](https://jwt.io/introduction/))  
     - **Video:** [JWT in Node.js](https://www.youtube.com/watch?v=mbsmsi7l3r4)  
  3. Set up MongoDB schema for user credentials.
     - **Reading:** [MongoDB Schemas](https://mongoosejs.com/docs/guide.html)  
     - **Video:** [Mongoose Basics](https://www.youtube.com/watch?v=WDrU305J1yw)  

- **Deliverables:**  
  - Functional login and signup forms.  
  - Secure backend for user authentication.

---

### **Week 3: Menu and Search Functionality**
- **Goal:** Create and manage dynamic menu items.
- **Tasks:**
  1. Develop a MongoDB schema for menu items.
     - **Reading:** [Designing MongoDB Schemas](https://www.mongodb.com/docs/manual/data-modeling/)  
     - **Video:** [Mongoose Schema and Models](https://www.youtube.com/watch?v=DZBGEVgL2eE&t=30s)  
  2. Implement menu display and search functionality in React.
     - **Reading:** [React useEffect for Data Fetching](https://react.dev/reference/react/useEffect)  
     - **Video:** [Search Bar in React](https://www.youtube.com/watch?v=sWVgMcz8Q44)  

- **Deliverables:**  
  - Responsive menu display.  
  - Search bar for filtering items.

---

### **Week 4: Cart and Order Management**
- **Goal:** Build a functional cart and order system.
- **Tasks:**
  1. Develop a cart component in React.
     - **Reading:** [State Management in React](https://react.dev/reference/react/useState)  
     - **Video:** [React Shopping Cart Tutorial](https://www.youtube.com/watch?v=HptuMAUaNGk)  
  2. Create backend API for managing orders.
     - **Reading:** [Express Routes](https://expressjs.com/en/guide/routing.html)  
     - **Video:** [REST API in Node.js](https://www.youtube.com/watch?v=fgTGADljAeg)  

- **Deliverables:**  
  - Dynamic cart management.  
  - API for order processing.

---

### **Week 5: Payment Integration**
- **Goal:** Integrate secure payment gateways.
- **Tasks:**
  1. Integrate Razorpay or Stripe API.
     - **Reading:** [Razorpay Integration Guide](https://razorpay.com/docs/)  
     - **Video:** [Payment Gateway Integration](https://www.youtube.com/watch?v=F1G8PiBh9Xw)  
  2. Add order confirmation and history features.
     - **Reading:** [React Context for State Management](https://react.dev/reference/react/Context)  
     - **Video:** [React State Management](https://www.youtube.com/watch?v=35lXWvCuM8o)  

- **Deliverables:**  
  - Functional payment gateway.  
  - User dashboard with order history.

---

### **Week 6: Final Testing and Deployment**
- **Goal:** Test the app and deploy it live.
- **Tasks:**
  1. Test app features for bugs.
     - **Reading:** [Unit Testing in React](https://jestjs.io/)  
     - **Video:** [Testing React Apps](https://www.youtube.com/watch?v=8Xwq35cPwYg&t=137s)  
  2. Deploy the app on Heroku or AWS.
     - **Reading:** [Deploying MERN Apps](https://www.mongodb.com/mern-stack)  
     - **Video:** [Deploy MERN App](https://www.youtube.com/watch?v=cVEOhgPziO8)  

- **Deliverables:**  
  - Live app accessible via a public URL.  

**Checkout the screenshots for your references:**
![Screenshot (122)](https://github.com/user-attachments/assets/8a8dbd11-3144-4cb5-86e9-6f552e086f70)
![Screenshot (123)](https://github.com/user-attachments/assets/2d8dcd25-125e-4ac5-97c1-7ef798c87bc5)
![Screenshot (114)](https://github.com/user-attachments/assets/73235506-a89d-446f-a753-1e32cfd8e356)
![Screenshot (116)](https://github.com/user-attachments/assets/f0197c09-021c-4036-8dc2-abb2150c2dc5)
![Screenshot (117)](https://github.com/user-attachments/assets/756b3b50-ba1b-40e1-8f65-8f3324b8bf37)
![Screenshot (118)](https://github.com/user-attachments/assets/3cedef1f-468d-47f0-aa24-8942707ca7a1)
![Screenshot (119)](https://github.com/user-attachments/assets/c2f10e8d-a45a-49a6-9c4e-9b74f7e395df)
![Screenshot (121)](https://github.com/user-attachments/assets/958e328a-5a28-458c-9354-679b0a40b577)

**The End**
--- 

# References:
https://github.com/arshdeepsingh2267/Gofood

