# 🏥 Healthcare Management System (Django)

A comprehensive web-based Healthcare Management System built with **Django**.  
This project provides an efficient platform for managing patients, doctors, appointments, and medical records, designed to improve hospital workflows and digitalize healthcare services.

---

## 🚀 Features

- 👩‍⚕️ **User Roles**
  - Admin: Manage doctors, staff, and patients.
  - Doctor: View appointments, manage patient records, prescribe medicines.
  - Patient: Register, book appointments, view prescriptions and medical history.

- 📅 **Appointment Scheduling**
  - Patients can book and manage appointments with doctors.
  - Doctors can approve/reject and manage schedules.

- 📝 **Medical Records**
  - Store patient details, diagnoses, prescriptions, and history.

- 🔐 **Authentication & Authorization**
  - Secure login system with role-based access.

- 📊 **Dashboard**
  - Admin and Doctors get separate dashboards to track their activities.

---

## 🛠️ Tech Stack

- **Backend:** Django, Python  
- **Frontend:** HTML5, CSS3, JavaScript, Bootstrap  
- **Database:** SQLite (default) / MySQL (can be configured)  
- **Other Tools:** Git, GitHub  

---

## 📂 Project Structure

```

Healthcare\_Management\_System/
│
├── mysite/                # Main project settings
├── healthcare/            # Core app with models, views, templates
├── templates/             # HTML templates
├── static/                # CSS, JS, images
├── db.sqlite3             # Default database
├── manage.py              # Django management script
└── README.md              # Project documentation

```

---

## ⚙️ Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/Akanksha123-ram/Healthcare_Management_System.git
   cd Healthcare_Management_System
``

2. **Create virtual environment**

   ```bash
   python -m venv venv
   source venv/Scripts/activate   # On Windows
   source venv/bin/activate       # On Linux/Mac
   ```

3. **Install dependencies**

   ```bash
   pip install -r requirements.txt
   ```

4. **Apply migrations**

   ```bash
   python manage.py makemigrations
   python manage.py migrate
   ```

5. **Create superuser**

   ```bash
   python manage.py createsuperuser
   ```

6. **Run the development server**

   ```bash
   python manage.py runserver
   ```
---

## 🔑 Default Roles

* **Admin Panel** → `/admin/`
* **Doctor & Patient** roles are created by the admin.

---

## 📌 Future Enhancements

* ✅ Online payment integration for appointments.
* ✅ Email/SMS notifications for bookings.
* ✅ Advanced analytics dashboard for hospitals.
* ✅ Integration with IoT devices for patient monitoring.

---

## 🤝 Contributing

Contributions are welcome! Fork the repository, make your changes, and create a pull request.

---

## 📜 License

This project is licensed under the **MIT License** – feel free to use and modify as needed.

---

## 👩‍💻 Author

Developed by **Akanksha Pandey**
🌐 GitHub: [Akanksha123-ram](https://github.com/Akanksha123-ram)
