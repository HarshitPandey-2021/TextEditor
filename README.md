# 📝 Online Text Editor (ASP.NET MVC)

A secure and intuitive text editor web app built using the MVC pattern in C#. Users can register, log in, and manage their documents — including creating, editing, and deleting notes. All documents are saved locally, with access protected via authentication.

---

## ✨ Features

- ✅ Create, edit, and delete personal documents
- 🔐 User authentication with session management
- 💾 Local file saving with ID-based retrieval
- 🧠 MVC pattern: clean separation of logic, UI, and backend
- 📱 Responsive layout for desktop and mobile use

---

## 🧰 Tech Stack

| Layer       | Technology Used         |
|-------------|--------------------------|
| Language    | C#                       |
| Framework   | ASP.NET MVC              |
| Frontend    | Razor Views, HTML, CSS   |
| Auth        | Session-based login      |
| Tools       | Visual Studio, Git, GitHub |

---

## 📁 Project Structure

```bash
TextEditorr/
├── Controllers/
│   └── TextEditorController.cs
├── Models/
│   └── DocumentModel.cs
├── Views/
│   ├── Login.cshtml
│   ├── Dashboard.cshtml
│   └── Edit.cshtml
├── wwwroot/
│   └── css/...
├── Program.cs
├── Startup.cs
└── README.md


🚀 Getting Started
1. Clone the repository
bash
Copy
Edit
git clone https://github.com/HarshitPandey-2021/TextEditor.git
cd TextEditor/TextEditorr

2. Open in Visual Studio
Restore NuGet packages

Add your local DB or JSON-based file persistence (if needed)

3. Run the app
bash
Copy
Edit
dotnet run

🧠 What I Learned
Implementing MVC structure in real web apps

Handling login/logout functionality securely

Building a full-stack CRUD app from scratch

📜 License
MIT License — open to use, modify, and improve

👨‍💻 Author
Created by Harshit Pandey
