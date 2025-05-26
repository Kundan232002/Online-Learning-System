# Online Learning System

## Overview
The **Online Learning System** is a web-based platform designed to facilitate virtual education by connecting students and instructors in an interactive environment. This system enables course creation, content sharing, assessments, and progress tracking to enhance the learning experience.

## Features
- User Registration and Authentication (Students & Instructors)
- Course Creation and Management
- Video Lectures and Quizzes
- Progress Tracking and Reporting
- Notifications and Announcements
- Responsive Design for Desktop and Mobile

## Technologies Used
- Python 3.x
- Django 4.x (Web Framework)
- SQLite/PostgreSQL (Database)
- HTML, CSS, JavaScript (Frontend)
- Bootstrap (CSS Framework)

## Installation

### Prerequisites
- Python 3.6 or higher installed on your system
- Git installed to clone the repository

### Steps to Setup Locally

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Kundan232002/Online-Learning-System.git
````

2. **Navigate to the project directory:**

   ```bash
   cd Online-Learning-System
   ```

3. **Create and activate a virtual environment:**

   * On Windows:

     ```bash
     python -m venv env
     env\Scripts\activate
     ```
   * On macOS/Linux:

     ```bash
     python3 -m venv env
     source env/bin/activate
     ```

4. **Install the required packages:**

   ```bash
   pip install -r requirements.txt
   ```

5. **Apply database migrations:**

   ```bash
   python manage.py migrate
   ```

6. **Run the development server:**

   ```bash
   python manage.py runserver
   ```

7. **Open your browser and visit:**

   ```
   http://localhost:8000
   ```

---

## Usage

* Register as a student or instructor.
* Instructors can create and manage courses, upload video lectures, and create quizzes.
* Students can enroll in courses, watch lectures, take quizzes, and track their progress.
* Receive notifications and announcements related to courses.

---

## Contribution Guidelines

Contributions are welcome! If you'd like to contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeature`).
3. Make your changes and commit them (`git commit -m 'Add some feature'`).
4. Push to your branch (`git push origin feature/YourFeature`).
5. Open a Pull Request.

Please ensure your code follows the project's style guidelines and is well tested.

---

## License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

---

## Contact

For any queries or suggestions, you can reach out at:

* Email: [kundansahu854@gmail.com](mailto:kundansahu854@gmail.com)
* GitHub: [https://github.com/Kundan232002](https://github.com/Kundan232002)
