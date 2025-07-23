# RoboCar Info Dashboard

Ein interaktives 3D-Dashboard zur Visualisierung und Erkundung von Roboterkomponenten auf einem Raspberry Pi-basierten Fahrzeug.

🌐 **Live-Demo**: [https://20korvin01.github.io/RoboCarInfoDashboard/](https://20korvin01.github.io/RoboCarInfoDashboard/)

## 🧾 Projektüberblick

Das Dashboard wurde im Rahmen der Veranstaltung *“Visualization of Geodata in 2D, 3D and 4D”* am KIT entwickelt. Es erlaubt die interaktive Erkundung von Komponenten eines RoboCars über ein Web-Interface mit 3D-Modell, Hover-Effekten und gezielter Kameranavigation.

## 🚀 Features

- Interaktive 3D-Visualisierung mit Three.js
- Hover- und Klick-Interaktion für Komponenten
- Dynamische Kamerasteuerung
- Info-Panels mit technischen Details
- Responsive Webdesign

## ⚙️ Technologien

- HTML5, CSS3, JavaScript (ES6+)
- Three.js für 3D-Darstellung
- Bootstrap Icons für UI-Elemente

## 🛠️ Bedienung

- **Maus**: Drehen & Zoomen des Modells
- **Komponenten klicken**: Fokus & Infoanzeige
- **Dropdowns**: Direkte Navigation zu Bauteilen

## 📂 Projektstruktur


```
RoboCarInfoDashboard/
├── index.html
├── model.js
├── dropdown.js
├── style.css
├── model/ # Enthält das 3D-Modell (OBJ/MTL/Texturen)
└── img/ # Komponentenbilder
```


## 🧪 Lokale Nutzung

1. Projekt herunterladen oder clonen  
2. Mit Live Server oder lokalem Webserver starten  
3. `index.html` im Browser öffnen

## 🧹 Hinweise

- 3D-Modell stammt aus photogrammetrischen Scans (Scaniverse, Metashape)
- Vorverarbeitung und Ausrichtung mit CloudCompare
- Hosting via GitHub Pages

## 👤 Autor

Korvin Brecht  
[GitHub-Profil](https://github.com/20korvin01)

---

**Lizenz**: Dieses Projekt dient ausschließlich Lehr- und Demonstrationszwecken.
