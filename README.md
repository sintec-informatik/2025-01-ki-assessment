# Street-lane-detector

English version below.

## Deutsch

### Schritte um Jupyter Notebook auf Windows zu installieren

1. Installiere [Visual Studio Code](https://code.visualstudio.com/Download)
2. Installiere [Python](https://www.python.org/downloads/)
3. Öffne `Visual Studio Code` und installiere die `Python` Erweiterung mit `Ctrl+Shift+X` und Suche nach `Python`
4. Check das `GitHub` Projekt aus
5. Öffne das ausgecheckte `GitHub` Projekt mit `Visual Studio Code`
6. Viel Spaß!


### Aufgabe

Entwickele ein System, welches Fahrspuren auf Straßenfotos erkennt und markiert.

Das mitgelieferte Jupyter Notebook `aufgabe.ipynb` beinhaltet Verarbeitungsschritte der Bildanalyse in `Python`.

#### Umsetzungschritte
1. Lade ein Bild.
2. Definiere den relevanten Bereich der Fahrbahn im Bild. Speichere das Bild mit dem markierten relevanten Bereich.
3. Projiziere das Bild der Fahrbahn in die Draufsicht (Vogelperspektive). Speichere das Bild.
4. Führe Kanten- und Linienerkennung mit dem Canny-Algorithmus durch. Speichere das Bild.
5. Analysiere die erkannten Linien. Welche Linien spiegeln die Fahrbahnmarkierungen wider?
6. Zeichne die erkannten Linien im Bild ein. Speichere das Bild.
7. Projiziere das Bild mit den erkannten Linien zurück. Speichere das Bild.
8. (Zusatzaufgabe: Filtere oder gruppiere die erkannten Linien in zwei Gruppen: linke Fahrbahnmarkierung und rechte Fahrbahnmarkierung.)
9. (Zusatzaufgabe: Verwende die gefilterten Linien und führe deinen Code aus Aufgabe 6 und Aufgabe 7 erneut aus. Was fällt dir auf? Speichere das Bild.)
 
#### Umsetzung
Die _Aufgabe_ kann in dem mitgelieferten Jupyter-Notebook oder einer Programmiersprache deiner Wahl gelöst werden.

## English

### Steps to install Jupyter Notebook for Windows

1. Install [Visual Studio Code](https://code.visualstudio.com/Download)
2. Install [Python](https://www.python.org/downloads/)
3. Open `Visual Studio Code` and install `Python` extension with `Ctrl+Shift+X` and search for `Python`
4. Check out the `GitHub` project
5. Open the checked out `GitHub` project with `Visual Studio Code`
6. Have fun!


### Task

Develop a system that recognises and marks lanes on road photos.

The provided Jupyter Notebook `task.ipynb` contains processing steps of the image analysis in `Python`.

#### Steps for realisation
1. load an image.
2. define the area of interest of the carriageway in the image. Save the image with the marked area of interest.  
3. project the bird's eye view of the carriageway. Save the image.
4. perform edge and line detection with the `Canny` algorithm. Save the image.
5. analyse the detected lines. Which lines reflect the lane markings?
6. draw the recognised lines in the image. Save the image.
7. project back the image with the recognised lines. Save the image
8. (Additional task: Filter or merge the recognised lines into two groups. Left edge line and right edge line)
9. (Additional task: Use the filtered lines and run your code from **Task 6** and **Task 7** again. What do you notice? Save the image).
 
#### Realisation
The _task_ can be solved using the Jupyter notebook or with the programming language of your choice.