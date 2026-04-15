The Stack Library: A LIFO-Based ERP System

Madhav Institute of Technology & Science (MITS), Gwalior 

The Stack Library is an integrated Library Management System built as a first-year BTech micro-project. It combines the fundamental Data Structure concept of a Stack (Last-In-First-Out) with modern Business System logic to manage student book transactions, librarian oversight, and financial audits.

1. 🏛️ Project Overview

This application provides a dual-portal interface for Students and Librarians. It focuses on data persistence, user privacy through session isolation, and real-time administrative analytics.

1.1. Key Objectives

Logical Implementation: Use the LIFO principle for issuing and returning books.

Business Integration: Automated fine calculation and revenue tracking.

Data Integrity: Reliable state management using browser LocalStorage.

User Security: Role-based access control with password protection.

2. ✨ Key Features

2.1. 👨‍🎓 Student Portal

Identity-Based Sessions: Login using a Library Card Number to access a private desk.

Visual Stack Desk: Manage issued books using Push (Issue) and Pop (Return) operations.

Real-Time Catalog: Search through categorized folders (Data Structures, Web Dev, etc.).

Fine Awareness: Private notification of outstanding fines on the dashboard.

2.2. 🔑 Librarian Portal (Admin)

Audit Ledger: Complete history of all transactions with timestamps and student IDs.

Fine Management: Monitor outstanding fines across all users and clear them upon payment.

Inventory Control: Register new books into specific library categories.

Live Analytics: Visual representation of library stock using dynamic charts.

Proactive Alerts: Automatic "Red Alert" notifications for books held over 24 hours.

3. 🛠️ Technology Stack

Frontend: HTML5, Tailwind CSS (Styling)

Logic: Vanilla JavaScript (ES6+)

Data Persistence: Browser LocalStorage API

Analytics: Chart.js

UI/UX: Dark Mode support and responsive layouts.

4. 📋 Business Logic & Data Structures

4.1. The LIFO Principle

The project serves as a practical demonstration of the Stack data structure. When a student returns a book, the system enforces that the last book issued is the first one returned, mirroring real-world physical book stacking.

4.2. Financial Module

To simulate a real Business System, an automated fine module is integrated:

Grace Period: 1 Minute (set for demonstration purposes).

Penalty: ₹5 per minute late.

Calculation: Computed using epoch timestamps to ensure accuracy even across browser sessions.

4.3. Security & Privacy

Session Isolation: Unique key mapping ensures Student A cannot view Student B's desk.

Admin Access: Librarian tools are gated by a master password (mits123).

5. 🚀 Getting Started

Clone the repository or download the index.html file.

Open the file in any modern web browser (Chrome, Firefox, or Edge).

To Login as Student: Enter any Card Number.

To Login as Librarian: Use the "Librarian" tab and enter password mits123.

6. 👥 Contributors

Aryan Sharma (Lead Developer | 1st Year CSBS)


