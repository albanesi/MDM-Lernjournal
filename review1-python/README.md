# Review 1 Python

## Beurteiltes Projekt

|       | Bitte ausfüllen |
|-------|-----------------|
| Review von (ZHAW-Kürzel) |   totholi         |
| Review durch (ZHAW-Kürzel) |       selimab     |
| Datum Review, von/bis |      |

## Review

| Thema                                                                      | Skala | Mängel | Verbesserungsmöglichkeiten |
|-----------------------------------------------------------------------------|--------|--------|------------------------------|
| Datenquelle klar definiert (Projekt 2: zusätzlich Abgrenzung zu Projekt 1) | 3      | Eine klare Datenquelle ist vorhanden | Keine                            |
| Scraping vorhanden                                                         | 0      | Scraping ist nicht implementiert. Stattdessen wird aufgrund von Zeitgründen auf eine API zurückgegriffen. | Evtl. in einem Folgeprojekt ergänzen                                  |
| Scraping automatisiert                                                     | 0      | Aus Zeitgründen wurde auf automatisiertes Scraping verzichtet und eine API verwendet. | Keine                            |
| Datensatz vorhanden                                                        | 3      | Der Datensatz ist umfangreich und informationsreich. | Keine                            |
| Erstellung Datensatz automatisiert, Verwendung Datenbank                   | 2      | Die Speicherung erfolgt in einer lokalen Datenbank. Mangel: Die Datenbank ist bislang nicht in der Cloud deployt. | Verbindung zu einer Cloud-basierten MongoDB (z. B. MongoDB Atlas) einrichten und verwenden. |
| Datensatz-Grösse ausreichend, Aufteilung Train/Test, Kennzahlen vorhanden  | 2      | Der Datensatz ist ausreichend gross. Eine Aufteilung in Trainings- und Testdaten sowie Metriken fehlen aktuell, da das Projekt sich noch in einem frühen Stadium befindet. | Aufteilung in Train/Test nach z. B. 80/20-Schema, Definition geeigneter Metriken zur Evaluation. |
| Modell vorhanden                                                           | 0      | Ein Modell ist bislang nicht vorhanden. Der Student plant jedoch, dies in einem späteren Schritt zu ergänzen. | Relevante Modelltypen identifizieren (z. B. Klassifikation, Regressionsanalyse), Training durchführen und evaluieren. |
| Modell-Versionierung vorhanden (ModelOps)                                  | 0      | Aufgrund des fehlenden Modells kann auch keine Versionierung umgesetzt werden. | Nach dem Training des Modells: Modellversionierung z. B. mit DVC oder MLflow implementieren. |
| App: auf lokalem Rechner gestartet und funktional                          | 1      | Ein erster Prototyp wurde präsentiert. Dieser enthält jedoch nicht alle geplanten Funktionen. | Modell integrieren und volle Funktionalität der App herstellen. |
| App: mehrere unterschiedliche Testcases durch Reviewer ausführbar          | 1      | Aktuell ist nur die Anzeige von Aktienhaltern und deren Preisentwicklung implementiert. Weitere Funktionalitäten fehlen. | Alle im Konzept vorgesehenen Funktionen umsetzen und Testfälle dokumentieren. |
| Deployment: Falls bereits vorhanden, funktional und automatisiert          | 0      | Es liegt bislang kein Deployment vor. | Anwendung deployen, z. B. via Azure Web App, Heroku oder Docker-Container auf Cloud-Plattform. |
| Code: Git-Repository vorhanden, Arbeiten mit Branches / Commits            | 3      | Git-Repository ist vorhanden, strukturiert und nachvollziehbar geführt. | Keine                            |
| Code: Dependency Management, Dockerfile, Build funktional                  | 2      | Dependency Management ist vorhanden. Ein Dockerfile ist begonnen, aber noch nicht vollständig. Lokaler Build funktioniert. | Dockerfile fertigstellen, Build automatisieren, evtl. CI/CD-Anbindung (z. B. mit GitHub Actions). |
|

\* wenn fehlend: mögliche Schwierigkeiten und Lösungen besprechen

## Skala

| Skala |                 |
|-------|-----------------|
| 0     | fehlt           |
| 1     | mit Lücken      |
| 2     | alles vorhanden |
| 3     | übertroffen     |

## Hinweise

Der Projekt-Review fliesst nicht in die Beurteilung der Leistungsnachweise ein, soll aber dem Studierenden dazu dienen, bis zur Abgabe noch Verbesserungsmöglichkeiten zu erkennen. Der Review *des fremden Projektes* muss als Teil des *eigenen* Lernjournals abgegeben werden.