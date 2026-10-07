# student-management-ERP
A full-stack Student Management ERP system built with Spring Boot, Java, React (Next.js), and MySQL to handle educational administration and data tracking.

## 🚀 Tech Stack
* **Backend:** Java, Spring Boot, Spring Data JPA, Maven
* **Frontend:** React, Next.js, TypeScript, Tailwind CSS, shadcn/ui
* **Database:** MySQL (Hosted on Aiven Cloud)
* **API Testing:** Postman

## ✨ Key Features
* **RESTful Architecture:** Clean and scalable API endpoints handling GET, POST, PUT, and DELETE requests.
* **Modern UI/UX:** Responsive, component-based frontend utilizing React hooks and Tailwind for a seamless user experience.
* **Dynamic Data Filtering:** Real-time client-side search functionality to filter students by name, branch, or section.
* **Cloud Database Integration:** Persistent data storage using a cloud-hosted MySQL relational database.

## 🛠️ Getting Started

### Prerequisites
* Java 17+
* Node.js & npm
* MySQL

### Backend Setup
1. Navigate to the `student-backend` directory.
2. Update the `application.properties` file with your database credentials.
3. Run the Spring Boot application using Maven:
   `./mvnw spring-boot:run`
4. The server will start on `http://localhost:8080`.

### Frontend Setup
1. Navigate to the `student-frontend` directory.
2. Install dependencies:
   `npm install`
3. Start the development server:
   `npm run dev`
4. Access the application at `http://localhost:3000`.
