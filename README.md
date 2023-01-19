# Projekt Seminar ME-TRPO
## Gruppe
Die Gruppe von aus Simon Lausch, Jan Felix Fuchs, Paul Jansen und Tobias Papen hat sich in zwei Gruppen aufgeteilt:
1. Simon Lausch, Jan Felix Fuchs und Paul Jansen (Deep Q Learning)
2. Tobias Papen (ME-TRPO)

Das Repository von Simon Lausch, Jan Felix Fuchs und Paul Jansen findet man <a href="https://github.com/TollheitsTobi/projektSeminar">hier</a>.

## Aufbau des Repositories:
- Die drei Notebooks sind unterteilt in me_trpo, ergebnisse und optmodel. In me_trpo ist das Environment, der Aufbau von Model Ensemble und darin wurden die Agents trainiert. Bei dem ergbnisse Notebook geht es darum die verschiedenen Agents zu testen und dazu Daten zu sammeln. Das optmodel Notebook hat die learning-rate und batchsize des Neuronalen Netzes optimiert.
- Im models/finished Verzeichnis sind die fertig trainierten Agents gespeichert.
- Das data und models Verzeichnis sind nur da um die gesammelten Daten und Agents zwischen zu speichern falls es abstürzt.
- In dem models/tmp Verzeichnis werden die Agents gespeichert um im richtigen Environment Daten zu sammeln.
- Die Präsentation.pdf Datei ist die finale Präsentation.

## Einrichtung der Arbeitsumgebung:
Im Repository befindet sich die projekt-seminar-me-trpo-env.yml Datei mit der man sich die Arbeitsumgebung einrichten kann.