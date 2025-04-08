# 🧠 Parkinson-Datensatzanalyse – Sprachdatenanalyse & Visualisierung zur Vorhersage klinischer Scores

In diesem Data-Science-Projekt wurde ein Datensatz mit **5'875 Stimmmessungen von 42 Parkinson-Patienten** im Frühstadium analysiert.  
Ziel war es, Sprachparameter wie **Jitter**, **Shimmer**, **HNR**, **NHR** etc. im Zusammenhang mit der **UPDRS-Skala** (Unified Parkinson’s Disease Rating Scale) zu untersuchen und visuell darzustellen.

Ich war verantwortlich für das **Preprocessing, die Analyse und die Visualisierung** der Daten und konnte dabei wertvolle Erfahrungen im Umgang mit realen, medizinischen Datensätzen sammeln.

**🔧 Tech Stack & Methoden:**  
- Python · Pandas · NumPy · Matplotlib · Seaborn  
- CSV-Parsing · Plausibilitätsprüfungen · Feature Engineering  
- Visualisierung (Violin Plots, Boxplots, Heatmaps, Histogramme, Scatterplots)

**📌 Highlights:**  
- Überprüfung & Bereinigung der Daten (NaNs, Duplikate, inkonsistente Werte)  
- Umwandlung und Kategorisierung von Merkmalen (z. B. Geschlecht, Probanden-ID)  
- Feature Engineering inkl. Interaktionsvariablen wie `motor_UPDRS * Jitter(%)`  
- Erstellung statistischer Visualisierungen zur Analyse geschlechtsspezifischer Unterschiede  
- Berechnung und Darstellung von Korrelationen zwischen klinischen Scores und Sprachmerkmalen

**📊 Ziel:**  
Die Ergebnisse liefern erste Hinweise darauf, dass Sprachveränderungen zur Vorhersage des **Parkinson-Verlaufs** genutzt werden können – z. B. über nicht-lineare Regressionsmodelle oder Klassifikatoren.