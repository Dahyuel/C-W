# 🎓 ASU Career Week – Event Management System

A scalable, role-based **Event Management Platform** built for university career events.
Designed to handle multi-day conferences with thousands of attendees, multiple operational teams, QR-based attendance tracking, session booking, analytics, and real-time dashboards.

> This project demonstrates full-stack event architecture, role-based access control, QR systems, analytics dashboards, and operational workflow management.

---

# 🚀 Overview

The ASU Career Week Event Management System is a centralized platform that manages:

* Attendee & volunteer registration
* Role-based dashboards
* QR-powered attendance tracking
* Session booking with capacity control
* Company showcase management
* Real-time building occupancy
* Points & leaderboard system
* Announcement system
* Analytics & reporting

It is built for large-scale university events where multiple teams operate simultaneously.

---

# 🏗 Architecture

### Frontend

* React 18
* TypeScript
* Tailwind CSS
* React Router v6
* Context API (AuthContext)

### Backend

* Supabase (PostgreSQL)
* Supabase Auth
* Supabase Storage

### Real-Time Features

* Live attendance updates
* Dynamic occupancy tracking
* Real-time leaderboard updates

---

# 👥 Role-Based System

The platform uses strict role-based access control. Each role has a dedicated dashboard and workflow.

| Role              | Description                                |
| ----------------- | ------------------------------------------ |
| Attendee          | Students and graduates attending the event |
| Volunteer         | General event volunteers                   |
| Registration Team | Event check-in team                        |
| Building Team     | Building entry management                  |
| Info Desk         | Session booking and management             |
| Team Leader       | Volunteer supervision & bonus assignment   |
| Admin             | Event management & analytics               |
| Super Admin       | System-level management                    |

---

# 🎓 Attendee Features

* Profile registration (multi-step form)
* QR code generation for check-in
* Session booking with seat limits
* View booked sessions
* Browse companies by filters
* View event schedule
* Interactive venue map
* Points & ranking system
* Notifications panel

---

# 🤝 Volunteer Features

* Personal dashboard
* Points tracking
* Ranking system
* Activity history
* Role-specific instructions
* Volunteer ID badge

---

# 🛂 Registration Team Features

* QR code scanning
* Manual search by ID
* Mark event entry/exit
* Live attendee validation
* Instant feedback system

---

# 🏢 Building Team Features

* Building entry/exit tracking
* Session entry validation
* Booking verification
* Bonus point automation
* QR-based check-ins

---

# 🧾 Info Desk Features

* Session capacity monitoring
* Add/remove attendees from sessions
* QR attendee lookup
* View full attendee lists
* Capacity warnings and full indicators

---

# 👨‍💼 Team Leader Features

* Manage assigned team members
* Assign bonus points
* Record volunteer attendance
* View real-time event statistics
* Send announcements (role-based or custom targeting)

---

# 🛠 Admin Features

* Overview dashboard with live statistics
* Session management (CRUD)
* Schedule management
* Company management
* User filtering & search
* CSV export functionality
* Detailed analytics:

  * Gender distribution
  * University breakdown
  * Faculty distribution
  * Daily attendance stats

---

# 👑 Super Admin Features

* System health overview
* Admin account management
* Security log monitoring
* Database maintenance tools
* Backup & optimization tools

---

# 📱 Shared Components

### Dashboard Layout

* Header with profile controls
* Notifications panel
* Leaderboard modal
* Responsive mobile navigation

### QR Scanner

* Camera-based QR reading
* Automatic detection
* Overlay targeting UI

### Leaderboard

* Top 3 podium
* Full ranking list
* Role filtering
* Current user highlighting

---

# 🏆 Points & Gamification System

Points are awarded for:

* Event participation
* Session attendance
* Volunteer activities
* Bonus assignments

The leaderboard encourages engagement and adds a competitive element to the event.

---

# 📊 Analytics & Reporting

Admins can monitor:

* Total registrations
* Attendance trends
* University distribution
* Faculty distribution
* Gender breakdown
* Daily entry/exit counts
* Session capacity usage
* Profile completion rates

---

# ⚙ Installation

```bash
# Clone repository
git clone <your-repository-url>

# Navigate to project
cd asu-career-week

# Install dependencies
npm install

# Start development server
npm run dev
```

---

# 🔧 Environment Variables

Create a `.env` file:

```env
VITE_SUPABASE_URL=your_project_url
VITE_SUPABASE_ANON_KEY=your_public_anon_key
```

---

# 🧪 Development Scripts

```bash
npm run dev       # Start development server
npm run build     # Production build
npm run preview   # Preview production build
```

---

# 📈 Scalability Considerations

* Modular role system
* Real-time database updates
* Optimized QR scanning workflow
* Capacity-controlled session booking
* Paginated user management
* Exportable datasets

---

# 🎯 Why This Project Matters

This system demonstrates:

* Full-stack architecture design
* Role-based access control (RBAC)
* Real-time data handling
* QR-based attendance systems
* Dashboard UI/UX architecture
* Event-scale database structuring
* Multi-team operational workflows

It reflects real-world event operations translated into software systems.

---

# 📄 License

This project was built for educational and portfolio purposes.
All rights reserved.
