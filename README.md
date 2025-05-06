# 📚 Docs & Notes Manager


[![Live Demo](https://img.shields.io/badge/Visit-Website-blue?style=for-the-badge&logo=github)](https://bharat346.github.io/Docs_and_Notes/#/)

A modern web application for managing documentation and personal notes with GitHub integration.

## ✨ Features

- **Admin Dashboard** – Secure management interface  
- **Markdown Support** – Rich formatting for notes/docs  
- **GitHub Backend** – All content stored in GitHub repository  
- **CRUD Operations** – Create, Read, Update, Delete functionality  
- **Responsive Design** – Works on all devices  

## 🏗️ Project Structure

```bash
/src/
├── admin/
│   ├── dashboard/     # Admin control panel
│   ├── addBlog/       # Documentation creation
│   └── manager/       # Content management
│
├── notes/
│   ├── addNotes/      # Note creation interface
│   ├── manager/       # Note organization
│   └── view/          # Note viewing
│
├── /              # Common documentation files
│   ├── showBlogs/     # Documentation viewer
│   └── ...            # Other doc components
│
└── hooks            # Shared components
```

## 🚀 Getting Started

### Prerequisites

- **Node.js** v18+
- GitHub account
- GitHub Personal Access Token

---

### 📦 Installation

```bash
git clone https://github.com/yourusername/Docs_and_Notes.git
cd Docs_and_Notes
npm install
```

## ⚙️ Configuration

Create a `.env` file in the root directory and add the following:

```env
VITE_GITHUB_TOKEN=your_github_token
VITE_GITHUB_OWNER=your_username
VITE_GITHUB_REPO=Docs_and_Notes
```

## ▶️ Running Locally

To start the project locally:

```bash
npm run dev
```
---
## 🚀 Deployment

To build and deploy the project:

```bash
npm run build
npm run deploy
```

---

## 🔒 Admin Access

Access the admin dashboard at /admin — protected via password authentication.
( This will Run on localHost )

## 🛠️ Built With
React – Frontend library

Vite – Lightning-fast build tool

GitHub API – Backend storage and versioning

Tailwind CSS – Styling and UI design

---

## 🤝 Contributing
Want to contribute? Follow these steps:

1. Fork the project

2. Create your feature branch:

```bash
git checkout -b feature/AmazingFeature
```
3. Commit your changes:

```bash
git commit -m "Add some amazing feature"
```
4. Push to the branch:

```bash

git push origin feature/AmazingFeature
```
5. Open a Pull Request
