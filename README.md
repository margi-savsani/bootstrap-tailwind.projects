# bootstrap/tailwind.projects

    Project - 1
---

# 🏫 EduNexus — School Management System

A comprehensive and fully responsive **School Management Web Application** built 
with **Bootstrap 5**, featuring separate portals for Students, Teachers & Admins 
— with assignments, attendance, results, admissions and much more.

---

## ✨ Key Features

### 🎓 Student Portal
- Secure Student Login (Roll Number + Password)
- View & submit assignments with deadline tracking
- Check attendance record (monthly & overall %)
- View exam results & subject-wise marks
- Access weekly timetable
- Read school notices & announcements
- Edit personal profile

### 👩‍🏫 Teacher Portal
- Secure Teacher Login (Staff Code + Password)
- Post assignments to specific classes with deadline dates
- Mark daily attendance for students (Present / Absent / Late)
- Enter and manage exam marks
- View class-wise student list
- Manage active & draft assignments

### 🛡️ Admin Dashboard
- Admin Login with full access control
- View & manage all students and staff records
- Review, approve or reject admission applications
- Track fee payment status and send reminders
- Post school-wide notices and announcements
- Configure school settings and notifications

### 📋 Admission Management
- Online admission application form
- Student & parent/guardian information capture
- Document upload (Birth Certificate, Marksheet)
- Real-time application status tracking
- Staff query form for admission enquiries

### 📢 Notice Board
- School-wide announcements
- Urgent / Event / Exam / General categories
- Date-wise notice listing

### 📅 Timetable
- Visual weekly timetable for each class
- Subject and teacher-wise schedule view

### 💰 Fee Management
- Student-wise fee records
- Paid / Pending / Overdue status
- One-click payment reminder

---

## 🛠️ Tech Stack

| Technology | Usage |
|------------|-------|
| HTML5 | Page structure & semantic layout |
| CSS3 | Custom styling & animations |
| JavaScript (Vanilla) | Dynamic UI, login logic, dashboard rendering |
| Bootstrap 5.3 | Responsive grid, components & utilities |
| Font Awesome 6 | Icons throughout the UI |
| Google Fonts | Premium typography (Plus Jakarta Sans) |

---

## 🔐 Login Credentials (Demo)

| Role | ID | Password |
|------|----|----------|
| Student | STU2026001 | any |
| Teacher | TCH2026042 | any |
| Admin | admin | any |

> ⚠️ This is a frontend-only demo. No real authentication is implemented.

---

## 📌 Pages & Sections

| Section | Description |
|---------|-------------|
| 🏠 Home / Hero | Landing page with school stats |
| ℹ️ About | Platform overview + Notice Board |
| ⚙️ Features | 9 key feature cards |
| 📝 Admission Form | Full online application form |
| 📅 Timetable | Sample weekly class schedule |
| 📞 Contact | Contact form + school info |
| 📊 Dashboard | Role-based portal after login |

---

## 📌 What I Learned

- Building multi-role dashboards with vanilla JavaScript
- Dynamic HTML rendering using JS template literals
- Role-based UI switching (Student / Teacher / Admin)
- Form handling and validation in pure JS
- Bootstrap 5 grid system & utility classes
- Responsive design principles
- Real-world school management system workflow

---

## 🔮 Future Improvements

- [ ] Backend integration (Node.js / PHP / Firebase)
- [ ] Real authentication with JWT tokens
- [ ] Database for storing student & staff data
- [ ] Online fee payment gateway
- [ ] SMS / Email notification system
- [ ] Mobile app version (React Native)
- [ ] AI-based student performance analytics

---

## 🙋‍♂️ Author

**Your Name**  
- GitHub: [@margi-savsani](https://github.com/margi-savsani)  

---

## 📄 License

This project is built for **educational & learning purposes only.**  
All school names and data used are fictional/demo only.

---
     Project - 2
---

# 💸 SplitWise — Real-Time Expense Splitter

A sleek and modern **Real-Time Expense Splitting Web App** built with 
**Tailwind CSS** — perfect for trips, group outings, and shared expenses. 
See exactly who owes whom, settle up instantly, and never have an awkward 
money conversation again!

---

## ✨ Key Features

### 👥 People Management
- Add & remove group members instantly
- Each person gets a unique color & avatar
- Real-time balance shown per person
- See how much each person has paid in total

### 💳 Expense Tracking
- Add expenses with description & amount
- Choose who paid for the expense
- Select category with emoji picker
  (🍕 Food · 🚗 Travel · 🏨 Hotel · 🎬 Fun · 🛒 Shopping · ⚡ Bills · 🎉 Party · 💊 Medical · ✈️ Flight · 🎮 Gaming)
- Add optional notes to each expense
- Set split between selected people only
- Delete any expense with confirmation modal
- Search & filter expenses in real time

### ⚖️ Smart Balance Calculation
- Auto-calculates who owes whom
- Minimizes total number of transactions
- Updates live as expenses are added/removed

### 🤝 Settle Up
- See all pending settlements clearly
- One-click "Mark as Settled" button
- Settled payments shown separately
- Visual progress bar per settlement amount

### 📊 Stats & Analytics
- Category-wise spending breakdown
- Per-person paid vs fair share comparison
- Largest expense tracker
- Average spending per person
- Total group spend summary

### 🎮 Demo Mode
- Pre-loaded demo data (Aryan, Priya, Rohan, Sneha — Goa Trip)
- One click to see all features in action
- 
---

## 🛠️ Tech Stack

| Technology | Usage |
|------------|-------|
| HTML5 | Page structure |
| CSS3 | Custom animations, effects & styling |
| JavaScript (Vanilla) | All logic — splitting, balances, settlements |
| Tailwind CSS (CDN) | Utility-first responsive styling |
| Font Awesome 6 | Icons |
| Google Fonts | Typography (Familjen Grotesk + DM Mono) |

---

## 🧮 How the Splitting Works
---

## 🎮 Demo Data Included

Click **"Load Demo"** button:

| # | Expense | Amount | Paid By |
|---|---------|--------|---------|
| 1 | 🍕 Dinner at Barbeque Nation | ₹2,400 | Aryan |
| 2 | 🚗 Goa Trip Petrol | ₹1,800 | Priya |
| 3 | 🏨 Hotel Booking | ₹5,600 | Aryan |
| 4 | 🎬 Movie Tickets | ₹960 | Rohan |
| 5 | 🛒 Groceries & Snacks | ₹640 | Sneha |
| 6 | 🎉 Beach Activity | ₹1,200 | Priya |

**Total: ₹12,600 split between 4 friends**

---

## 💡 Use Cases

- 🏖️ **Trip planning** — Split hotel, travel & food costs
- 🍽️ **Group dining** — Who paid for dinner?
- 🏠 **Roommates** — Monthly shared bill splitting
- 🎉 **Events & parties** — Track who spent what
- 👨‍👩‍👧 **Family trips** — Fair expense distribution

---

## 📌 What I Learned

- Real-time DOM manipulation with vanilla JavaScript
- Greedy algorithm for minimizing settlement transactions
- Tailwind CSS utility-first design approach
- Dynamic UI rendering using JS template literals
- Modal & toast notification systems
- CSS animations & glassmorphism effects
- Local state management without any framework

---

## 🔮 Future Improvements

- [ ] localStorage / Firebase to save data permanently
- [ ] Export settlements as PDF or WhatsApp message
- [ ] Multi-currency support (₹, $, €, £)
- [ ] QR code payment integration (UPI, PhonePe)
- [ ] Trip history & archive
- [ ] Mobile app (React Native / Flutter)
- [ ] Invite friends via link to same expense group

---

## 🙋‍♂️ Author

**Your Name**
- GitHub: [@margi-savsani](https://github.com/margi-savsani)

---

## 📄 License

This project is built for **educational & portfolio purposes.**
Inspired by Splitwise — built from scratch with love. 💚
