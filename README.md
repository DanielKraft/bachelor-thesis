# Analyse von einem Java-System mit Hilfe von jQAssistant sowie Entwicklung eines Algorithmus zur Generierung eines Abänderungsvorschlages auf Basis von Domian-Driven Design

## Kurzbeschreibung
Zurzeit  wird  gerne  das  Domain-Driven  Design  verwendet.  Aber  nicht  in  allen  existierenden  Systemen  werden  alle  Standards  von  Domain-Driven  Design  eingehalten.  Die Standards helfen dabei modularen Quellcode zu entwickeln, wodurch das System leichter verändert werden kann. Außerdem sorgen die Standards dafür, dass der Quellcode lesbarer wird und weniger Duplikate enthält. Aufgrund dieser Vorteile kann es nützlich sein die Architektur eines vorhandenen Systems auf Basis von Domain-Driven Design abzuändern.  Dabei  ergibt  sich  die  Problematik,  dass  man  anhand  eines  Algorithmus nicht eingehaltene Standards in der Architektur finden und beheben muss.

![Workflow von dieser Arbeit](/gfx/Workflow.png?raw=true "Workflow")

## Zielsetzung
Mit der Arbeit möchte ich ein Konzept entwickeln, mithilfe derer überprüft werden kann, ob ein bestehendes Java-System die Prinzipien von Domain-Driven Design einhält. Das bestehende System wird anhand einer Kennzahl, zum Beispiel die prozentuale Einhaltung der Prinzipien, bewertet. Außerdem soll ein Algorithmus entwickelt werden, welcher versucht die nicht eingehaltenen Prinzipien, wenn es möglich ist, zu verbessern. Dabei möchte ich besonders meinen Schwerpunkt auf die Verbesserung der Architektur legen. Der Algorithmus gilt als erfolgreich, wenn die Bewertung des verbesserten Systems besser geworden ist oder sich nicht verschlechtert hat.

## Ergebnis
Der Quellcode ist in folgenden Repository verfügbar: [illumi-code-ddd](https://github.com/DanielKraft/illumi-code-ddd)

## Autor
[**Kraft, Daniel**](https://github.com/DanielKraft)

## Danksagung
[**adesso AG**](https://www.adesso.de/de/)
