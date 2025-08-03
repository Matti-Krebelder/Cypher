# Cypher – Web & Surveillance Intelligence Tool

**Entwickelt von [Fsociety00.com](https://fsociety00.com)  
Projektleitung: Matti Krebelder**

---

## ⚠️ Hinweis

Cypher ist ein rein **ethisches, forensisches Analyse- und Testtool**, das ausschließlich zu **legalen Zwecken** entwickelt wurde. Jeder Missbrauch zu illegalen oder nicht genehmigten Zwecken ist strengstens untersagt.

---

## 🌐 Funktionen: "Scan the Web"

`scan the Web` ist ein zentraler Bestandteil von Cypher. Es durchsucht in Echtzeit das Internet (Clearnet, Deep Web & Darknet) nach illegalen Inhalten und reportet diese automatisiert:

- Kindesmissbrauch / CSAM (Child Sexual Abuse Material)
- Scam- und Phishing-Webseiten
- Menschenhandel-Listings
- Botnet Command & Control Server
- Illegale Drogenmärkte
- Terroristische Kommunikation & Propaganda
- Betrügerische Online-Shops
- Finanzbetrug (Fake Investment Plattformen, Crypto Rugpulls)
- Leaked Credential Dumps / Datenbanken
- Ransomware Distribution Nodes
- Malware-Distribution (z. B. über Malvertising)

> Cypher nutzt eine Kombination aus KI-gestützter Mustererkennung, Hash-Vergleich, Realtime-Linkgraphen und OSINT-Techniken.

---

## 🛰 Globale Echtzeitüberwachung

Cypher greift in Echtzeit auf Datenströme aus über 15 Kategorien zu:

- **>8.000 Satelliten-Feeds** (u.a. Wetter, Umwelt, EO)
- **10.000+ Flugzeuge weltweit** (ADS-B, ICAO)
- **100.000+ maritime Objekte** (AIS-Daten)
- **ISS Live-Tracking** mit Bahnverlauf & Koordinaten
- **>400.000 Webcams weltweit** (Livecams, Verkehrsfeeds, Städte, Natur)
- **Öffentliche Verkehrsdaten global** (Zug, Metro, Bus – je nach Region in Echtzeit)
- **Globale NEWS RSS FEEDS**

Alle Feeds werden automatisiert aggregiert, verarbeitet und gespeichert.

---

## 🤖 KI, Automatisierung & Anti-Bot-Techniken

Cypher setzt an mehreren Stellen KI und Automatisierungslogik ein:

- **Objekterkennung & Bildanalyse** mittels YOLOv8, OpenCV, DETR, Color Match KI
- **Adaptive Entscheidungslogik** zur Priorisierung von Funden (Relevanz, Risikobewertung)
- **Cloudflare & Bot-Protection Bypass** Advanced Protection durch Random Proxys / Advanced Cloudflare Bypasses...
- **Human Behavior Simulation** (Mouse Movement, Delay Injection, Randomized Headers)
- **Erweiterbares Modul-System**

Zudem nutzt Cypher ein integriertes Task-Scheduling-System, das alle relevanten Datenquellen automatisch und zyklisch abruft.

---

## 🔍 Visuelle Erkennung & Webcam-Suche

Cypher kombiniert Deep Learning mit globalem Webcam-Zugriff. Beispiel: Ein Nutzer sucht ein „schwarzes Auto“ – das System identifiziert relevante Merkmale im Bild und durchsucht weltweit Live-Webcams:

- Verkehrskameras
- Parkplätze
- Straßenzüge
- Flughafenzufahrten

Treffer werden mit **Screenshot, Koordinaten & Zeitstempel** dokumentiert.

**Unterstützte visuelle Suchanfragen:**

- Fahrzeuge (Typ, Marke, Farbe)
- Kleidung, Bewegung, Tiere, Drohnen
- Personen (nur autorisierte Test-Szenarien)
- Nummernschilder (wenn technisch und rechtlich möglich)

**Datenschutz:** Keine privaten CCTV-Kameras, nur öffentlich zugängliche Quellen. Alle Objekte werden anonymisiert.

---

## 🧠 Social Engineering KI (Ethical Use Only)

Cypher enthält eine experimentelle Social Engineering-KI für **Awareness-Tests** und autorisierte Sicherheitsprüfungen:

- Simulierte Chatdialoge (WhatsApp, Telegram, Instagram)
- Generierung realistischer menschlicher Antwortmuster
- Soziale Profilanalyse (öffentlich zugängliche Accounts)
- Phishing-Szenarien für Schulungszwecke

⚠️ **Keine echte Interaktion mit realen Zielpersonen. Kein Zugriff auf private Accounts oder sensible Daten.**

---

## 🧩 Systemübersicht & Funktionen

Cypher besteht aus modularen Analyse- und Datenerfassungseinheiten:

### 🌍 Zugriff auf FBI Datenbank für Gesuchte Personen
- Beschreibung der Person


### 🌍 Standort & Geodaten
- Konvertiert Adressen in GPS-Koordinaten
- Liefert genaue Ortsangaben (Reverse Geocoding)

### 🚢 Schiffstracking
- Verfolgt maritime Bewegungen
- Suche nach MMSI, Namen oder Position

### ✈️ Flugverfolgung
- Echtzeitdaten von Verkehrs- & Privatflugzeugen
- Speicherung von Flugrouten

### 📸 Webcam-Auswertung
- Extrahiert Livebilder aus Streams
- Erkennung & Kategorisierung von Inhalten

### 🧠 Bilderkennung & Farbzuordnung
- Identifiziert Objekte & Farben in Bildern
- KI-gestützte Analyse (YOLO, DETR)
- Entfernung redundanter Erkennungen

### 👤 Personenrecherche
- Sucht nach Personen in Online-Quellen (Global Scrapper)
- Liefert Name, Adresse, Telefonnummer (sofern öffentlich)
- Durchschnittliche Personen ergebnisse c.a 5-450 Tausend Entrys!

### 📧 E-Mail-Benachrichtigung
- HTML-Mails mit strukturierten Berichten via SMTP versenden

### 📰 Nachrichtenanalyse
- Aggregation aus 10+ RSS-Newsfeeds
- Filtert tagesaktuelle Artikel

### 🚨 Warnsysteme (NINA)
- Holt Wetter-, Polizei- & Katastrophenwarnungen (DE)
- JSON-basierte Speicherung

### ☀️ Wetterdaten
- Aktuelles Wetter weltweit für beliebige Koordinaten
- Speicherung in strukturierter Form

### 📹 Webcam-Suche
- Findet Webcams nach Koordinaten, Radius & Kategorie
- Gitternetz-Logik zur Vollabdeckung

### 🌐 Websuche & Relevanzfilter
- Suche über 11 Engines (Google, Bing, DuckDuckGo etc.)
- Relevanzbewertung, Dublettenerkennung, Stemming-Analyse

---

## 🧠 Systemintegration

- Zentrale Steuerung über `main`
- Lädt alle Module & API-Schlüssel
- Führt zyklisch (alle 5 Minuten) Datensammlungen durch
- Unterstützt einfache Erweiterung per Plug-in

---

## 🔧 Weiterentwicklung

- Projektleitung: **Matti Krebelder**
- Entwickelt & maintained von **[Fsociety00.com](https://fsociety00.com)**
- Community-Integration & Open Source Roadmap in Arbeit
- Erweiterungen für Darknet-Analyse und Blockchain-Monitoring in Planung

---

## 📜 Lizenz & Ethik

Cypher dient ausschließlich der Forschung, Aufklärung und Cybersicherheitsanalyse. Jeder Missbrauch führt zu strafrechtlichen Konsequenzen.

> „Observe, don’t exploit. Analyze, don’t attack.“  
> – Fsociety00 Ethical Guidelines

