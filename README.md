
# Capstone LMS Project

## Description
This is a **Learning Management System (LMS)** capstone project built using **C#**, **JavaScript**, **CSS**, and **SQL Server**.  
The project allows users to **register, log in**, and access LMS functionalities based on their roles (**Admin, Student, or User**).  
It includes **course management**, **user management**, and **role-based access control** with a responsive frontend interface.

## Features
- User registration and login system with role selection (Admin, Student, User)  
- Role-based dashboards and access control  
- Course creation, updating, and deletion (Admin functionality)  
- Enroll in courses (Student functionality)  
- Responsive frontend UI for easy navigation  
- Database-driven backend using SQL Server  

## Technologies Used
- **Backend:** C# (.NET), SQL Server  
- **Frontend:** JavaScript, HTML, CSS, React.js (if applicable)  
- **Version Control:** Git & GitHub  

## Project Structure
```
Capstone_LMS/
├── Backend/          # Server-side code (C#, .NET)
├── Database/         # SQL scripts and DB configuration
├── Frontend/src/     # Frontend source code
├── Demo_video/       # Demonstration video
```

## Installation
1. **Clone the repository**  
```bash
git clone https://github.com/manjumanda/Capstone_Lms.git
```
2. **Backend setup**  
   - Open the backend project in **Visual Studio**  
   - Configure the **SQL Server database** using scripts in `Database/`  
   - Run the backend server  
3. **Frontend setup**  
   - Navigate to the frontend folder  
   - Install dependencies:  
```bash
npm install
```
   - Start the frontend server:  
```bash
npm start
```

## Usage
- **Admin:** Manage courses and users  
- **Student:** Register, enroll in courses, view enrolled courses  
- **User:** Basic LMS access (depending on implemented features)

## Contributing
1. Fork the repository  
2. Create a new branch (`git checkout -b feature/YourFeature`)  
3. Make your changes  
4. Commit changes (`git commit -m "Add new feature"`)  
5. Push to branch (`git push origin feature/YourFeature`)  
6. Create a pull request  

## License
This project is open-source and available under the **MIT License**.

