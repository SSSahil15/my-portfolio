# Sahil Ansari | Cybersecurity Portfolio 🛡️

A professional, fully responsive portfolio website built to showcase my transition and expertise in the cybersecurity domain. This project is heavily themed with a "cyber/terminal" aesthetic—focusing on a clean, glassmorphic layout mixed with neon-green accents, mimicking modern security dashboards.

## 🚀 Features

* **Cyber/Terminal Aesthetic**: Dark themes, typing-writer effects, neon borders, and dynamic glowing glass-panels.
* **Responsive Architecture**: Fully responsive grid systems using CSS Flexbox and Grid.
* **Component-Based Pages**:
  * **Home (`/`)**: Hero section with interactive particle backgrounds.
  * **About (`/about`)**: Features custom terminal layouts, HackTheBox/TryHackMe stats, and a dynamic timeline.
  * **Skills (`/skills`)**: Clean 2x2 badge-based dashboard classifying skills (Security, Tools, Programming, Platforms).
  * **Projects (`/projects`)**: Highlight of tools written/configured strictly for ethical hacking operations.
  * **Experience (`/experience`)**: System administration and specialized security training timeline.
  * **Certificates (`/certs`)**: Verified training certificates externally linked.
  * **Hire Me (`/hire-me`)**: A structured professional proposal specifically for Penetration Tester & Security Researcher roles.
  * **Contact (`/contact`)**: Secure email transmission portal.

## 💻 Tech Stack

* **Backend**: Python 3, Flask
* **Frontend**: HTML5, Vanilla CSS3 (Custom Variables), Vanilla JavaScript
* **Assets**: Feather Icons, Particles.js

## ⚙️ Running Locally

1. **Clone the repository** (if hosted via git) or navigate into the directory:
   ```bash
   cd "sa portfolio"
   ```

2. **Set up a Virtual Environment**:
   ```bash
   python3 -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install Dependencies**:
   ```bash
   pip install Flask
   ```

4. **Run the Application**:
   ```bash
   python3 app.py
   ```
5. **Access the portal**: Open a browser and navigate to `http://127.0.0.1:5000`.

## 📁 Directory Structure

```text
sa portfolio/
├── app.py                 # Main Flask application and routing logic
├── static/
│   ├── css/
│   │   └── style.css      # Core cybersecurity stylesheet
│   └── js/
│       └── script.js      # Frontend interaction logic
└── templates/             # Jinja2 HTML Templates
    ├── base.html          # Base layout wrapper (Navbar/Footer)
    ├── index.html         # Homepage
    ├── about.html         # Whoami & Profiles Stats
    ├── skills.html        # Custom skill badges
    ├── projects.html      # External repository links
    ├── experience.html    # Timeline logic
    ├── certs.html         # Live credentials
    ├── hire_me.html       # Landing page for recruiters
    └── contact.html       # Contact form logic
```

## 🤝 Let's Connect
Feel free to initialize a connection or reach out on [LinkedIn](https://www.linkedin.com/in/-sahil/). 
**Focus:** *Break it. Understand it. Secure it.*
