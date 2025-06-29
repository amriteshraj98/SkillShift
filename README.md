# SkillShift(Backend)
The back-end of the platform is built using NodeJS and ExpressJS, providing APIs for the front-end to consume. These APIs include functionalities such as user authentication, course creation, and course consumption. The back-end also handles the logic for processing and storing the course content and user data.

Back-end Features
- User Authentication and Authorization: Students and instructors can sign up and log in to the platform using their email addresses and passwords. The platform also supports OTP (One-Time Password) verification and forgot password functionality for added security.
- Course Management: Instructors can create, read, update, and delete courses, as well as manage course content and media. Students can view and rate courses.
- Payment Integration: Students will purchase and enroll in courses by completing the checkout flow, followed by Razorpay integration for payment handling.
- Cloud-based Media Management: SkillShift uses Cloudinary, a cloud-based media management service, to store and manage all media content, including images, videos, and documents.
- Markdown Formatting: Course content in document format is stored in Markdown format, allowing for easier display and rendering on the front-end.

Back-end Frameworks, Libraries, and Tools :

The back-end of Skillshift uses various frameworks, libraries, and tools to ensure its functionality and performance, including:
- Node.js: Used as the primary framework for the back-end.
- Express.js: Used as a web application framework, providing a range of features and tools for building web applications.
- MongoDB: Used as the primary database, providing a flexible and scalable data storage solution.
- JWT (JSON Web Tokens): Used for authentication and authorization, providing a secure and reliable way to manage user credentials.
- Bcrypt: Used for password hashing, adding an extra layer of security to user data.
- Mongoose: Used as an Object Data Modeling (ODM) library, providing a way to interact with MongoDB using JavaScript.

Data Models and Database Schema

The back-end of StudyNotion uses several data models and database schemas to manage data, including:

- Student Schema: Includes fields such as name, email, password, and course details for each student.
- Instructor Schema: Includes fields such as name, email, password, and course details for each instructor.
- Course Schema: Includes fields such as course name, description, instructor details, and media content.
  
## Database

The database for the platform is built using MongoDB, a NoSQL database that provides a flexible and scalable data storage solution. MongoDB allows for the storage of unstructured and semi-structured data. The database stores the course content, user data, and other relevant information related to the platform.

![schema](https://github.com/user-attachments/assets/f4a90ae9-a173-4998-821e-87c0f8218f79)

## Architecture Diagram

Below is a high-level diagram that illustrates the architecture of the skillshift EdTech platform:

![architecture](https://github.com/user-attachments/assets/e8e2e571-d4c4-49cc-bc34-bf427f1ebb2e)

## API Design

The SkillShift platform's API is designed following the REST architectural style. The API is implemented using Node.js and Express.js. It uses JSON for data exchange and follows standard HTTP request methods such as GET, POST, PUT, and DELETE.


