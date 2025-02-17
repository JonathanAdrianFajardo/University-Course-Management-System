# University-Course-Management-System
Objective: To design and implement a robust University Course Management System that optimizes academic administration by effectively managing courses, student enrollments, faculty assignments, grade tracking, and report generation. The system provides secure and role-specific access for administrators, faculty, and students, offering customized tools for seamless course registration, progress monitoring, and faculty schedule management. By streamlining these essential operations, the system aims to boost efficiency and promote a well-structured academic ecosystem.

Key Features:  
- Course Management: (Add, edit, and delete courses)  
- Student Management: (Enroll students, maintain records, and assign grades)  
- Faculty Management: (Assign faculty to courses and manage their workloads)  
- Authentication System: (Role-based access for administrators, students, and faculty)  
- Grade Management: (Record and compute student grades)  
- Reporting System: (Generate detailed reports on grades, class lists, and faculty loads)

## Tech Stack

- **Frontend**: React.js
- **Backend**: Django (Python)
- **Database**: PostgreSQL
- **APIs**: RESTful architecture
- **Version Control**: Git

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/JonathanAdrianFajardo/University-Course-Management-System.git
   ```
2. Navigate to the project directory:
   ```bash
   cd University-Course-Management-System
   ```
3. Install backend dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Install frontend dependencies:
   ```bash
   cd frontend
   npm install
   cd ..
   ```
5. Configure the database in the `settings.py` file.
6. Apply database migrations:
   ```bash
   python manage.py migrate
   ```
7. Start the backend server:
   ```bash
   python manage.py runserver
   ```
8. Start the frontend server:
   ```bash
   cd frontend
   npm start
   ```

## Usage

- Access the system in your web browser at the configured URL (e.g., `http://127.0.0.1:8000` for local deployment).
- Log in using appropriate credentials based on your role (Admin, Faculty, or Student).
- Navigate through the intuitive interface to manage courses, enrollments, grades, and reports.

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new feature branch: `git checkout -b feature-name`.
3. Commit your changes: `git commit -m 'Add some feature'`.
4. Push to the branch: `git push origin feature-name`.
5. Open a pull request.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

---

For any issues, please create a GitHub issue or reach out to the project maintainer.
