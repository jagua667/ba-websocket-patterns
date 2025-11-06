# Vergleich von Design-Patterns für WebSocket-basierte Echtzeitkommunikation

Dieses Repository enthält Beispielimplementierungen von drei gängigen **Design-Patterns**  
im Kontext einer **Fitnesskurs-Verwaltungs-App**, in der Kund:innen in **Echtzeit benachrichtigt** werden –  
z. B. wenn Kurse **gebucht, storniert oder geändert** werden.

Das Projekt ist Teil der **Bachelorarbeit von Claudia Sadotra**  
(Wilhelm Büchner Hochschule, Studiengang Digitale Medien B.Sc., 2025).

---

## Ziel der Arbeit
Ziel ist es, die **Praxistauglichkeit** der Patterns **Observer**, **Mediator** und **Publish/Subscribe (Pub/Sub)**  
für WebSocket-basierte Benachrichtigungssysteme zu vergleichen – insbesondere im Hinblick auf:
- Verständlichkeit und Wartbarkeit des Codes  
- Erweiterbarkeit bei neuen Ereignissen  
- Performance (konzeptionell, nicht gemessen)

Das Feedback erfahrener Softwareentwickler:innen dient der qualitativen Bewertung dieser Ansätze.

---

## Struktur
Jedes Pattern besteht aus zwei Dateien, die jeweils eine vereinfachte Implementierung der Nachrichtenlogik darstellen:

src/services/notifications/
└── observerNotifier.js
src/websocket/
└── ObserverStrategy.js

src/services/notifications/
└── mediatorNotifier.js
src/websocket/
└── MediatorStrategy.js


src/services/notifications/
└── pubsubNotifier.js
src/websocket/
└── PubSubStrategy.js


Alle Implementierungen basieren auf denselben funktionalen Anforderungen:
> Verwaltung von Fitnesskursen mit Echtzeit-Benachrichtigungen,  
> z. B. wenn ein Kurs gebucht, storniert oder aktualisiert wird.

---

## Leitfaden (Review-Vorlage)

Bitte lade zuerst den Excel-Leitfaden herunter, fülle ihn aus und gib ihn anschließend über das Formular zurück.

 **Download (Leitfaden):**  
[https://docs.google.com/spreadsheets/d/1P_gXnnJW-661QC7CRkGU1yrIU274igu3/edit?usp=sharing](https://docs.google.com/spreadsheets/d/1P_gXnnJW-661QC7CRkGU1yrIU274igu3/edit?usp=sharing)

 **Rückgabe (Upload-Formular):**  
[https://forms.gle/PruNv3gsbotCgfWJ7](https://forms.gle/PruNv3gsbotCgfWJ7)

🕒 **Frist:** 12. November 2025, 23:59 Uhr

---

**Hinweis:**  
Das Google-Formular dient **nur zum Hochladen** deiner ausgefüllten Datei.  
Den Leitfaden selbst bitte vorher über den Download-Link abrufen.


## Teilnahme-Infos
- **Aufwand:** ca. 20 Minuten (alle 3 Patterns)  
- **Abgabefrist:** 12. November 2025 (23:59 Uhr)  
- **Rückgabewege:**  
  - Upload-Formular: [https://forms.gle/PruNv3gsbotCgfWJ7](https://forms.gle/PruNv3gsbotCgfWJ7)  
  - Alternativ per E-Mail: [claudia.sadotra@web.de]

---

## Datenschutz
Die Teilnahme erfolgt **freiwillig, anonym und ausschließlich zu akademischen Zwecken**.  
Es werden keine personenbezogenen oder sensiblen Daten erhoben.  

**Verantwortliche gemäß DSGVO:**  
Claudia Sadotra (WBH, Studierende)  
📧 [claudia.sadotra@web.de]

---

## Lizenz
MIT License  
© 2025 Claudia Sadotra  

Diese Codebeispiele dürfen frei verwendet, modifiziert und geteilt werden,  
sofern die Quelle genannt wird.

---

## 💬 Kontakt
📧 [claudia.sadotra@web.de]
🎓 Wilhelm Büchner Hochschule – Digitale Medien (B.Sc.)  
📅 Bachelorarbeit: *Vergleich von Design-Patterns (Observer, Mediator, Pub/Sub)  
für Echtzeit-Benachrichtigungen in einer Fitnesskurs-Verwaltungs-App*

