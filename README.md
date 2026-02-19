# 📘 MTET Midterm Examination Timetable Dashboard

An elegant, interactive web dashboard that allows users to **input, manage, and export midterm examination schedules** with a modern animated interface.

This project is built as a **single-file lightweight application** using HTML, Tailwind CSS, IndexedDB, and client-side PDF generation — making it fast, portable, and beginner-friendly.

---

## ✨ Overview

The MTET Midterm Examination Timetable Dashboard helps students and academic staff:

* Prompt and capture exam details
* Automatically display organized schedules
* Persist data locally using IndexedDB
* Export the timetable as a professional PDF

Everything runs **100% in the browser** — no backend required.

---

## 🚀 Key Features

* 🧠 Prompt-driven timetable entry
* 🎨 Modern animated UI with Tailwind CSS
* 💾 Local storage using IndexedDB
* 📅 Structured timetable dashboard
* 📄 One-click PDF export with custom filename
* 📱 Fully responsive layout
* ⚡ Single-file lightweight architecture

---

## 🛠️ Technologies Used

* **HTML5** — Structure
* **Tailwind CSS (CDN)** — Styling and animations
* **Vanilla JavaScript** — Application logic
* **IndexedDB** — Local persistent storage
* **html2pdf.js** — Client-side PDF generation

---

## 📂 Project Structure

This project intentionally uses a **single-file architecture** for simplicity and portability:

```
project-root/
└── index.html   # Complete application (UI + Logic + Storage)
```

No additional folders or backend services are required.

---

## ⚙️ How the System Works

### 1️⃣ User Input

The user fills the form:

* Day name
* Date (DD-MM)
* Time
* Course
* Group

After submission:

✅ Data is validated
✅ Time is converted to AM/PM
✅ Record is stored in IndexedDB
✅ Dashboard updates automatically

---

### 2️⃣ Local Database

The app creates:

```
Database: ScheduleDashboardDB
Object Store: schedules
Key: auto-increment id
```

This allows:

* Persistent storage
* Offline usage
* Fast retrieval

---

### 3️⃣ Dashboard Rendering

When the page loads:

* The system reads all saved schedules
* Dynamically generates animated rows
* Shows empty state if no data exists

---

### 4️⃣ PDF Export

When **Download PDF** is clicked:

1. User is prompted for filename
2. System captures the timetable
3. Generates high-quality PDF
4. Automatically downloads

---

## ▶️ How to Run

### ✅ Direct Open (Simplest)

Just open:

```
index.html
```

in any modern browser.

---


## 💡 Usage Guide

1. Open the dashboard
2. Fill the exam details form
3. Click **Add to Dashboard ✦**
4. View organized schedule below
5. Click **Download PDF** when needed

---

## 🔒 Data Persistence

* Data is stored locally in the browser
* No internet required after first load
* Clearing browser storage will remove records

---

## 🎯 Design Goals

This project was built to be:

* Beginner-friendly
* Visually modern
* Lightweight
* Fully client-side
* Easy to extend

---

## 🚧 Possible Future Improvements

* Edit/Delete schedule entries
* Search and filtering
* Dark mode toggle
* Cloud synchronization
* Multi-timetable support
* Authentication layer

---

## 🤝 Contribution

Contributions, suggestions, and improvements are welcome.

If you plan to extend the system:

* Keep the UI clean
* Maintain single-file simplicity (if possible)
* Follow readable JavaScript practices

---

## 📜 License

This project is open for educational and academic use.

---
"