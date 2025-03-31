# TaskNexusX 🚀

TaskNexusX เป็นระบบจัดการงานและโปรเจคที่ช่วยให้คุณและทีมของคุณสามารถบริหารงานได้อย่างมีประสิทธิภาพ ด้วยฟีเจอร์ Kanban Board, การแจ้งเตือนแบบ Real-time และการจัดการงานแบบ Collaboration ทำให้ทุกคนทำงานได้อย่างราบรื่น

## 🔥 Features

✅ **User Management** – ลงทะเบียน, เข้าสู่ระบบ, กำหนดบทบาท (Admin, Member)  
✅ **Project Management** – สร้างและจัดการโปรเจค, เพิ่มสมาชิกในโปรเจค  
✅ **Task Management** – สร้าง, แก้ไข, และมอบหมายงานให้สมาชิกในทีม  
✅ **Kanban Board** – จัดการงานด้วยกระดาน Kanban แบบ Drag & Drop  
✅ **Real-time Notifications** – แจ้งเตือนเมื่อมีการเปลี่ยนแปลงงานหรือโปรเจค  
✅ **Comment & Collaboration** – แสดงความคิดเห็นในงานเพื่อการสื่อสารที่ดีขึ้น  
✅ **Dashboard & Reports** – ดูสถิติและวิเคราะห์ข้อมูลโปรเจค  

## 🛠️ Tech Stack

### Backend:
- Spring Boot (Java)
- Spring Security + JWT Authentication
- WebSocket for real-time notifications
- PostgreSQL/MySQL
- Redis (Optional - สำหรับ Caching)

### Frontend:
- Angular (TypeScript)
- Angular Material / TailwindCSS
- NgRx (State Management)

### DevOps:
- Docker (Optional - Containerization)
- CI/CD (GitHub Actions / Jenkins)
- Deployed on AWS / DigitalOcean / Heroku

## 📂 Project Structure

```
TaskNexusX/
│-- backend/  (Spring Boot API)
│-- frontend/ (Angular UI)
│-- docs/     (Documentation)
│-- docker/   (Docker Configurations)
│-- README.md
```

## 🚀 Getting Started

### 1. Clone Repository
```bash
git clone https://github.com/yourusername/TaskNexusX.git
cd TaskNexusX
```

### 2. Backend Setup (Spring Boot)
```bash
cd backend
./mvnw spring-boot:run
```

### 3. Frontend Setup (Angular)
```bash
cd frontend
npm install
ng serve
```

### 4. Access the Application
- Frontend: `http://localhost:4200`
- Backend API: `http://localhost:8080/api`

## 🛡️ Security & Authentication
- ใช้ JWT สำหรับการยืนยันตัวตน
- Role-based Access Control (RBAC) กำหนดสิทธิ์การเข้าถึง

## 📜 API Documentation
API สามารถเข้าถึงได้ที่ `http://localhost:8080/swagger-ui.html`

## 📌 Future Enhancements
- เพิ่มการเชื่อมต่อกับ Google Calendar
- รองรับ Multi-tenancy สำหรับองค์กร
- Mobile App (React Native / Flutter)

## 👨‍💻 Contributing
Pull Requests ยินดีต้อนรับ! กรุณาอ่าน [CONTRIBUTING.md](CONTRIBUTING.md) ก่อนเริ่มต้น

## 📄 License
MIT License - สามารถใช้งานและปรับปรุงโค้ดได้อย่างอิสระ 🎉

