# **Covey.Town README**

## **Overview**
Covey.Town is an advanced virtual meeting platform that simulates real-life interactions by enabling participants to fluidly navigate through multiple simultaneous video conversations. It's designed to provide a seamless, natural communication experience for remote collaboration.

## **Architecture**
The platform utilizes a robust frontend built with PhaserJS for interactive 2D environments and incorporates the Twilio Programmable Video API for reliable video chat functionality. The backend, responsible for the application's logic, is managed within the `townService` directory.

## **Technical Contributions**

### **Development and Interface Design**
- Orchestrated the development of Covey.Town, emphasizing fluid transitions between video calls to mimic in-person interactions.
- Crafted over 10 responsive webpages with TypeScript and React, focusing on user engagement and interface responsiveness.
- Utilized Tailwind CSS for its utility-first approach, enabling a more intuitive and visually appealing user experience.
- Ensured consistent UI performance and feature stability by implementing snapshot testing with Jest.js.

### **Streaming and Backend Optimization**
- Enhanced video streaming capabilities with CRUD RESTful APIs built with Express.js, improving data interaction and management.
- Adopted MongoDB for its flexible data schema, which is ideal for the dynamic data handling required by Covey.Town.
- Deployed the application on AWS EC2, taking advantage of its scalable cloud computing capabilities.
- Applied auto-scaling and load balancing to ensure that the platform performs optimally, even under varying loads.

## **Local Deployment**

### **Backend Setup**
1. Create a Twilio account to access their communication APIs.
2. Generate the necessary API credentials through Twilio.
3. Configure a `.env` file in the `townService` directory with the Twilio credentials.

### **Frontend Configuration**
1. Define the backend service URL in a `.env` file in the frontend directory as `REACT_APP_TOWNS_SERVICE_URL=http://localhost:8081`.
2. Launch the frontend with `npm start` after performing an initial `npm install`.

Explore Covey.Town and its functionalities at [app.covey.town](http://app.covey.town). For a detailed setup guide and the latest updates, refer to the comprehensive documentation within the Covey.Town repository.
