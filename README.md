# Hand on Project: Reinforcement Learning: Highway-Env

Dieses Projekt wurde im Rahmen des Moduls "Aktuelle Data Science-Entwicklungen" im Bachelorstudium "Wirtschafts-
informatik Data Science" an der Dualen Hochschule Baden-Württemberg Mannheim im Jahr 2023 erstellt.

## Autor des Projekts

Dieses Projekt wurde selbständig von **[Tobias Kister - 9416513](https://github.com/tkister)** unter Verwendung der
angegebenen Quellen erstellt.

## Projektbeschreibung

In diesem Projekt wird die Highway-Env Umgebung genutzt, um die Entwicklung von Reinforcement Learning (RL) Strategien
für autonomes Fahren zu untersuchen. Die Kernidee des Projekts besteht darin, ein Auto in verschiedenen Szenarien
innerhalb der Highway-Env Umgebung zu platzieren und es zu trainieren, sich sicher zu bewegen. Highway-Env ist eine
Open-Source-Bibliothek, die speziell für das Testen von RL-Algorithmen im Kontext des autonomen Fahrens entwickelt
wurde. Die Bibliothek bietet eine realitätsnahe Simulationsumgebung, die es ermöglicht, RL-Algorithmen unter
realistischen Bedingungen zu testen und zu optimieren.

## Motivation zur Durchführung des Projekts

Ich möchte Ihnen kurz meine persönliche Motivation für dieses Reinforcement Learning Projekt zum Thema autonomes Fahren
auf der Autobahn mitteilen.

Seit meiner Kindheit bin ich fasziniert von der Technologie und dem unglaublichen Potenzial, das sie bietet. Autonomes
Fahren hat mich besonders angezogen, da es die Möglichkeit bietet, die Art und Weise, wie wir reisen, radikal zu
verändern. Ich bin begeistert von der Vorstellung, dass Autos eines Tages sicher und effizient ohne menschliches
Eingreifen fahren können.

Die Wahl des Reinforcement Learning (RL) rührt daher, dass ich glaube, dass RL eine Schlüsselrolle bei der Bewältigung
der Herausforderungen des autonomen Fahrens spielen kann, indem es Fahrzeugen ermöglicht, intelligente Entscheidungen in
komplexen Umgebungen zu treffen.

Ich habe mich für die Highway-Env Bibliothek entschieden, weil sie eine realitätsnahe Simulationsumgebung bietet, die
speziell für das autonome Fahren entwickelt wurde. Dies ermöglicht es mir, RL-Algorithmen unter realistischen
Bedingungen zu testen und zu optimieren.

Meine Motivation liegt in der Hoffnung, dass ich durch diese Projekt ein besseres Verständis für RL und seine Anwendung
im Bereich des autonomen Fahrens erhalte. Und dieses in Zukunft in der Praxis anwenden kann.

## Vorgehensweise

Zu Beginn meines Projekts setzte ich mir das Ziel, ein autonomes Fahrzeug zu entwickeln, das halbwegs sicher fahren und
anderen Fahrzeugen ausweichen kann. Ich wusste, dass ich zuerst nach geeigneten Tools und Technologien suchen musste,
die mir bei der Erreichung dieses Ziels helfen könnten. Ich stieß auf verschiedene Optionen wie Highway-Env, BarkML und
Bark-Simulator und beschäftigte mich eingehend mit jedem davon. Nach einiger Überlegung entschied ich mich für
Highway-Env, hauptsächlich weil ich auf Hardware-Probleme stieß, als ich versuchte, BarkML und Bark-Simulator zu
verwenden.

Als nächstes machte ich mich damit vertraut, was Highway-Env zu bieten hat. Ich experimentierte mit seinen verschiedenen
Funktionen und Möglichkeiten und versuchte, die zugrunde liegenden Konzepte zu verstehen.

Mit einem guten Verständnis von Highway-Env machte ich mich daran, meinen ersten Reinforcement Learning (RL) Agenten zu
implementieren. Dabei stützte ich mich stark auf die Dokumentation von Highway-Env, die mir wertvolle Einblicke und
Anleitungen für die Implementierung von RL-Agenten gab.

Nachdem der RL-Agent implementiert war, ging ich zur Trainingsphase über. Ich trainierte den Agenten auf verschiedenen
Ebenen und konzentrierte mich dabei darauf, seine Fähigkeiten zur sicheren Navigation in der simulierten Umgebung zu
verbessern.

Sobald das Training abgeschlossen war, evaluierte ich die Ergebnisse sorgfältig. Ich legte besonderen Wert auf die
Veranschaulichung des Fortschritts des Agenten im Laufe der verschiedenen Trainingsstufen. Dies half mir, ein klares
Bild von den Verbesserungen und möglichen Schwächen des Agenten zu erhalten.

Zum Abschluss dokumentierte ich die Ergebnisse und das Vorgehen, das ich im Projekt verfolgt hatte. Dies diente mir
nicht nur als Referenz für zukünftige Projekte, sondern half mir auch dabei, die Erkenntnisse und Erfolge des Projekts
mit anderen zu teilen.

Rückblickend bin ich zufrieden mit der systematischen Herangehensweise, die ich verfolgt habe, von der anfänglichen
Zielsetzung über die Auswahl der Tools, die Implementierung und das Training des RL-Agenten bis hin zur Evaluierung und
Dokumentation der Ergebnisse. Ich habe wertvolle Einblicke gewonnen und bin gespannt, wie sich diese Technologie in der
Zukunft entwickeln wird.

---

## Verwendete Technologien und Konzepte des Projekts

In diesem Projekt zum autonomen Fahren wurden mehrere Technologien und Konzepte verwendet, um das Training und die
Evaluation von Reinforcement Learning Agenten zu ermöglichen. Im Folgenden wird ein Überblick über die verwendeten
Technologien und Konzepte gegeben:

### Reinforcement Learning (RL)

Reinforcement Learning ist ein maschinelles Lernparadigma, bei dem ein Agent lernt, Aktionen in einer Umgebung
auszuführen, um eine bestimmte Zielfunktion zu maximieren. In diesem Projekt wird RL verwendet, um einen Agenten zu
trainieren, der in der Lage ist, ein Auto sicher und effizient auf einer virtuellen Autobahn zu steuern.

### Highway-Env

Highway-Env ist eine Open-Source-Simulationsumgebung, die speziell für das Testen von RL-Algorithmen im Kontext des
autonomen Fahrens entwickelt wurde. Es bietet eine realistische Darstellung einer Autobahn mit mehreren Fahrspuren,
unterschiedlichen Verkehrsdichten und Fahrphysik. Im Projekt wurde insbesondere die Highway-Umgebung innerhalb von
Highway-Env verwendet.

### DQN-Agents (Deep Q-Network)

DQN steht für Deep Q-Network, eine Art von RL-Agent, der eine Kombination aus Q-Learning und tiefen neuronalen Netzen
verwendet. DQN-Agenten können komplexe Muster und Zusammenhänge in der Umgebung erkennen und sind daher besonders
geeignet für Aufgaben wie autonomes Fahren.

### Stable Baselines3

Stable Baselines3 ist eine Bibliothek, die eine Sammlung von hochwertigen Implementierungen von RL-Algorithmen enthält.
Es wurde entwickelt, um das Training und die Evaluation von RL-Agenten zu vereinfachen. In diesem Projekt wurde Stable
Baselines3 verwendet, um den DQN-Agenten zu implementieren und zu trainieren.

### Gym (jetzt: Gymnasium)

Gym ist eine Open-Source-Bibliothek, die von OpenAI entwickelt wurde und eine Sammlung von Testumgebungen für RL
bereitstellt. Highway-Env ist als Gym-Umgebung implementiert, was die Integration mit RL-Algorithmen wie DQN und
Bibliotheken wie Stable Baselines3 erleichtert.

### Torch

Torch ist eine Open-Source-Deep-Learning-Bibliothek, die in Python geschrieben ist und auf der Lua-Programmiersprache
basiert. Es wird häufig in der Entwicklung von neuronalen Netzwerken verwendet. In diesem Projekt wurde Torch als
Backend für das Training von DQN-Agenten verwendet.

### TensorFlow

TensorFlow ist eine ebenfalls weit verbreitete Open-Source-Deep-Learning-Bibliothek, entwickelt von Google. Es
ermöglicht das einfache Erstellen und Trainieren von neuronalen Netzwerken. Während Torch als primäres Backend verwendet
wurde, ermöglichte TensorFlow zusätzliche Experimente und Vergleiche.

Zusammen bilden diese Technologien und Konzepte das Fundament des Projekts und ermöglichen ein tiefgreifendes
Verständnis und Forschung im Bereich des autonomen Fahrens durch die Anwendung von Reinforcement Learning.

---

## Aufbau und Verwendung des Projekts

### Aufbau des Projekts

Dieses Projekt besitzt die folgende Datenstruktur:

```
|- highway_dqn
|  |- dqn
|  |  |- stablebaseline3
|  |  |  |- model_500.zip
|  |  |  |- model_2000.zip
|  |  |  |- model_5000.zip
|  |  |  |- model_10000.zip
|  |  |  |- model_20000.zip
|  |  |- torch
|  |  |- .gitkeep
|- notebooks
|  |- Highway_StableBaseline3.ipynb
|  |- Highway_Torch.ipynb
|- .gitignore
|- environment.yml
|- LICENSE
|- README.md
|- requirements.txt
```

### Verwendung des Projekts

#### Aufsetzen der Voraussetzungen für die Verwendung des Projekts

Um das Projekt zu verwenden, müssen folgende Schritte durchgeführt werden:

1. Clonen Sie das Projekt (Github Repository) auf Ihren lokalen Rechner. Dazu können Sie folgenden Befehl verwenden:

```bash
git clone https://github.com/DHBW-Artificial-Intelligence-9416513/Hand-on-Reinforced-Learning.git
```

2. Navigieren Sie in den Ordner des Projekts und setzen Sie eine virtuelle Umgebung auf. Dazu können Sie eine der
   folgenden Möglichkeiten verwenden:
    1. #### Conda
        1. Verwenden von Conda Virtual Environments:
         ```bash
         conda create -n <Name der Enviroment> python=3.8
         ```
        2. Nach dem Erstellen der virtuellen Umgebung muss diese noch aktiviert werden. Dazu können Sie folgenden Befehl
           verwenden:
         ```bash
         conda activate <Name der Enviroment>
         ```
        3. In Anschluss müssen noch die benötigten Pakete installiert werden. Dazu können Sie folgenden Befehl
           verwenden:
         ```bash
         pip install -r requirements.txt
         ```
       **!!Hinweis!!:** Alternativ können Sie auch die Datei `environment.yml` verwenden, um die virtuelle Umgebung zu
       erstellen. Dazu können Sie folgenden Befehl verwenden:
         ```bash
         conda env create -f environment.yml
         ```
    2. #### Virtualenv:
         ```bash
         python3 -m venv <Name der Enviroment>
         ```
       Nach dem Erstellen der virtuellen Umgebung muss diese noch aktiviert werden. Dazu können Sie folgenden Befehl
       verwenden:
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

- **[StableLine3 - DQN](notebooks/Highway_StableBaseline3.ipynb)**

---

## Ergebnisse des Projekts

Zu Beginn des Projektes (0. Generation des Agenten), war er nur in der Lage, das Auto geradeaus fahren zu lassen.
Nachdem der Agent trainiert wurde, konnte er das Auto erfolgreich durch die Kurven steuern.
Dies lässt sich in folgendem Video beobachten:

[![Video](https://img.youtube.com/vi/9Q1QX6Z3Zq0/0.jpg)](https://www.youtube.com/watch?v=9Q1QX6Z3Zq0)

Zum Ende des Trainingszyklus und dem somit erreichten Ergebnis, konnte der Agent das Auto erfolgreich durch die Kurven
steuern. Dies lässt sich in folgendem Video beobachten:

[![Video](https://img.youtube.com/vi/9Q1QX6Z3Zq0/0.jpg)](https://www.youtube.com/watch?v=9Q1QX6Z3Zq0)

Die letzte Generation erzielte die folgenden Ergebnisse:

---

## Diskussion der Ergebnisse und Ausblick auf mögliche Verbesserungen

---

## Quellen

Für die Erstellung des Projekts wurden folgende Quellen verwendet:

- [Dokumentation von Highway-Env](https://highway-env.farama.org/) - 05.07.2023 (15:25)
- [Dokumentation von Stable-Baselines3](https://stable-baselines3.readthedocs.io/en/master/) - 05.07.2023 (15:25)
- [Highway-Env Github Repository](https://github.com/Farama-Foundation/HighwayEnv)
- [Tutorial: Highway-Env Highway Stablebaseline3 - eleurent](https://github.com/Farama-Foundation/HighwayEnv/blob/master/scripts/sb3_highway_dqn.ipynb)

---

## Lizenz

Dieses Projekt ist lizenziert unter der MIT-Lizenz - siehe [LICENSE](LICENSE) für weitere Details.

---

## Kontakt

Sollten Sie Fragen oder Anmerkungen zu diesem Projekt haben, können Sie mich gerne unter folgender E-Mail-Adresse
kontaktieren: [Contact@tkister.de](mailto:Contact@tkister.de)