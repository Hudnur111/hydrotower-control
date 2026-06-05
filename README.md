# Hydrotower — Steuerung, Sensorik & Aktorik

![GitHub Release](https://img.shields.io/github/v/release/hudnur111/hydrotower-control?style=for-the-badge&color=2ecc71)
![GitHub Repo size](https://img.shields.io/github/repo-size/hudnur111/hydrotower-control?style=for-the-badge&color=3498db)
![GitHub License](https://img.shields.io/github/license/hudnur111/hydrotower-control?style=for-the-badge&color=e67e22)
![GitHub Last Commit](https://img.shields.io/github/last-commit/hudnur111/hydrotower-control?style=for-the-badge&color=9b59b6)

Professionelles, automatisiertes Hydroponik-System mit intelligenter Steuerung, präziser Sensorik und automatisierter Aktorik.

---

## 🌿 Repository-Struktur & Branches

Die Entwicklung dieses Projekts ist in spezialisierte Bereiche unterteilt. Bitte wechsle in den entsprechenden Branch, um am jeweiligen Modul zu arbeiten:

### 1. `main` (Production)
![Branch main](https://img.shields.io/badge/Branch-main-brightgreen?style=flat-square)
* **Fokus:** Allgemeine Dokumentation, Systemarchitektur, Release-Notes und Lizenzübersicht.

### 2. `ui` (Benutzeroberfläche)
![Branch ui](https://img.shields.io/badge/Branch-ui-blue?style=flat-square)
* **Fokus:** GUI und Dashboard zur Echtzeit-Visualisierung der Sensordaten und manuellen Steuerung der Aktoren.
* **Tech-Stack:** ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) 
  ![Tkinter](https://img.shields.io/badge/UI-Tkinter-blueviolet?style=flat-square)
* 🔗 [Zum UI Branch wechseln](../../tree/ui)

### 3. `hardware-code` (Embedded Firmware)
![Branch hardware](https://img.shields.io/badge/Branch-hardware--code-orange?style=flat-square)
* **Fokus:** Firmware für die Mikrocontroller, Auslesen der Sensorik (pH, EC, Füllstand) und Schalten der Relais (Pumpen, Licht).
* **Tech-Stack:** ![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)
  ![ESP32](https://img.shields.io/badge/Hardware-ESP32-red?style=flat-square)
* 🔗 [Zum Hardware Branch wechseln](../../tree/hardware-code)

### 4. `gh-pages` (Projekt-Webseite)
![GitHub Pages Deployment](https://img.shields.io/github/actions/workflow/status/hudnur111/hydrotower-control/pages/pages-deployment?style=flat-square&label=Deployment)
* **Fokus:** Automatisch bereitgestelltes Web-Interface zur Live-Ansicht des Projektstatus.
* 🌐 **Live-Link:** [hudnur111.github.io/hydrotower-control](https://hudnur111.github.io/hydrotower-control/)

---

## 🛠️ Schnellstart

### 1. Repository klonen
```bash
git clone [https://github.com/hudnur111/hydrotower-control.git](https://github.com/hudnur111/hydrotower-control.git)
cd hydrotower-control
