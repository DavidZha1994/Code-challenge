# Vorhersage von Versicherungsschäden

Dieses Projekt zielt darauf ab, Versicherungsschäden vorherzusagen, indem verschiedene maschinelle Lernmodelle auf einen Datensatz angewendet werden. Die Modelle umfassen Random Forest, Gradient Boosting und XGBoost, die nach fortgeschrittenem Feature-Engineering und Hyperparameter-Optimierung trainiert wurden.

## Projektübersicht

In diesem Projekt verwenden wir einen Datensatz, der verschiedene Merkmale enthält, die das Schadensrisiko von Versicherungskunden beeinflussen können. Ziel ist es, die jährlichen Verluste (Annual Loss) pro Kunde basierend auf diesen Merkmalen vorherzusagen.

## Installationsanleitung

1. Klone das Repository:
   ```bash
   git clone https://github.com/DavidZha1994/Code-challenge.git
   cd Code-challenge

2. Erstelle eine virtuelle Umgebung und installiere die Abhängigkeiten:
    ```bash
    conda env create -f environment.yaml

## Projektstruktur

	•	data/: Enthält die Datensätze (muss manuell hinzugefügt werden).
	•	notebook/: Jupyter Notebook für Datenexploration und Modelltraining.
	•	models/: Gespeicherte Modelle, die nach dem Training exportiert werden.
	•	README.md: Diese Datei.
	•	environment.yaml: Liste der Python-Pakete, die für dieses Projekt erforderlich sind.


## Modelle und Methoden

	•	Feature-Engineering: Verwendung von PolynomialFeatures für die Generierung von Interaktionsmerkmalen sowie Skalierung der Merkmale mittels StandardScaler.
	•	Modelltraining: RandomForest, GradientBoosting und XGBoost wurden mit GridSearchCV für eine optimale Leistung trainiert.
	•	Feature-Importance-Analyse: Analyse der wichtigsten Merkmale für die Vorhersage, sowohl für Original- als auch für Kombinationsmerkmale.

## Ergebnisse

    Die Ergebnisse werden in Form von RMSE (Root Mean Squared Error) für jedes Modell aufgeteilt in Cross-Validation und Test-Datensatz präsentiert. Zusätzlich wird die Wichtigkeit der Merkmale visualisiert, um die Einflussfaktoren besser zu verstehen.


## Kontakt

Für Fragen oder Anmerkungen wenden Sie sich bitte an:

	•	Name: Yu Zha
	•	E-Mail: sa-u@live.com