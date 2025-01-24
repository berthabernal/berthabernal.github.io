'''mermaid
flowchart TD
Start[[start]] --> End[[End]]
guessing ["'This is the **_guessing_** game'"]
newLines["'54
89
34
27
91 
60'"]
markdown --> newLines
rules ["'Pick one of the **6** numbers to guess from, the closer you get to the write number you'll see a _happy_ face appear, the farther you'll see a _sad_ face appear. Once you guessed the write number you'll see a yellow star'"]
faces["'54 ---> happy face
89 ---> happy face
34 ---> sad face
27 ---> sad face
91 ---> sad face
60 ---> yellow star'"]

