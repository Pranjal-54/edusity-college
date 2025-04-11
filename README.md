🎓 Edusity - College Website
A responsive, single-page college website built using React and Tailwind CSS. Designed to enhance a college’s digital presence by providing intuitive access to course listings, faculty profiles, event updates, and announcements—all in a sleek, modern interface.

Features
•	- Single Page Application (SPA) with React Router
•	- Searchable and Filterable Courses
•	- Faculty and Department Listings
•	- Upcoming Events and Announcements
•	- Mobile-First Responsive Design
•	- Tailwind CSS Utility-Based Styling
•	- HTTPS Secure Deployment (Netlify)

Tech Stack
•	React: Component-based UI
•	Vite: Fast development build tool
•	Tailwind CSS: Styling and layout
•	React Router DOM: SPA routing
•	Netlify: Hosting & deployment
•	Firebase (Planned): Notifications via FCM

Project Structure

edusity-college/
├── public/                # Static assets
├── src/
│   ├── components/        # UI components (Navbar, Footer, etc.)
│   ├── pages/             # Route-based views (Home, Courses, Events)
│   ├── App.jsx            # Main routing and layout
│   └── main.jsx           # Entry point
├── tailwind.config.js     # Tailwind configuration
├── vite.config.js         # Vite configuration
└── package.json           # Project metadata and dependencies

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
