🚀 Scope Your Project – Gruppe 7

Dieses Repository gehört zur Gruppe 7 des Moduls Scope Your Project (HSLU).
Thema: Releases & Change Management
Ziel ist es, den vollständigen Lebenszyklus von Software-Releases – von der Versionierung bis zum Deployment – praxisnah zu verstehen und zu dokumentieren.

📘 Inhalt

Überblick

Releases & Change Management

Lokales Setup

Projektstruktur

Team

Technologien

Changelog

Lizenz

🧩 Überblick

Das Projekt simuliert und dokumentiert, wie Software-Releases professionell geplant, umgesetzt und verwaltet werden.
Im Fokus stehen:

Automatisierte Versionierung (Semantic Versioning, Git Tags, Release Notes)

Change Control über CHANGELOG & Release Management

Deployment Strategien mit Phasing, Feature Flags & Rollback

Projektressourcen:

📄 Dokumentation (Pages)

📘 GitHub Wiki

🧾 CHANGELOG.md

⚙️ Lokales Setup

Führe folgende Befehle im Terminal aus, um das Projekt lokal zu klonen und auszuführen:

# Repository klonen
git clone https://github.com/HSLU-Exercise/scope-your-project-gruppe_7.git
cd scope-your-project-gruppe_7

# Abhängigkeiten installieren (je nach Projekttechnologie)
npm install     # Node.js
# oder
pip install -r requirements.txt  # Python

# Lokale Entwicklungsumgebung starten
npm run dev
# oder
python app.py

🧱 Projektstruktur
scope-your-project-gruppe_7/
├── .github/              # CI/CD Workflows
├── docs/                 # MkDocs / Dokumentation
├── CHANGELOG.md          # Änderungsverlauf
├── mkdocs.yml            # MkDocs-Konfiguration
├── README.md             # Diese Datei
└── src/                  # (optional) Beispielcode oder Simulation

👥 Team
Name	Rolle	Beschreibung
Ulrich Luca	🧭 Product Owner	Verantwortlich für Vision, Anforderungen & Abnahme der Releases
Nikola Loosli	⚙️ Scrum Master	Moderiert Prozesse, fördert Teamflow & koordiniert Sprints
Nando Manuel Brauchli	🧠 Release Manager / DevOps	Verantwortlich für Versionierung, CI/CD Workflows, Automation & Dokumentation
Joshua Lipp	💻 Technical Writer / Change Coordinator	Dokumentiert Change Requests, pflegt Changelog & Wiki-Struktur
André Bucheli	🧩 QA Engineer / Tester	Testet Deployments, validiert Rollbacks und Release-Stabilität
🧾 Releases & Change Management
🔖 Version Management

Semantic Versioning (1.0.0 → Major.Minor.Patch)

Automatisierte Release Notes via GitHub Actions

Nutzung von Tags zur Releases-Kennzeichnung

🔄 Change Control

Automatisierter CHANGELOG.md

Release Schedule Management

Kommunikation mit Stakeholdern über Wiki / Pages

🚀 Deployment Strategien

Phased Deployment (App-Rollout in Etappen)

Feature Flags (z. B. Beta-Features)

Rollback Capabilities (Fehlerbehebung durch Version Downgrade)

🧮 Technologien

Git & GitHub Actions – CI/CD und automatisierte Releases

MkDocs – Projekt-Dokumentation (Deploy auf Pages)

Markdown – Strukturierte Doku und Wiki-Texte

Python / Node.js – Simulation von Release-Automatisierungen

📜 Changelog

Siehe CHANGELOG.md

Beispiel:

# Changelog
## [1.0.0] – 2025-10-16
- Initiale Struktur erstellt (README, Pages, Wiki)
- Teamrollen definiert
- Basisdokumentation aufgebaut

⚖️ Lizenz

© 2025 HSLU – Scope Your Project (Gruppe 7)
Dieses Projekt dient ausschließlich zu Lern- und Demonstrationszwecken.
