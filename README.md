# Sentiview

## 📖 Projektbeschreibung
Wir sind eine Studentengruppe aus der **Technischen Hochschule Aschaffenburg**, Studiengang **Software Design**.  
Im Rahmen unseres Bachelorstudiums haben wir dieses Projekt entwickelt, um unsere Kenntnisse in **Data Science** und **Natural Language Processing (NLP)** praktisch anzuwenden.  

Das Ziel des Projekts ist die Entwicklung eines **Sentiment-Analyse-Systems** für deutsche Texte.  
Dabei soll ein Modell erkennen, ob eine Rezension oder ein Kommentar **positiv, negativ oder neutral** ist.  

---

### 👩‍💻 Projektteam (Scrum Team)
- Ngoc Anh Thu Pham: Product Owner, Developer
- Yeoyoung Yi: Scrum Master, Developer

---

### 🎯 Projektziele
- Sammlung und Aufbereitung deutscher Textdaten (Rezensionen, Kommentare).  
- Vorverarbeitung: Tokenisierung, Entfernen von Stoppwörtern, Normalisierung.  
- Training verschiedener Modelle (TF-IDF + Logistic Regression, SVM, Transformer-Modelle).  
- Vergleich der Modelle mit Metriken wie Accuracy und F1-Score.  
- Bereitstellung einer benutzerfreundlichen Web-App (Streamlit), in der Texte eingegeben werden können und das System die Stimmung vorhersagt.  

---

### 🗂️ Projektstruktur
Sentiview/
│
├── data/
│ ├── raw/ # Originaldaten
│ └── processed/ # Bereinigte Daten
│
├── notebooks/
│ ├── 01_data_preprocessing.ipynb
│ └── 02_model_training.ipynb
│
├── models/ # Trainierte Modelle
├── app/ # Streamlit-App-Code
│
├── README.md # Projektbeschreibung
├── requirements.txt # Python-Abhängigkeiten
└── .gitignore

---

## ⚙️ Installation
1. Repository klonen:

2. Benötigte Bibliotheken installieren:

3. App starten:

---

## 📌 Git-Workflow (für unsere Team)

- Branches: Jeder arbeitet in einem eigenen Branch (main/<New Branch>).

- Commits: Klare Commit-Messages auf Englisch oder Deutsch.

- Pull Requests: Vor jedem Merge in main wird ein PR erstellt und reviewed.

- Issues: Zur Aufgabenverteilung und Nachverfolgung.