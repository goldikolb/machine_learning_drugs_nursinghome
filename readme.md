# Einfache Lineare Regression für Pflegeheim-Daten

Dieses Repository enthält ein Beispiel für eine einfache lineare Regression, die Beispiel-Daten für eine Träger von mehreren Pflegeeinrichtungen verwendet, um die Beziehung zwischen Personalkosten und der Anzahl der verordneten Psychopharmaka zu modellieren.
Jede Reihe stellt eine Stationseinheit mit z.B. 30 Bewohnern dar und die zweite Spalte die Anzahl der verordneten Psychopharmaka aller Bewohner. Ich stelle einfach einen Zusammenhang (Korrelation), je mehr oder qualifiziertes Personal, umso weniger Psychpharmaka benötigt man. Ob es wirklich so einen Zusammenhang gibt, keine Ahnung, ich glaube so eine Studie will keiner.

## Datensatz

Der Datensatz (`drugs_nursing_home.csv`) enthält die folgenden Spalten:
- `Personalkosten (€)`: Jährliche Personalkosten für jede Station.
- `Verordnete Psychopharmaka`: Anzahl der verordneten Psychopharmaka für jede Station.

## Überblick

Ziel ist es, eine einfache lineare Regressionsanalyse durchzuführen, um zu verstehen, wie die Personalkosten die Anzahl der verordneten Psychopharmaka beeinflussen.

## Schritte

1. **Laden des Datensatzes**
2. **Aufteilen des Datensatzes** in Trainings- und Testdaten
3. **Trainieren des Modells** mit den Trainingsdaten
4. **Visualisieren der Ergebnisse** für sowohl Trainings- als auch Testdaten
5. **Vorhersagen treffen** für neue Daten
6. **Anzeigen der Modellparameter**

## Anforderungen

Um den Code auszuführen, benötigen Sie die folgenden Python-Pakete:
- `pandas`
- `scikit-learn`
- `matplotlib`

Diese Pakete können Sie mit pip installieren:
```bash
pip install pandas scikit-learn matplotlib