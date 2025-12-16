# 🧾 ResuCraft

**ResuCraft** is a modern and intuitive **Resume Writer & Manager** built with **Qt (C++ / Qt Widgets)**.  
It allows users to **create, edit, and manage multiple resumes**, and export them to professional **PDF documents** — all in one simple interface.

---

## 🌟 Key Features

### 🧍 Manage Multiple People

- View all saved profiles in the **left pane (10%)**
- Easily **switch**, **edit**, or **add** new people
- All data is stored locally in an **SQLite database**

---

### 🧩 Resume Sections

#### 🖊️ Middle Pane (60%)

Main resume details and career information:

- **Name**
- **Short Bio** (up to 100 words)
- **Employment History**
  - Position
  - Company
  - Location
  - Dates (From – To)
  - Duties
- **Education**
  - Course
  - Institution
  - Dates (From – To)
- **Referees**
  - Name
  - Organization
  - Contact

✅ Employment, Education, and Referees sections are **dynamic** — unlimited entries supported.

---

#### 📜 Right Pane (30%)

Profile and personal details:

- **Profile Picture**
- **Career / Profession**
- **Nationality**
- **Contact**
- **Email**
- **Physical Address**

Other sections:

- **Skills** (up to 5, each with name and progress bar)
- **Achievements** (unlimited)
- **Languages** (unlimited, with proficiency levels)

---

## 🎨 Themes

ResuCraft supports up to **5 selectable themes**, configurable from **Settings**.

| Theme | Primary Color | Accent Color |
|------|---------------|--------------|
| Classic Blue | #1565C0 | #0D47A1 |
| Emerald Green | #2E7D32 | #1B5E20 |
| Royal Purple | #6A1B9A | #4A148C |
| Sunset Orange | #EF6C00 | #E65100 |
| Slate Gray | #455A64 | #263238 |

Each theme updates the app’s color scheme dynamically.

---

## 🧱 Database Design (SQLite)

**Database:** `resucraft.db`

| Table | Purpose | Important Fields |
|------|--------|----------------|
| people | Base info | id, name, bio, picture, career, nationality, contact, email, address |
| employment | Work history | id, person_id, position, company, location, from_date, to_date, duties |
| education | Academic background | id, person_id, course, institution, from_date, to_date |
| referees | References | id, person_id, name, organization, contact |
| skills | Skills | id, person_id, skill_name, skill_level |
| achievements | Achievements | id, person_id, achievement_text |
| languages | Languages | id, person_id, language_name, proficiency |

---

## 🧰 Tech Stack

- **Language:** C++
- **Framework:** Qt 5 (Qt Widgets)
- **Database:** SQLite (QSqlDatabase / QSqlQuery)
- **PDF Export:** QPdfWriter or QPrinter
- **Theme Styling:** Qt Style Sheets (QSS)

---

## 🚀 App Workflow

1. Start App → Load all people into the left pane
2. Select Person → Details appear in middle and right panes
3. Edit Mode → Enable editing and adding entries
4. Save → Data is written to the database
5. Add New → Open a blank resume template
6. Export PDF → Generate a clean, professional PDF resume
7. Settings → Change application theme

---

## 🧭 Future Enhancements

- Resume templates for PDF export
- Profile picture cropping tool
- Import / export `.rcv` (ResuCraft Resume) files
- Cloud backup and sync
- AI-powered resume suggestions (optional)

---

## 🪄 Developer Notes

**ResuCraft** is designed for simplicity and clarity.  
All code prioritizes **readability and maintainability**, making it suitable for both beginners and experienced Qt developers.

---

## 🧑‍💻 Author

- **Project:** ResuCraft
- **Developer:** Njagi
- **Language:** C++ / Qt 5
- **Goal:** Smart, customizable, offline resume writer

---