
# 📋 Feedback Collection System

A full-stack feedback collection system built with **Node.js**, **Express**, **EJS**, and **Vanilla JS**. Allows users to submit feedback for teachers and provides an admin panel to view all submissions.

---

## 🚀 Features

- 📝 Submit feedback through a multi-field form
- 🧠 Client-side & server-side validation
- 📂 Store feedbacks in a local JSON file
- 🔒 Admin panel with access to view all feedbacks
- ✉️ Flash messages for user interactions
- 🎨 Clean and responsive UI using CSS

---

## 📁 Project Structure

```
feedback-system/
├── public/             # CSS and static files
│   └── styles.css
├── views/              # EJS templates
│   ├── index.ejs
│   ├── thankyou.ejs
│   └── admin.ejs
├── routes/             # Express routes
│   └── feedback.js
├── feedbacks.json      # Feedback data (JSON)
├── teachers.json       # List of teachers (JSON)
├── app.js              # Main Express app
├── package.json        # Node dependencies
└── README.md
```

---

## 🔧 Technologies Used

- **Frontend**: HTML, CSS, JavaScript, EJS
- **Backend**: Node.js, Express.js
- **Middleware**: body-parser, express-validator, express-flash, express-session
- **Storage**: Local JSON file

---

## 🛠 Installation

```bash
# Clone the repo
git clone https://github.com/yourusername/feedback-system.git
cd feedback-system

# Install dependencies
npm install

# Start the server
node app.js
```

Visit `http://localhost:3000` in your browser.

---

## 📦 Sample Data

- `teachers.json`: Stores the list of teachers
- `feedbacks.json`: Stores submitted feedbacks

---

## 🔐 Admin Panel

To access feedbacks, visit:

```
http://localhost:3000/admin
```

> 🔒 You can add login-based protection for admin routes (optional enhancement)

---

## 🌐 Deployment

You can deploy it for free using:

- [Render](https://render.com/)
- [Glitch](https://glitch.com/)
- [Railway](https://railway.app/)
- [Vercel](https://vercel.com/) *(if frontend only)*

> Be sure to configure `start` script in `package.json`:
```json
"scripts": {
  "start": "node app.js"
}
```

---

## 📌 To Do / Enhancements

- [ ] Add Admin Login with Username/Password
- [ ] Export Feedbacks to CSV
- [ ] Use MongoDB or Firebase for storage
- [ ] Add charts/graphs in Admin panel
- [ ] Deploy online

---

## 📸 Screenshots

> (Add screenshots here after deployment)

---

## 👨‍💻 Author

**Your Name** — [@yourGitHub](https://github.com/yourGitHub)

---

## 🧪 License

MIT License. Feel free to use, modify, and share.

---
