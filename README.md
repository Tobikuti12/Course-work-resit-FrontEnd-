# Course-work-resit-FrontEnd-
# CST3144 Coursework: After School Lessons Full Stack Web Application

## 1. Project Overview
This project is a Full Stack Web Application that allows users to browse and purchase after-school lessons. It features a reactive frontend built with Vue.js and a RESTful API backend built with Node.js/Express, connected to a MongoDB Atlas cloud database.

## 2. Links to Hosted Application
* **Frontend GitHub Repository:** [(https://github.com/Tobikuti12/Course-work-resit-FrontEnd-)]

* **Frontend Live Site (GitHub Pages):** [(https://tobikuti12.github.io/Course-work-resit-FrontEnd-/)]

* **Backend GitHub Repository:** 
[(https://github.com/Tobikuti12/CourseWork-BackEnd/tree/main)]

* **Backend Live API (Render):** 
[(https://coursework-backend-1-irvy.onrender.com)]/lessons

## 3. Key Features
* **Lessons Display:** Dynamically fetches 10+ lessons from the MongoDB database.
* **Real-time Search:** A "Search as you type" feature that filters lessons by subject and location.
* **Sorting:** Users can sort lessons by subject, location, price, and availability in both ascending and descending order.
* **Shopping Cart:** Users can add multiple lessons to a cart and remove them. The system prevents adding more items than available in the inventory.
* **Checkout Validation:** A secure checkout form using Regular Expressions to ensure:
    * **Name:** Contains letters only.
    * **Phone:** Contains numbers only.
* **Database Integration:** * `POST` requests to save new orders.
    * `PUT` requests to update lesson inventory/spaces automatically upon purchase.

## 4. Technology Stack
* **Frontend:** Vue.js (v2.7), HTML5, CSS3, Font Awesome.
* **Backend:** Node.js, Express.js.
* **Database:** MongoDB Atlas (Native Node.js Driver).
* **Hosting:** GitHub Pages (Frontend) and Render (Backend).

## 5. Setup and Local Execution
To run this project locally:
1.  **Backend:**
    * Navigate to the backend directory.
    * Run `npm install` to install dependencies (Express, CORS, MongoDB).
    * Run `node server.js` to start the server.
2.  **Frontend:**
    * Open `index.html` in any modern web browser.
    * Ensure the `BASE_URL` in the `<script>` section of `index.html` matches your local or live server address.

## 6. Testing
API endpoints (GET, POST, PUT) were tested using **Postman**. The Postman collection file is included in the root directory of this submission for verification.
