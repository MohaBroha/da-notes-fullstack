# 📒 DA Notes – Fullstack App (Django + Angular)

Eine moderne Fullstack Notes Anwendung mit Django REST Framework Backend und Angular Frontend.  
Die App ermöglicht das Erstellen, Bearbeiten, Markieren und Löschen von Notizen.

---

## 🚀 Live Repository

👉 https://github.com/MohaBroha/da-notes-fullstack

---

## 🧠 Projektbeschreibung

DA Notes ist eine CRUD-basierte Notizen-App mit klarer Trennung zwischen Backend und Frontend.

- Backend: REST API mit Django & Django REST Framework  
- Frontend: Angular SPA (Standalone Components)  
- Kommunikation erfolgt über HTTP (HttpClient)

---

## 🛠️ Tech Stack

### Backend
- Python
- Django
- Django REST Framework
- django-cors-headers
- SQLite (Development Database)

### Frontend
- Angular
- TypeScript
- SCSS
- HttpClient

---

## ✨ Features

### 📝 Notizen verwalten
- Notiz erstellen
- Notiz anzeigen
- Notiz bearbeiten
- Notiz löschen

### ⭐ Status Funktionen
- Notizen markieren (Favorite)
- Notizen in den Papierkorb (Trash)
- Filterung nach Status:
  - Normal Notes
  - Marked Notes
  - Trash

---

## 🔗 API Endpoints (Backend)

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | `/notes/` | Alle Notizen abrufen |
| POST | `/notes/` | Neue Notiz erstellen |
| PUT | `/notes/<id>/` | Notiz aktualisieren |
| DELETE | `/notes/<id>/` | Notiz löschen |

---

## ⚙️ Installation & Setup

### 🧩 Backend (Django)

cd da_notes_backend  
python -m venv venv  
venv\Scripts\activate (Windows)  
pip install -r requirements.txt  
python manage.py runserver  

Backend läuft auf: http://127.0.0.1:8000/

---

### 🌐 Frontend (Angular)

cd frontend  
npm install  
ng serve  

Frontend läuft auf: http://localhost:4200/

---

## 🔗 Verbindung

Frontend kommuniziert mit Backend über:  
http://127.0.0.1:8000/notes/

---

## 👨‍💻 Autor

MohaBroha
