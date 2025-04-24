University Enrollment System (Full Stack)
A complete university course registration system with backend APIs (Spring Boot) and a frontend interface (HTML/CSS/JS). Allows students to browse courses, register, and manage enrollments — all in one platform.
📁 Project Structure

university-enrollment-system/
├── backend/    → Spring Boot API for students, courses, enrollments
├── frontend/   → HTML/CSS/JS UI for interacting with the system

🧠 Features

- Student registration and management
- Course listing and admin controls (add/edit/delete)
- Enroll and drop courses
- Integrated API calls between frontend & backend
- Responsive, clean UI

⚙️ Tech Stack

| Layer      | Tech Used                 |
|------------|---------------------------|
| Backend    | Java 17, Spring Boot, JPA, H2/MySQL |
| Frontend   | HTML5, CSS3, JavaScript   |
| Build Tool | Maven                     |
| Deployment | GitHub + Local setup      |

🚀 How to Run Locally
1️⃣ Backend Setup

cd backend
./mvnw spring-boot:run
Runs at: http://localhost:8080

2️⃣ Frontend Setup

cd frontend
Open index.html in browser
(Use Live Server extension in VS Code for best results)

🔗 API Endpoints (Examples)

| Method | Endpoint             | Description                   |
|--------|----------------------|-------------------------------|
| GET    | /api/students        | Get all students              |
| GET    | /api/courses         | Get all courses               |
| POST   | /api/students        | Register new student          |
| POST   | /api/enrollments     | Enroll student in a course    |

✅ Future Enhancements

- JWT-based user authentication
- Admin dashboard for managing data
- Confirmation alerts and error handling in frontend
- Cloud deployment on Render / AWS EC2 / Vercel

💼 Ideal For

- Full-stack Spring Boot + JS practice
- Cloud deployment portfolio
- Real-world university/college projects
