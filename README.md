# 🎓 VibeCoding Evaluation Tool

Eine moderne, unterhaltsame Web-Anwendung zur Bewertung akademischer Projekte mit automatischer PDF-Report-Generierung.

## ✨ Features

### 🎨 Entertainment-Elemente:
- **Particle System** mit schwebenden animierten Partikeln im Hintergrund ✨
- **3D Card Flip Effekte** beim Hover über Bewertungskarten 🎴
- **Sound Effects** bei Interaktionen (Klicks, Slider-Bewegungen) 🔊
- **Konfetti-Explosion** beim PDF-Download mit Feuerwerk-Effekt 🎆
- **Emoji-Regen** Animation basierend auf der erreichten Note 🌟
- **Typing Animation** für Titel und Texte ⌨️
- **Pulsing Glow Effects** für wichtige Elemente 💫
- **Dark/Light Mode Toggle** mit smooth Transition 🌓
- **Achievement Badges** beim Erreichen von Meilensteinen 🏆
- **Interactive Progress Ring** mit Prozent-Animation 🎯
- **Shake Animation** bei Fehlern ⚠️
- **Smooth Page Transitions** mit Fade & Slide Effekten 🎬
- **Responsive Design** für alle Geräte 📱

### 📊 Funktionale Features:
- Strukturierte Rubrik-basierte Bewertung (70 Punkte System)
- Studentendaten-Erfassung (Name, Matrikelnummer)
- Kommentarfunktion für jede Kategorie
- Automatische Notenberechnung
- PDF-Report-Generierung mit professionellem Design
- Dockerized Application für einfaches Deployment

## 🚀 Installation & Start

### Option 1: Mit Docker (Empfohlen)
```bash
docker-compose up
```

### Option 2: Lokal
```bash
# Abhängigkeiten installieren
pip install -r requirements.txt

# Anwendung starten
python app.py
```

Öffne deinen Browser und gehe zu: `http://localhost:5000`

## 📋 Bewertungskategorien

### Report (40 Punkte):
1. **Introduction** (5 Punkte)
2. **Project Overview & Objectives** (5 Punkte)
3. **System Requirements** (5 Punkte)
4. **Core Functionality & Feature Implementation** (10 Punkte)
5. **System Design** (5 Punkte)
6. **Results, Challenges & Discussion** (5 Punkte)
7. **Outlook** (5 Punkte)

### Application (30 Punkte):
8. **Feature Completeness + Working** (10 Punkte)
9. **User Interface Design + Usability** (8 Punkte)
10. **Code Quality & Documentation** (4 Punkte)
11. **Containerized DevOps** (6 Punkte)
12. **Testing & Reliability** (2 Punkte)

## 🎯 Verwendung

1. **Studentendaten eingeben**: Name und Matrikelnummer
2. **Bewertung durchführen**: Slider für jede Kategorie anpassen
3. **Kommentare hinzufügen**: Feedback für jede Kategorie
4. **Echtzeit-Übersicht**: Automatische Berechnung der Gesamtpunktzahl
5. **PDF generieren**: Button klicken und Report herunterladen 🎉

## 🛠️ Technologie-Stack

- **Backend**: Flask (Python)
- **Frontend**: HTML5, CSS3, JavaScript (Vanilla)
- **PDF-Generierung**: ReportLab
- **Containerization**: Docker & Docker Compose
- **Design**: Modern Glassmorphism UI mit Animationen

## 📦 Projektstruktur

```
WEB-APP/
├── app.py                 # Flask Backend
├── templates/
│   └── index.html        # Frontend UI
├── static/               # Statische Dateien (falls benötigt)
├── requirements.txt      # Python Dependencies
├── Dockerfile           # Docker Configuration
├── docker-compose.yml   # Docker Compose Setup
└── README.md           # Diese Datei
```

## 🎨 Design-Highlights

- **Farbschema**: Lila-Blau Gradient (#667eea → #764ba2)
- **Animationen**: Fade-in, Slide, Float, Confetti
- **Responsive**: Mobile-First Design
- **Accessibility**: Klare Kontraste und intuitive Navigation

## 📝 Notensystem

- **90-100%**: Excellent (1.0-1.3)
- **80-89%**: Very Good (1.7-2.3)
- **70-79%**: Good (2.7-3.3)
- **60-69%**: Satisfactory (3.7-4.0)
- **<60%**: Fail (5.0)

## 👥 Kontakt

- **Atezaz Ahmad**: ahmad@sd.uni-frankfurt.de
- **Hendrik Drachsler**: h.drachsler@dipf.de

## 📅 Wichtige Termine

- **Abgabe**: 03.03.2026
- **Präsentationen**: 04.02.2026 & 11.02.2026

---

**Viel Erfolg bei deiner Präsentation! 🎓✨**
