## Bachelorarbeit — Klassifizierung von Hirntumoren mit Deep Learning

### Projektbeschreibung
Dieses Projekt entstand im Rahmen der Bachelorarbeit an der Universität Augsburg.  
Ziel war die Entwicklung, Implementierung und Evaluierung von Deep-Learning-Modellen zur Klassifizierung von Hirntumoren anhand von MRT-Bildern.  

Es wurden folgende Schwerpunkte bearbeitet:

- Datenaufbereitung und Visualisierung
- Modellarchitekturen, einschließlich eines selbst entwickelten CNN und eines vortrainierten ResNet50
- Training, Validierung und Vergleich der Modelle
- Sicherstellung der Reproduzierbarkeit durch Dokumentation von Software-Versionen und Umgebungen

---

### Projektstruktur
```
Bachelorarbeit — Klassifizierung von Hirntumoren mit Deep Learning/  
├── Bachelorarbeit/  
│   ├── BA (main).tex  
│   ├── BA (main).pdf  
│   ├── Literatur.bib  
│   ├── autorjahrdidiDE.bst  
│   ├── Kapitel/  
│   └── Abbildungen/  
├── Datenbeispiele/  
│   ├── Glioma.jpg  
│   ├── Meningioma.jpg  
│   ├── NoTumor.jpg  
│   └── Pituitary.jpg  
├── Modell/  
│   └── BA_Modell.ipynb  
├── README.md  
├── LICENSE  
├── .gitignore  
├── environment.yml  
└── requirements.txt  
```

---

### Voraussetzungen
- Python 3.9.13 oder höher
- GPU empfohlen
- Conda

---

### Installation
1. Repository klonen:
   ```bash
   git clone https://github.com/hloulou/Bachelorarbeit---Klassifizierung-von-Hirntumoren-mit-Algorithmen-des-Deep-Learning.git
   cd Bachelorarbeit---Klassifizierung-von-Hirntumoren-mit-Algorithmen-des-Deep-Learning
   ```
2. Virtuelle Conda-Umgebung erstellen:
   ```bash
    conda env create -f environment.yml
    conda activate BA_HT_Env
   ```
3. Abhängigkeiten installieren
   ```bash
    pip install -r requirements.txt
   ```

---

### Nutzung
- Das Jupyter Notebook BA_Modell.ipynb dokumentiert die vollständigen Schritte zur Datenaufbereitung, Modellbildung, Training und Evaluation von CNNs  
- Die Daten werden über Kaggle heruntergeladen (siehe Notebook). Die Datenbeispiele enthalten kleine Ausschnitte der vier Klassen zur Demonstration.  
- Ergebnisse der Trainingsläufe und Modellarchitekturen sind im Notebook dokumentiert.
- Die verwendeten Versionen von Python und Bibliotheken sind in environment.yml dokumentiert, um die Reproduzierbarkeit sicherzustellen.

---

### Autorin:
Hanan Loulou  

---

### Lizenz
MIT. Siehe LICENSE-Datei.