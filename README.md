# SaqrEye — Explore Saudi Arabia

SaqrEye is a persona-based web platform that lets you explore Saudi Arabia through two lenses — as a **Tourist** or an **Investor**. Each persona gets a tailored experience showcasing the most relevant cities, destinations, and Vision 2030 projects.

---

##  Features

- **Persona System** — Choose between Tourist or Investor for a personalized experience
- **Bilingual** — Full Arabic (RTL) and English (LTR) support
- **Dark / Light Mode** — Smooth theme switching saved in localStorage
- **Responsive Design** — Works seamlessly on all screen sizes
- **Cookie-based Memory** — Persona and language preferences are remembered

---

## Built With

- **HTML & CSS**
- **Bootstrap 5**
- **Django**

---

## Setup


# Clone the repo
git clone https://github.com/3li-507/SaqrEye.git
cd SaqrEye

# Create & activate virtual environment
python -m venv venv
venv\Scripts\activate      # Windows
source venv/bin/activate   # Mac/Linux

# Install dependencies
pip install django

# Run the server
python manage.py runserver


Then open your browser at **http://127.0.0.1:8000/**