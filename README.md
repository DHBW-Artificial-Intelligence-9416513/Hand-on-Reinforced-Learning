# Hand on Project: Reinforcement Learning - BARKnDrive

Dieses Projekt wurde im Rahmen des Moduls "Aktuelle Data Science-Entwicklungen" im Bachelorstudium "Wirtschafts-
informatik Data Science" an der Dualen Hochschule Baden-Württemberg Mannheim im Jahr 2023 erstellt.

## Autor des Projekts

Dieses Projekt wurde selbständig von **[Tobias Kister - 9416513](https://github.com/tkister)** unter Verwendung der angegebenen Quellen erstellt.

## Projektbeschreibung


## Motivation zur Durchführung des Projekts

## Vorgehensweise

## Verwendete Technologien und Konzepte des Projekts

## Aufbau und Verwendung des Projekts

### Aufbau des Projekts

Dieses Projekt besitzt die folgende Datenstruktur:

```

```

### Verwendung des Projekts

#### Aufsetzen der Voraussetzungen für die Verwendung des Projekts

Um das Projekt zu verwenden, müssen folgende Schritte durchgeführt werden:
1. Clonen Sie das Projekt (Github Repository) auf Ihren lokalen Rechner. Dazu können Sie folgenden Befehl verwenden:
```bash
git clone https://github.com/DHBW-Artificial-Intelligence-9416513/Hand-on-Reinforced-Learning.git
```
2. Navigieren Sie in den Ordner des Projekts und setzen Sie eine virtuelle Umgebung auf. Dazu können Sie eine der folgenden Möglichkeiten verwenden:
   1. #### Conda
        1. Verwenden von Conda Virtual Environments:
        ```bash
        conda create -n <Name der Enviroment> python=3.8
        ```
        2. Nach dem Erstellen der virtuellen Umgebung muss diese noch aktiviert werden. Dazu können Sie folgenden Befehl verwenden:
        ```bash
        conda activate <Name der Enviroment>
        ```
        3. In Anschluss müssen noch die benötigten Pakete installiert werden. Dazu können Sie folgenden Befehl verwenden:
        ```bash
        pip install -r requirements.txt
        ```
      **!!Hinweis!!:** Alternativ können Sie auch die Datei `environment.yml` verwenden, um die virtuelle Umgebung zu erstellen. Dazu können Sie folgenden Befehl verwenden:
        ```bash
        conda env create -f environment.yml
        ```
   2. #### Virtualenv:
        ```bash
        ```bash
        python3 -m venv <Name der Enviroment>
        ```
        Nach dem Erstellen der virtuellen Umgebung muss diese noch aktiviert werden. Dazu können Sie folgenden Befehl verwenden:
        ```bash
        source <Name der Enviroment>/bin/activate
        ```
        In Anschluss müssen noch die benötigten Pakete installiert werden. Dazu können Sie folgenden Befehl verwenden:
        ```bash
        pip install -r requirements.txt
        ```

   3. Nachdem die virtuelle Umgebung erfolgreich erstellt wurde, kann das Projekt verwendet werden.

       Um die einzelnen Jupyter Notebooks zu starten, können Sie folgenden Befehl verwenden:
       ```bash
       jupyter notebook
       ```
       Um die einzelnen Pythonskripte zu starten, können Sie folgenden Befehl verwenden:
       ```bash
       python <Name des Skripts>.py
       ```

Die folgenden Notebooks beinhalten den Code für die einzelnen Schritte des Projekts:
- **Trainieren des Agenten** 
- **Testen des Agenten**

---
## Ergebnisse des Projekts

Zu Beginn des Projektes (0. Generation des Agenten), war er nur in der Lage, das Auto geradeaus fahren zu lassen. Nachdem der Agent trainiert wurde, konnte er das Auto erfolgreich durch die Kurven steuern.
Dies lässt sich in folgendem Video beobachten:

[![Video](https://img.youtube.com/vi/9Q1QX6Z3Zq0/0.jpg)](https://www.youtube.com/watch?v=9Q1QX6Z3Zq0)

Zum Ende des Trainingszyklus und dem somit erreichten Ergebnis, konnte der Agent das Auto erfolgreich durch die Kurven steuern. Dies lässt sich in folgendem Video beobachten:

[![Video](https://img.youtube.com/vi/9Q1QX6Z3Zq0/0.jpg)](https://www.youtube.com/watch?v=9Q1QX6Z3Zq0)

Die letzte Generation erzielte die folgenden Ergebnisse:

---
## Diskussion der Ergebnisse und Ausblick auf mögliche Verbesserungen

---
## Quellen

Für die Erstellung des Projekts wurden folgende Quellen verwendet:

---
## Lizenz
Dieses Projekt ist lizenziert unter der MIT-Lizenz - siehe [LICENSE](LICENSE) für weitere Details.

---
## Kontakt

Sollten Sie Fragen oder Anmerkungen zu diesem Projekt haben, können Sie mich gerne unter folgender E-Mail-Adresse kontaktieren: [Contact@tkister.de](mailto:Contact@tkister.de)