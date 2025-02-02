# SkillsBloom-Skill sharing website 🎯


## Basic Details
### Team Name: INNO


### Team Members
- Member 1: Fathima Nehrine - Govt.Model Engineering College,Thrikkakara
- Member 2: Sahlah Fathima  - Govt.Model Engineering College,Thrikkakara
- Member 3: Mishelina Joby  - Govt.Model Engineering College,Thrikkakara

### Hosted Project Link
[mention your project hosted project link here]

### Project Description
A web-based platform designed to connect individuals looking to share and learn new skills. Users can register, upload tutorials, schedule sessions, and interact through discussions, fostering a community of knowledge sharing.

### The Problem statement
There is a growing demand for accessible platforms where individuals can share their skills and gain mentorship. Many people face challenges in finding appropriate mentors for specific skills and lack easy ways to offer their own expertise. The existing systems are often fragmented and don't offer an integrated platform that facilitates both learning and teaching efficiently

### The Solution
The Skill Sharing Platform is a comprehensive solution that allows users to register, share their skills, and get mentorship from others with complementary expertise. It includes features like skill categorization, tutorial uploads, session scheduling, and a discussion forum. The platform ensures ease of access for users to both share and acquire knowledge in various skill categories. This centralized system provides a seamless experience for learning, teaching, and interaction within the community.

## Technical Details
### Technologies/Components Used
For Software:
- Languages used:
      [Front end] HTML,CSS,JavaScript
      [Back end] Node.js
- VS Code, Git


### Implementation
For Software:
1. Frontend Implementation:
HTML, CSS, JavaScript: The frontend is built using basic web technologies. HTML is used for structuring the content, CSS is used for styling, and JavaScript is used for handling user interactions and connecting to the backend.
Pages:
Homepage: Welcomes users and provides navigation links to other pages.
Registration/Login Page: Allows users to either register or log in, with form validation for username, email, and skills.
Profile Page: Displays user details and skills.
Skills Page: Shows a list of skill categories and allows users to upload tutorials.
Session Scheduling Page: Allows users to schedule mentorship sessions based on their skills.
Forum Page: Provides space for users to post and discuss messages.
2. Backend Implementation:

Node.js & Express: The backend is built using Node.js and the Express.js framework, which handles HTTP requests and responses.
In-Memory Data Storage: Temporary arrays are used to store data like users, tutorials, and sessions. This data can be replaced by a database later.
APIs: Several routes and APIs are implemented to handle user registration, tutorial uploads, session scheduling, and fetching data (e.g., users, tutorials by skill, and sessions by skill).
POST /register: Handles user registration and stores the user information.
GET /api/users: Retrieves all registered users.
POST /upload: Allows users to upload tutorial videos.
GET /api/tutorials/:skill: Retrieves tutorials for a specific skill.
POST /schedule: Allows users to schedule sessions.
GET /api/sessions/:skill: Retrieves sessions for a specific skill

3. Server and Routing:
The Express server listens on port 5000, and the pages (like index.html, register.html, skills.html) are served as static files from the public directory.
The backend APIs are connected with the frontend through forms and AJAX requests to create a seamless user experience.

# Installation
[commands]

# Run
[commands]

### Project Documentation
For Software:

# Screenshots (Add at least 3)

1. ![Screenshot (947)](https://github.com/user-attachments/assets/82dfb5e5-6263-4c78-9229-50fce075fc13) - Home Page
2. ![Screenshot (948)](https://github.com/user-attachments/assets/e7f91fe0-5ad0-401a-bea1-24c4befe1ab2) - Registration/Login Page
3. ![Screenshot (949)](https://github.c![Screenshot (949)](https://github.com/user-attachments/assets/b17ee9c1-8565-4739-bb89-802ecd9ad4fe) - Profile Page
4. ![Screenshot (950)](https://github.com/user-attachments/assets/ea8a9c84-abf7-48e9-9e56-68a8e7694dc8)
   ![Screenshot (951)](https://github.com/user-attachments/assets/f4e3459c-54f1-4f56-bf67-1dea3b60b91e)
   ![Screenshot (952)](https://github.com/user-attachments/assets/aa535f20-9b12-4216-9138-befd88be0f8a)
              - Skills for learning
5. ![Screenshot (953)](https://github.com/user-attachments/assets/e88c64be-b4f1-47f7-b7f9-3f3f516dc704) - Scheduling tutorial sessions
6. ![Screenshot (954)](https://github.com/user-attachments/assets/ec7f2023-06c7-4440-a40a-cd31e48e6cbc) - Forum Posting


### Project Demo
# Video
[]
Explain what the video demonstrates



## Team Contributions
- Sahlah Fathima: Front End
- Fathima Nehrine: Back end
- Mishelina Joby: Front end

---
Made with ❤ at TinkerHub
