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

Bevor nun die eigentliche Implementierung des Projekts beschrieben wird, soll zunächst der Aufbau des Projekts, sowie
die Abhängigkeiten und die Verwendung des Projekts beschrieben werden.

### Kopieren des Projekts

Um das Projekt selber in einer beliebigen IDE zu öffnen, muss das Projekt zunächst geklont werden. Dazu muss folgende
Befehl in einen Terminal eingegeben werden:

```shell
git clone https://github.com/DHBW-Artificial-Intelligence-9416513/Hand-on-Reinforced-Learning.git
```

### Aufbau des Projekts

Nach den erfolgreichen Klonen des Projekts sollte sich nun ein Ordner mit dem Namen **Hand-on-Reinforced-Learning** im
aktuellen
Verzeichnis des Terminals befinden. In diesem Ordner befindet sich jetzt das Projekt. Der Aufbau des Projekts ist wie
folgt:

```text
|- Hand-on-Reinforced-Learning
|  |- highway_models
|  |  |- dqn
|  |  |  |- stable_baselines3
|  |  |  |  |- v1
|  |  |  |  |  |- model_500.zip
|  |  |  |  |  |- model_2000.zip
|  |  |  |  |  |- model_5000.zip
|  |  |  |  |  |- model_10000.zip
|  |  |  |  |  |- model_20000.zip
|  |  |  |  |- v2
|  |  |  |  |  |- model_DQN_MlpPolicy_v2_100.zip
|  |  |  |  |  |- model_DQN_MlpPolicy_v2_500.zip
|  |  |  |  |  |- model_DQN_MlpPolicy_v2_1000.zip
|  |  |  |  |  |- model_DQN_MlpPolicy_v2_2000.zip
|  |  |  |  |  |- model_DQN_MlpPolicy_v2_4000.zip
|  |  |  |  |  |- model_DQN_MlpPolicy_v2_8000.zip
|  |  |  |  |  |- model_DQN_MlpPolicy_v2_16000.zip
|  |  |  |  |  |- model_DQN_MlpPolicy_v2_32000.zip
|  |  |  |  |- v3
|  |  |  |  |  |- best_model.zip
|  |  |  |  |  |- .dqn_model_3000_steps.zip
|  |  |  |  |  |- .dqn_model_6000_steps.zip
|  |  |  |  |  |- .dqn_model_9000_steps.zip
|  |  |  |  |  |- .dqn_model_12000_steps.zip
|  |  |  |  |  |- .dqn_model_15000_steps.zip
|  |  |  |  |  |- .dqn_model_18000_steps.zip
|  |  |  |  |  |- .dqn_model_21000_steps.zip
|  |  |  |  |  |- .dqn_model_24000_steps.zip
|  |  |  |  |  |- .dqn_model_27000_steps.zip
|  |  |  |  |  |- .dqn_model_30000_steps.zip
|  |  |  |- torch
|  |  |  |  |- .gitkeep
|  |  |- ppo
|  |  |  |- stable_baselines3
|  |  |  |  |- v1
|  |  |  |  |  |- best_model.zip
|  |  |  |  |  |- .ppo_model_3000_steps.zip
|  |  |  |  |  |- .ppo_model_6000_steps.zip
|  |  |  |  |  |- .ppo_model_9000_steps.zip
|  |  |  |  |  |- .ppo_model_12000_steps.zip
|  |  |  |  |  |- .ppo_model_15000_steps.zip
|  |  |  |  |  |- .ppo_model_18000_steps.zip
|  |  |  |  |  |- .ppo_model_21000_steps.zip
|  |  |  |  |  |- .ppo_model_24000_steps.zip
|  |  |  |  |  |- .ppo_model_27000_steps.zip
|  |  |  |  |  |- .ppo_model_30000_steps.zip
|  |- img
|  |  |- dqn
|  |  |  |- eval_mean_length.png
|  |  |  |- eval_reward.png
|  |  |  |- train_mean_length.png
|  |  |  |- train_reward.png
|  |  |- ppo
|  |  |  |- eval_length.png
|  |  |  |- eval_reward.png
|  |  |  |- train_mean_length.png
|  |  |  |- train_reward.png
|  |- logs
|  |  |- stable_baselines3
|  |  |  |- DQN
|  |  |  |  |- DQN_1
|  |  |  |  |  |- events.out.tfevents.1690498131.DESKTOP-GOIJTI0.3053.0
|  |  |  |  |- DQN_2
|  |  |  |  |  |- events.out.tfevents.1690534342.DESKTOP-GOIJTI0.664.1
|  |  |  |  |- .gitkeep
|  |  |  |  |- evaluations.npz
|  |  |  |  |- monitor.csv
|  |  |  |- ppo
|  |  |  |  |- PPO_1
|  |  |  |  |  |- events.out.tfevents.1690523738.DESKTOP-GOIJTI0.664.0
|  |  |  |  |- PPO_2
|  |  |  |  |  |- events.out.tfevents.1690543213.DESKTOP-GOIJTI0.664.2
|  |  |  |  |- .gitkeep
|  |  |  |  |- evaluations.npz
|  |  |  |  |- monitor.csv
|  |- notebooks
|  |  |- Highway_StableBaseline3.ipynb
|  |  |- Highway_StableBaselines3_v3.0_multi_agent.ipynb
|  |  |- Highway_Stableline3_v2.0.ipynb
|  |  |- Highway_Visualisation.ipynb
|  |- videos
|  |  |- readme
|  |  |  |- .gitkeep
|  |  |- stable_baselines3
|  |  |  |  |- dqn.mp4
|  |  |  |  |- dqn_multi.mp4
|  |  |  |- ppo
|  |  |  |  |- ppo.mp4
|  |  |  |  |- ppo_multi.mp4
|  |- .gitignore
|  |- environment.yml
|  |- LICENSE
|  |- README.md
|  |- requirements.txt

```

### Installation der Abhängigkeiten des Projekts

Bevor man das Projekt ausführen kann, müssen zunächst die Abhängigkeiten des Projekts installiert werden. Dazu gibt es
die folgenden Möglichkeiten: **[pip](https://pip.pypa.io/en/stable/)**, **[conda](https://docs.conda.io/en/latest/)**
und **[venv](https://docs.python.org/3/library/venv.html)**.
Alle drei Möglichkeiten werden im Folgenden beschrieben, setzen jedoch eine installierte Python-Version voraus (Dieses
Projekt wurde mit Python 3.11.* entwickelt). Sollte noch keine passende Python-Version installiert sein, kann diese von
der offiziellen **[Python-Website](https://www.python.org/downloads/)** heruntergeladen werden.

**Beachte:** Es gibt neben den Abhängigkeiten des Projekts noch weitere Abhängigkeiten, welche durch das Operating
System definiert werden. Bitte dazu entsprechend die Fehlermeldungen beachten.

#### Installation mit pip

Um die Abhängigkeiten mit pip zu installieren, muss folgender Befehl in ein Terminal eingegeben werden:

```shell
pip install -r requirements.txt
```

**Beachte:** Durch diese Methode werden die Pakete global installiert. Sollte dies nicht gewünscht sein, sollte eine der
anderen Methoden verwendet werden.

#### Installation mit conda

Bevor man die einzelnen Abhängigkeiten installieren kann, muss zunächst conda installiert werden und aktiviert sein.
Beachten Sie dabei bitte die offizielle Dokumentation von **[conda](https://docs.conda.io/en/latest/)**. Nachdem conda
eingerichtet worden ist, bietet es sich an für dieses Projekt eine eigene Environment zu erstellen, um dort nur die
benötigten Bibliotheken zu installieren. Führen Sie dazu die folgenden Schritte durch:

```shell
conda create --name <Name der Environment> python=3.11
```

Nach der erstellung der Environment, muss diese zunächst durch den nachfolgenden Schritt aktiviert werden.

```shell
conda activate <Name der Environment>
```

**Beachte:** Sollte die Environment nicht mehr benötigt werden, kann diese durch den folgenden Befehl wieder deaktiviert
werden. Zudem kann es erforderlich sein, dass bei jeder neuen Sitzung die Environment erneut aktiviert werden muss.

```shell
conda deactivate
```

Nachdem die Environment aktiviert worden ist, können nun die Abhängigkeiten installiert werden. Dazu muss folgender
Befehl in ein Terminal (mit aktivierter Environment) eingegeben werden:

```shell
conda install --file requirements.txt
```

#### Installation mit venv

Um die Abhängigkeiten mit venv zu installieren, muss zunächst ebenfalls eine neue Environment durch den folgenden Befehl
in einem Terminal erstellt werden:

```shell
python -m venv <Name der Environment>
```

Nachdem die Environment erstellt worden ist, muss diese zunächst durch den nachfolgenden Schritt aktiviert werden.

```shell
<Name der Environment>\Scripts\activate.bat
```

**Beachte:** Sollte die Environment nicht mehr benötigt werden, kann diese durch den folgenden Befehl wieder deaktiviert
werden. Zudem kann es erforderlich sein, dass bei jeder neuen Sitzung die Environment erneut aktiviert werden muss.

```shell
deactivate
```

Nachdem die Environment aktiviert worden ist, können nun die Abhängigkeiten installiert werden. Dazu muss folgender
Befehl in ein Terminal (mit aktivierter Environment) eingegeben werden:

```shell
pip install -r requirements.txt
```

Damit sind nun alle Abhängigkeiten installiert und das Projekt kann ausgeführt werden.

### Ausführen des Projekts

Um das Projekt auszuführen, muss zunächst ein Jupiter Notebook Server gestartet werden. Dazu muss folgender Befehl in
ein Terminal, welches entweder eine aktive Python-Umgebung oder eine aktive conda-Umgebung besitzt, eingegeben werden:

```shell
jupyter notebook
```

Anschließend kann über den Browser auf die Notebooks zugegriffen werden. Dazu muss in der Adresszeile des Browsers
folgender Link eingegeben werden:

```text
http://localhost:8888/tree
```

Nachdem der Link aufgerufen worden ist, sollte sich ein Fenster mit dem Inhalt des Notebooks öffnen. Nun kann das
Notebook ausgeführt werden.

Die folgenden Notebooks beinhalten den Code für die einzelnen Schritte des Projekts:

- **[StableLine3 - DQN](notebooks/Highway_StableBaseline3.ipynb)**
- **[StableLine3 - DQN Version 2 ](notebooks/Highway_Stableline3_v2.0.ipynb)**
- **[StableLine3 - PPO](notebooks/Highway_StableBaselines3_v3.0_multi_agent.ipynb)**

---

## Ergebnisse des Projekts

In diesen Abschnitt werden nun die zentralen Erkenntnisse aus dem Projekt vorgestellt.

Im Rahmen dieses Projekts wurden zwei unterschiedliche Agenten auf die Umgebung trainiert, PPO und DQN. Beide Agenten
stammen aus der Bibliotheke Stable-Baselines3. Die Ergebnisse der beiden Agenten werden im Folgenden vorgestellt.
Bevor einige Aussagen zu den einzelnen Agenten getroffen werden, werden zunächst einige allgemeine Aussagen getroffen.
Es ist festgestellt worden, dass von den beiden Agenten, der PPO am besten abgeschnitten hat, wenn man sich sowohl die
Average Reward Werte pro Evaluation anschaut, als auch an den Punkt, wie lange der Agent sich in der Umgebung halten
kann. Jedoch stellt auch dieser Agent keine zufriedenstellenden Ergebnisse dar. Der Agent ist in der Lage sich in der
für einige Sekunden zu halten jedoch crashed auch dieser immer noch, sodass weiteres Training oder gar ein anderer
Ansatz notwendig sein könnte.

### DQN

In den nachfolgenden Diagrammen werden die Ergebnisse des DQN Agenten dargestellt.
Dabei werden immer zwei identische
DQN-Agenten miteinander verglichen.
Beide wurden auf derselben Vektorisiserten Umgebung trainiert und weißen dieselben Hyperparameter auf.

In den ersten Diagrammen wird der Average Reward pro Evaluation dargestellt. Es ist ersichtlich, dass der Agent immer
einen Reward von mindestens 4 und maximal 13 erreichen kann.
![eval_reward.png](img%2Fdqn%2Feval_reward.png)
Jedoch scheint es so, dass das Modell einen Reward von 13 nicht halten kann, da der Reward immer wieder auf 4 zurück was
ein Zeichen dafür sein könnte, dass der Agent noch nicht verstanden hat, wie man den anderen Fahrzeugen optimal
ausweichen kann.
In den nächsten Diagrammen wird die durchschnittliche Länge der Episode pro Evaluation dargestellt. Es ist ersichtlich,
dass der Agent immer eine Episode Länge von mindestens 6 und maximal 13 erreichen kann.
![eval_mean_length.png](img%2Fdqn%2Feval_mean_length.png)

Das ist ein sehr kurzes Ergebnis, da der Agent immer noch sehr schnell crashed. Es ist jedoch ersichtlich, wenn man sich
eine der Umgebungen mal als Video betrachtet, so ist jedoch erkennbar, dass der Agent sich über das Training hinweg
immer länger in der Umgebung halten kann, jedoch nicht lange genug, um die Episode zu beenden.

### PPO

In den nachfolgenden Diagrammen werden die Ergebnisse des PPO Agenten dargestellt. Grundlegend ist zu sagen, dass der
PPO-Agent besser abschneidet als der DQN-Agent. So liegt bereits beim ersten Training der Average Reward über 14, was
das maximum von den DQN-Agenten entspricht und nahm im Laufe des Trainings immer weiter zu, bis es dann sich bei ca. 27
eingependelt hat.
![train_reward.png](img%2Fppo%2Ftrain_reward.png)

Mit Blick auf den Average Reward pro Evaluation ist zu erkennen, ebenfalls besser abschneidet als das DQN, jedoch ist
besonders auffällig, dass der Agent zwischen 24.000 und 26.000 Schritten einen Einbruch hat, was darauf hindeutet, dass
der Agent in diesem Bereich schlechter geworden ist. Jedoch hat sich der Agent wieder gefangen und konnte sich wieder
verbessern.
![eval_reward.png](img%2Fppo%2Feval_reward.png)

In Hinblick auf die durchschnittliche Länge der Episode pro Evaluation ist zu erkennen, dass der Agent sich im Laufe des
sich anders als der DQN, welcher bei 6 bis 13 lag, sich der PPO-Agent zwischen 20 und 30 Sekunden halten kann. Zudem
nahm die Episodenlänge im laufenden Training zu, was ich als ein Indiez dafür sehe, dass der Agent sich verbessert hat.
Und es sich vermutlich lohnen sollte, das Training noch weiter zu führen.

![train_length.png](img%2Fppo%2Ftrain_length.png)
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