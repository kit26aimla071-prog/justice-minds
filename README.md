# ⚖️ JUSTICE CAMPUS — A Safe & Transparent Student Grievance Portal
> **"Your Voice, Our Responsibility."**  
> An institutional digital grievance management platform designed for higher education colleges and universities.  
> Developed for College Hackathon Presentation by **Team Justice Minds**.

---

## 🏆 Team Justice Minds (Project Innovators)
- **Oviya K** — *Team Lead & Full-Stack Architect* (Artificial Intelligence & Data Science)
- **Dhilipkumar N B** — *Backend & Security Engineer* (Information Technology)
- **Anbu S** — *UI/UX Designer & Frontend Developer* (Computer Science & Engineering)
- **Vaishnavi D** — *Database & Analytics Specialist* (Electronics & Communication Engg)

---

## 🚀 Instant Demonstration & Access

### 1-Click Launch Options (For Hackathon Judges & Evaluators)
1. **Direct Double-Click Launcher:** Double-click `Launch-JusticeCampus.bat` in the project root to immediately open the portal in your default browser (`index.html`).
2. **Direct Browser File:** Open `index.html` directly in Google Chrome, Microsoft Edge, or Firefox.
3. **Backend REST API Server:** Run `node server.js` (or run `Run-Server.bat` / `server.ps1`) to serve the Express REST API at `http://localhost:5000`.

---

## 🔑 Demo Access Credentials (Preloaded as Specified)

The portal features an **Instant Jury Quick-Switch Bar** in the navigation header and authentication modal. You can sign in with any of these preloaded institutional accounts:

### 🎓 Student Accounts
- **Primary Student Email:** `studentskit@gmail.com`
- **Default Student Password:** `studentkit1`

| Student Name | Email / Login | Password | Department | Register No | Hostel / Day Scholar |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **Dharsan** *(Primary)* | `studentskit@gmail.com` | `studentkit1` | Computer Science & Engg | `711522CS101` | Cauvery Boys Hostel - Rm 304 |
| **Kaviya** | `kaviya@justicecampus.edu` *(or `studentskit@gmail.com`)* | `studentkit1` | AI & Data Science | `711522AI042` | Kaveri Girls Hostel - Rm 212 |
| **Jeevitha** | `jeevitha@justicecampus.edu` *(or `studentskit@gmail.com`)* | `studentkit1` | Information Technology | `711522IT033` | Day Scholar (Coimbatore Bus 7) |
| **Sachin** | `sachin@justicecampus.edu` *(or `studentskit@gmail.com`)* | `studentkit1` | Mechanical Engineering | `711522ME058` | Bhavani Boys Hostel - Rm 108 |
| **Nethra** | `nethra@justicecampus.edu` *(or `studentskit@gmail.com`)* | `studentkit1` | Electronics & Comm. Engg | `711522EC079` | Day Scholar (Saravanampatti) |

### 🛡️ Admin Authority Accounts
- **Default Admin Password:** `admin1230`

| Admin Name | Email / Login | Password | Designation & Committee Wing |
| :--- | :--- | :--- | :--- |
| **Dr. Oviya** | `oviya.admin@justicecampus.edu` *(or `Oviya`)* | `admin1230` | Chief Grievance Redressal Officer & Anti-Ragging Chairperson |
| **Dr. Dhilipkumar** | `dhilip.admin@justicecampus.edu` *(or `Dhilipkumar`)* | `admin1230` | Disciplinary Council Chairperson & ICC Advisor |

---

## 🎨 Design System & Color Palette
- **Primary Navy Blue:** `#070F1E`, `#0B192C`, `#112240`, `#1E3E62` (Institutional authority, depth, focus)
- **Secondary Light Blue & Azure:** `#0284C7`, `#38BDF8`, `#E0F2FE` (Clarity, transparency, trust)
- **Pure White & Half-White:** `#FFFFFF`, `#F8FAFC`, `#F1F5F9` (Readability, clean modern cards)
- **Sophisticated Accents:**
  - **Charcoal:** `#1E2022`, `#24292E` (Deep cards, high contrast)
  - **Warm Taupe:** `#A89F91` (Neutral secondary text)
  - **Muted Gold:** `#E5A93C`, `#F59E0B` (Warning badges, star ratings)

---

## 🌟 Core Modules & Functional Architecture

### 1. 🏛️ Modern Landing Page
- Institutional brand banner with UGC & AICTE compliance badges.
- **Tagline:** *"Your Voice, Our Responsibility."*
- **About the Project & Our Mission:** Fear-free digital grievance redressal.
- **7 Dedicated Complaint Categories:**
  1. *Bullying* (Intimidation, senior dominance, peer coercion)
  2. *Harassment* (Sexual, psychological, cyber-stalking, offensive messages)
  3. *Discrimination* (Language, regional, gender, caste bias)
  4. *Academic Issues* (Internal test marks discrepancy, attendance, lab detention)
  5. *Hostel Issues* (Drinking water quality, food hygiene, room facilities)
  6. *Campus Facilities* (Projector, air handling, lab equipment, Wi-Fi, transport)
  7. *Other Issues* (Fee counter, library access, extracurriculars)
- **4-Step How It Works Workflow:** Submit ➔ AI Triage & ID ➔ Authority Action Timeline ➔ Certified Closure.
- **Emergency Statutory Helplines:** 24x7 National Anti-Ragging (`1800-180-5522`) and Women Safety Helpline (`1091`).
- **Campus Redressal Contacts:** Direct contacts for Deanery of Student Affairs, Anti-Ragging Cell, and POSH/ICC.

### 2. 📱 Professional Sidebar Navigation
- Seamless sidebar navigation in both Student and Admin consoles.
- Quick navigation to:
  - 📊 Overview & KPI Counters
  - ➕ Submit Grievance (Student)
  - ⏳ Under Review / Pending Cases
  - ⚙️ In Progress Dockets
  - ✅ Resolved & Closed Cases
  - 🚨 Escalated to Principal
  - 🔄 1-Click Demo Profile Switcher
- Fully responsive on mobile, tablet, and desktop displays with smooth slide-in hamburger drawer.

### 3. 🎓 Student Dashboard
- **Profile Card:** Full name, roll/register number, department, year/semester, hostel room / day scholar bus route, phone.
- **KPI Metrics:** Total Lodged, In Progress, Resolved Cases, Critical Severity count.
- **Submit Complaint Modal:**
  - 7 standard categories with visual icons.
  - Title and detailed chronological statement.
  - Incident date and location fields.
  - Urgency priority selector (`Low`, `Medium`, `High`, `Critical`).
  - **Upload Supporting Evidence:** Document / photo file selector with simulated upload and badge preview.
  - **Optional Anonymous Reporting:** Cryptographically shields student identity from authorities to prevent reprisal.
  - **AI-Assisted Category & Priority Suggester:** Natural language classifier scans text and recommends the correct category, urgency priority, and committee cell with confidence score.
  - Automatic Complaint ID generation (`JC-2026-XXXX`).
- **Complaint Tracking & 5-Stage Stepper:**
  1. `Submitted`
  2. `Under Review`
  3. `In Progress`
  4. `Resolved`
  5. `Closed`
- **Certified Action Timeline:** Chronological audit trail showing actions taken by college authorities.
- **Download Official PDF Report:** Prints or saves a formatted official grievance docket.
- **Student Satisfaction Rating:** Rate resolution (1 to 5 stars) and add feedback to close the docket.

### 4. 🛡️ Admin & Disciplinary Console
- View all student complaints across college departments.
- **Search complaints by Complaint ID** (e.g. `JC-2026-8941`) or keywords.
- **Multi-level filters:** Filter by category, status, priority, and escalation.
- **Assign Complaints:** Routes to designated committee heads (Anti-Ragging, ICC, Deanery, Hostel, Facilities).
- **Advance Status & Add Action Notes:** Update status with remarks that append to the audit timeline.
- **Escalate Delayed Complaints:** 1-click formal escalation to Principal Bench for overdue cases (> 48h SLA).
- Clear distinction between pre-seeded sample data (`[DEMO SAMPLE]`) and student session complaints (`[LIVE COMPLAINT]`).

### 5. 📊 Grievance Analytics & Compliance
- Metrics tracking total cases, resolution rate, average turnaround time (2.4 days), and escalations.
- Grievance breakdown by category with responsive comparative bars.
- Statutory committee oversight status table.

### 6. 🌐 Multilingual Support (English & Tamil)
- Instant 1-click bilingual toggle between **English** and **தமிழ்** across landing pages, dashboards, buttons, and status labels.

### 7. 🔔 Real-Time Notifications & Sound Effects
- In-app notification center with live unread counter badge.
- Audio feedback chimes via browser Web Audio API for submissions and status advancements.

---

## 🗄️ Database Schema & Architecture

- **`database/schema.sql`:** Compatible with MySQL, MariaDB, and SQLite.
  - `users`: User profiles, institutional email, hashed passwords, roles (`student`, `admin`), student details.
  - `complaints`: Docket ID, student ID, category, description, incident date/location, priority, status, assigned authority, escalation flags, resolution notes, student rating.
  - `timeline_actions`: Immutable audit trail of every status transition and remark.
  - `notifications`: Push-style alerts for status updates, escalations, and assignments.
  - `authorities`: Master registry of campus committees, committee heads, and contact hotlines.
- **`database/seedData.json`:** Structured database seed file synchronized with both client application and Node.js REST API.
- **`server.js`:** Express.js REST API server with CORS, JSON body parser, health checks, authentication, and full complaint lifecycle endpoints.

---

## 🏁 Hackathon Evaluation Checklist

| Requirement | Implementation Status | Location |
| :--- | :--- | :--- |
| **Color Scheme** | Navy Blue, White, Light Blue, Charcoal, Half White, Warm Taupe, Muted Gold | `index.html` Tailwind Config |
| **Sidebar Navigation** | Responsive collapsible sidebar for both Student & Admin | `index.html` Aside Navigation |
| **Landing Page** | Project name, tagline, about, mission, features, how it works, helplines, contact | `index.html` Landing View |
| **Student Credentials** | Dharsan, Kaviya, Jeevitha, Sachin, Nethra (`studentskit@gmail.com` / `studentkit1`) | `INITIAL_USERS` in `index.html` & `seedData.json` |
| **Admin Credentials** | Oviya, Dhilipkumar (`admin1230`) | `INITIAL_USERS` in `index.html` & `seedData.json` |
| **7 Categories** | Bullying, Harassment, Discrimination, Academic, Hostel, Facilities, Other | `COMPLAINT_CATEGORIES` |
| **5 Status Stages** | Submitted ➔ Under Review ➔ In Progress ➔ Resolved ➔ Closed | `COMPLAINT_STAGES` |
| **Action Timeline** | Verified chronological audit trail with authority remarks | `ComplaintTimelineModal` |
| **Admin Features** | View all, search by ID, category/status filters, assign authority, update status, notes, escalate | Admin Console in `index.html` |
| **Distinguish Demo vs Real** | `[DEMO SAMPLE]` badge vs `[LIVE COMPLAINT]` badge | Complaint cards in `index.html` |
| **AI Category Suggester** | Real-time NLP classifier for category & priority recommendation | `analyzeComplaintText()` |
| **Multilingual** | English and Tamil (தமிழ்) toggle throughout | `DICTIONARY` in `index.html` |
| **Downloadable Report** | Formatted PDF Docket generation via print API | `printGrievanceDocket()` |
| **About Us Team** | Team Justice Minds: Oviya K, Dhilipkumar N B, Anbu S, Vaishnavi D | About View & Footer |
