Bash fenster muss als Programm extra von Internet geladen und installiert werden
Der ssh_Schlüssel steht bei d./Users/coellen/source/rpos/.ssh  Datei   id_rsa.pub, mit note pad aufrufen,
	Inhalt kopieren, und bei https:/github/Settings/keys im Feld ssh pasten, kann sein, das man einen Eingangscode
	via email gesendet bekommt

URL von repository https://github.com/coellen/c_Taschenrechner   (Groß- Kleinschreibung egal)

Ablauf:
Rechner.cs ändern
abspeichern

git status  (Groß- und Kleinschreibung beachten)
git add -m "Erklärung anhängen"
	!!!!!	Erklärung wichtig, da sonst ein bash_fenster erscheint, welches man nur mit ESC:wq verlassen kann

weitere auffallende Commandos

git add -A (oder --all), wenn mehrere Dateien markiert werden sollen
git merge --abort	,wenn beim mergen etwas schief gelaufen ist