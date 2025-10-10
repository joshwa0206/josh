# 📰 IBM-FE Blog (Simple)

A **single-page blog web app** built using **HTML, CSS, and JavaScript**, featuring a simple **comment system** powered by browser `localStorage`.

This project was developed as part of the **IBM Front-End Development** exercise.

---

## 🚀 Features

- 🏠 **Home Page:** Displays a list of blog posts with search functionality.  
- ✍️ **Post Detail View:** Read full content of any post.  
- 💬 **Comments Section:** Add, view, and store comments per post (persisted locally).  
- 👤 **Login Simulation:** Simple name-based login using `localStorage`.  
- 🔍 **Search Posts:** Real-time filtering of posts by title, author, or excerpt.  
- 📱 **Responsive Design:** Works smoothly across mobile and desktop screens.  

---

## 🧱 Tech Stack

| Component | Technology |
|------------|-------------|
| Structure | HTML5 |
| Styling | CSS3 (with custom variables and responsive design) |
| Logic & Data | Vanilla JavaScript |
| Storage | Browser `localStorage` |

---

## 🧩 File Structure

---

## ⚙️ How It Works

1. **Posts** are pre-defined in the script (no backend).
2. **Comments** are stored locally:
   - Each post’s comments are saved under `comments_<postId>` in `localStorage`.
3. **Login system** stores the username under the key `simple_blog_user`.
4. **XSS Protection:** User inputs are escaped before display.

---

## 🪄 Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/joshwa0206/josh
2. Deployment:
   '''bash
   git clone
 https://joshwa0206.github.io/josh/
