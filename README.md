clinic-website/
├── app.js                  # Main Express server file
├── db.js                   # DB initialization and connection (SQLite)
├── package.json            # Dependencies and scripts
├── routes/
│   ├── index.js            # Landing page routes
│   ├── auth.js             # Authentication routes (login, register, logout)
│   ├── student.js          # Student-specific routes
│   ├── admin_clerk.js      # Admin/Clerk-specific routes
│   └── nurse_doctor.js     # Nurse/Doctor-specific routes
├── views/
│   ├── index.ejs           # Landing page
│   ├── login.ejs           # Login form
│   ├── register.ejs        # Student registration form
│   ├── book.ejs            # Appointment booking form
│   ├── student_dashboard.ejs # Student dashboard
│   ├── admin_clerk_dashboard.ejs # Admin/Clerk dashboard
│   ├── nurse_doctor_dashboard.ejs # Nurse/Doctor dashboard
│   ├── announcements.ejs   # Manage announcements (admin)
│   ├── reports.ejs         # Reports view (admin)
│   ├── search.ejs          # Student search (admin)
│   ├── schedules.ejs       # Manage schedules (admin)
│   ├── patient_history.ejs # Patient history view (nurse/doctor)
│   └── info.ejs            # FAQ/Emergency info page
├── public/
│   ├── css/
│   │   └── style.css       # Basic responsive styling
│   └── js/
│       └── script.js       # Client-side JS (placeholder for validation, etc.)
└── database/
    └── clinic.db           # SQLite database file (generated on first run)
