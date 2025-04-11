# 🎓 Edusity - College Website

A responsive, single-page college website built using **React** and **Tailwind CSS**.  
It enhances a college’s digital presence by providing intuitive access to **courses**, **faculty profiles**, **event updates**, and **announcements**—all with a modern UI.

---

## ✨ Features

- ⚛️ Single Page Application (SPA) with React Router
- 🔍 Searchable and Filterable Courses
- 👨‍🏫 Faculty and Department Listings
- 📅 Event Announcements and Updates
- 📱 Fully Responsive Design (Mobile-First)
- 🎨 Tailwind CSS Utility-Based Styling
- 🔒 Secure HTTPS Deployment via Netlify

---

## 🛠 Tech Stack

| Technology            | Purpose                          |
|------------------------|----------------------------------|
| **React**              | Component-based UI               |
| **Vite**               | Fast build tool and dev server   |
| **Tailwind CSS**       | Utility-first styling framework  |
| **React Router DOM**   | SPA navigation                   |
| **Netlify**            | Deployment platform              |
| **Firebase (Planned)** | Notifications via FCM            |

---

## 📁 Project Structure

```bash
edusity-college/
├── public/                # Static assets
├── src/
│   ├── components/        # UI components (Navbar, Footer, etc.)
│   ├── pages/             # Route-based views (Home, Courses, Events)
│   ├── App.jsx            # Main layout and routing
│   └── main.jsx           # Entry point
├── tailwind.config.js     # Tailwind configuration
├── vite.config.js         # Vite configuration
└── package.json           # Project dependencies


Getting Started
•	- Clone the Repository: git clone https://github.com/pranjal-54/edusity-college
•	- Install Dependencies: npm install
•	- Start Development Server: npm run dev
•	- Build for Production: npm run build

Functional Modules
•	Navigation System: Smooth in-app routing via React Router, persistent navbar, custom 404 route
•	Course Explorer: Search/filter options, responsive grid layout, API ready
•	Event Updates: List display of events, future-ready for Firebase notifications

Non-Functional Goals
•	- Loads in <3 seconds on broadband
•	- Cross-platform browser compatibility
•	- Modular and maintainable design
•	- Optimized for future backend integration

Design Constraints
•	- React + Vite frontend stack
•	- Tailwind CSS for UI consistency
•	- SPA-compliant architecture
•	- No backend/database in current release

Planned Enhancements
•	- Backend integration (MongoDB/Express)
•	- Role-based access for admin updates
•	- Multi-language support
•	- Analytics integration (Google Analytics)
•	- Event notifications with Firebase FCM


License
This project is open for educational and personal use under the MIT License.
