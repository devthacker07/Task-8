# Simple Blog Layout – Task 8

A responsive blog page built with **Bootstrap 5** that demonstrates how to combine Bootstrap components with custom CSS to create an attractive, mobile‑first layout.

---

##  Features

| Area | Details |
|------|---------|
| **Framework** | Bootstrap 5 (via CDN) |
| **Layout** | Responsive grid with collapsible navbar, blog‑post cards, and footer |
| **Components** | Navbar brand & links, card decks for posts, footer with social icons |

---

##  Project Structure

```text
Task‑8/
├── index.html
├── assets/
│   ├── css/
│   │   └── style.css
│   └── js/
│       └── script.js
└── images/
    └── … (blog post thumbnails)
```

*If you downloaded `Task 8.zip`, simply extract it to reveal the above tree.*

---

##  Getting Started

1. **Clone or download** this repository (or unzip **Task 8.zip**).
2. Open `index.html` in any modern browser – no build steps are required because all dependencies are loaded from CDNs.

```bash
# example
unzip Task\ 8.zip
cd Task-8
open index.html   # macOS
# or
start index.html  # Windows
```

---

##  What I Implemented

| Step | Explanation |
|------|-------------|
| **1. Bootstrap CDN** | Added `<link>` & `<script>` tags for Bootstrap CSS, JS, and Popper in the `<head>` / end of `<body>`. |
| **2. Navbar** | Created a dark, sticky‑top navbar with brand name and menu links; collapses into a hamburger on small screens. |
| **3. Blog Cards** | Used Bootstraps’s **card** component inside a responsive grid – each card holds an image, title, excerpt, and “Read more” button. |
| **4. Footer** | Simple footer with © text and Font Awesome social icons. |
| **5. Custom CSS** | Added `style.css` to: <br>• apply a diagonal gradient background <br>• give cards a glass effect (blur & transparency) <br>• add smooth hover lift animation <br>• tweak typography & spacing. |
| **6. Clean JS (optional)** | A tiny `script.js` file shows an example scroll‑to‑top button; feel free to extend it. |

---
