# student-performance-analytics-tool
A Flask-based web app to analyze student data, generate grayscale PDF grade cards with insights, and secure access with teacher authentication. Built with Python, SQLite, Matplotlib, and ReportLab.
Engineered a Flask web application to process student data from CSV files, compute performance metrics (e.g., class average, median, top/bottom performers), and visualize results using Matplotlib for grade distribution and attendance-performance correlation.  

Designed and implemented professional-grade PDF grade cards using ReportLab, adhering to specific design requirements: grayscale color scheme, sharp-edged borders, and Times New Roman font for a clean, formal appearance.  

Enhanced grade cards with personalized insights, including performance comparisons to class averages, identification of strongest/weakest subjects, and tailored recommendations based on scores and attendance, improving usability for educators.  

Implemented secure teacher authentication with session management, requiring a password change after the first login using hashed passwords (via werkzeug.security), ensuring compliance with basic security standards.  

Developed responsive front-end templates using HTML and CSS, featuring a consistent design with gradient backgrounds, rounded containers, and interactive elements like tooltips for correlation insights.  

Utilized SQLite for persistent storage of teacher credentials and login status, enabling secure password updates and maintaining state across sessions.  

Integrated Flask’s flash messaging system to provide user feedback for login, logout, and password change actions, enhancing the user experience.

