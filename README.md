# Habibi Note App

[![Pitch Deck](https://img.shields.io/badge/Pitch%20Deck-Canva-blue)](https://www.canva.com/design/DAG45TDZGv4/E85-jLj37PX6-odwxJPsAA/edit?utm_content=DAG45TDZGv4&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)

**Frontend:** [Habibi Note App](https://habibi-liart.vercel.app/)  
**Backend:** [API Server](https://xabibi.onrender.com)

---

## Table of Contents
- [Project Overview](#project-overview)  
- [Motivation](#motivation)  
- [Alignment with SDG 4](#alignment-with-sdg-4)  
- [Features](#features)  
- [Technology Stack](#technology-stack)  
- [Project Structure](#project-structure)  
- [Architecture](#architecture)  
- [Installation & Setup](#installation--setup)  
- [Usage](#usage)  
- [Future Roadmap](#future-roadmap)  
- [Contributing](#contributing)  
- [License](#license)  

---

## Project Overview
Habibi Note App is a cloud-based, modern note-taking application built using the **MERN stack (MongoDB, Express, React, Node.js)**. The app enhances learning for students, teachers, and lifelong learners by making note-taking, organization, and collaboration intuitive and effective.  

---

## Motivation
Learners often struggle with:
- Efficiently organizing their notes  
- Accessing educational content from multiple devices  
- Collaborating and sharing knowledge  
- Tracking learning progress  

Habibi Note App addresses these pain points, making learning more organized and accessible.  

---

## Alignment with SDG 4
The app supports **Sustainable Development Goal 4 (Quality Education)** by:
- Providing **accessibility**: Notes are cloud-based and can be accessed anywhere  
- Promoting **inclusivity**: Designed for diverse learners  
- Enabling **collaboration**: Shared notes enhance peer learning  
- Improving **learning outcomes**: Organized notes help learners retain and review information  

---

## Features
- User authentication (Sign Up / Login / Logout)  
- Create, edit, delete notes  
- Categorize and tag notes  
- Search and filter notes  
- Cloud synchronization  
- Offline access  
- Reminders and notifications  
- Collaborative note sharing  
- Responsive design for web and mobile  

---

## Technology Stack
- **Frontend:** React, Tailwind CSS, Vite  
- **Backend:** Node.js, Express.js  
- **Database:** MongoDB  
- **Authentication:** JWT  
- **Hosting:**  
  - Frontend: Vercel ([Live Link](https://habibi-liart.vercel.app/))  
  - Backend: Render ([Live Link](https://xabibi.onrender.com))  

---

## Project Structure

```

habibi-note-app/
├── backend/
│   ├── src/
│   │   ├── config/
│   │   │   └── db.js              # Database connection setup
│   │   ├── models/
│   │   │   └── Notes.js           # Note schema/model
│   │   ├── routes/
│   │   │   └── notes.js           # API routes for CRUD operations
│   │   └── server.js              # Express server setup
│   └── package.json
│
├── frontend/
│   ├── src/
│   │   ├── assets/                # Static assets (images, icons)
│   │   ├── components/
│   │   │   ├── ui/                # Reusable UI components
│   │   │   │   ├── button.jsx
│   │   │   │   ├── card.jsx
│   │   │   │   ├── input.jsx
│   │   │   │   └── textarea.jsx
│   │   │   ├── NewNoteDialog.jsx  # Modal for creating new notes
│   │   │   └── NoteCard.jsx       # Component to display individual notes
│   │   ├── lib/
│   │   │   ├── api.js             # API client for backend communication
│   │   │   └── utils.js           # Utility functions
│   │   ├── pages/
│   │   │   └── Dashboard.jsx      # Main dashboard page
│   │   ├── App.jsx                # Root React component
│   │   ├── main.jsx               # Entry point
│   │   └── index.css              # Global styles
│   ├── vite.config.js             # Vite configuration
│   └── package.json
│
└── README.md

```

---

## Architecture
```

Frontend (React) <---> Backend API (Express/Node.js) <---> MongoDB

````
1. **Frontend:** Handles UI, note creation/editing, and user interactions.  
2. **Backend:** RESTful API for authentication, notes, and CRUD operations.  
3. **Database:** Stores user accounts, notes, and metadata.  

---

## Installation & Setup

### Prerequisites
- Node.js (v18+)  
- npm or yarn  
- MongoDB Atlas or local MongoDB  

### Clone Repository
```bash
git clone <repository-url>
cd habibi-note-app
````

### Backend Setup

```bash
cd backend
npm install
npm run dev
```

* Configure `.env`:

```
MONGO_URI=<Your MongoDB URI>
JWT_SECRET=<Your JWT Secret>
PORT=5000
```

### Frontend Setup

```bash
cd frontend
npm install
npm start
```

* App will run at [http://localhost:3000](http://localhost:3000)

---

## Usage

1. Sign up or log in
2. Create new notes with title, category, and content
3. Edit or delete existing notes
4. Organize notes using categories and tags
5. Share notes with collaborators
6. Search and filter to find specific notes

---

## Future Roadmap

* AI-powered note summarization
* Mobile applications (iOS & Android)
* Multi-language support
* Offline-first functionality
* Integration with educational platforms

---

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/feature-name`)
3. Commit your changes (`git commit -m "Add feature"`)
4. Push the branch (`git push origin feature/feature-name`)
5. Open a Pull Request

---

## License

This project is licensed under the **MIT License**.

---

**Pitch Deck:** [View on Canva](https://www.canva.com/design/DAG45TDZGv4/E85-jLj37PX6-odwxJPsAA/edit?utm_content=DAG45TDZGv4&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)

**Frontend:** [Habibi Note App](https://habibi-liart.vercel.app/)
**Backend:** [API Server](https://xabibi.onrender.com)

```

