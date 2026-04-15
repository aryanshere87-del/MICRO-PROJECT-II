The Stack Library: A LIFO-Based ERP System

Madhav Institute of Technology & Science (MITS), Gwalior 

The Stack Library is an integrated Library Management System built as a first-year BTech micro-project. It combines the fundamental Data Structure concept of a Stack (Last-In-First-Out) with modern Business System logic to manage student book transactions, librarian oversight, and financial audits.

🏛️ Project Overview

This application provides a dual-portal interface for Students and Librarians. It focuses on data persistence, user privacy through session isolation, and real-time administrative analytics.

Key Objectives

Logical Implementation: Use the LIFO principle for issuing and returning books.

Business Integration: Automated fine calculation and revenue tracking.

Data Integrity: Reliable state management using browser LocalStorage.

User Security: Role-based access control with password protection.

✨ Key Features

👨‍🎓 Student Portal

Identity-Based Sessions: Login using a Library Card Number to access a private desk.

Visual Stack Desk: Manage issued books using Push (Issue) and Pop (Return) operations.

Real-Time Catalog: Search through categorized folders (Data Structures, Web Dev, etc.).

Fine Awareness: Private notification of outstanding fines on the dashboard.

🔑 Librarian Portal (Admin)

Audit Ledger: Complete history of all transactions with timestamps and student IDs.

Fine Management: Monitor outstanding fines across all users and clear them upon payment.

Inventory Control: Register new books into specific library categories.

Live Analytics: Visual representation of library stock using dynamic charts.

Proactive Alerts: Automatic "Red Alert" notifications for books held over 24 hours.

🛠️ Technology Stack

Frontend: HTML5, Tailwind CSS (Styling)

Logic: Vanilla JavaScript (ES6+)

Data Persistence: Browser LocalStorage API

Analytics: Chart.js

UI/UX: Dark Mode support and responsive layouts.

📋 Business Logic & Data Structures

The LIFO Principle

The project serves as a practical demonstration of the Stack data structure. When a student returns a book, the system enforces that the last book issued is the first one returned, mirroring real-world physical book stacking.

Financial Module

To simulate a real Business System, an automated fine module is integrated:

Grace Period: 1 Minute (set for demonstration purposes).

Penalty: ₹5 per minute late.

Calculation: Computed using epoch timestamps to ensure accuracy even across browser sessions.

Security & Privacy

Session Isolation: Unique key mapping ensures Student A cannot view Student B's desk.

Admin Access: Librarian tools are gated by a master password (mits123).

🚀 Getting Started

Clone the repository or download the index.html file.

Open the file in any modern web browser (Chrome, Firefox, or Edge).

To Login as Student: Enter any Card Number.

To Login as Librarian: Use the "Librarian" tab and enter password mits123.

👥 Contributors

Aryan Sharma (Lead Developer | 1st Year CSBS)



