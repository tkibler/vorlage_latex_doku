# Anmerkungen zur LaTeX-Vorlage
Vorlage für Student*innen der DHBW Ravensburg, Campus Friedrichshafen, zur Anfertigung von Praxisberichten, Hausarbeiten, Studienarbeiten und Bachelorarbeiten.

Benutzen Sie für diese Vorlage zur Erstellung des Literaturverzeichnisses Biber anstatt BibTeX.
* In TeXstudio einzustellen im Menü unter Optionen-TeXstudio konfigurieren-Erzeugen-Standard Bibliographieprogramm-Biber.
* Zur Erzeugung der .bib-Datei sind Literaturverwaltungsprogramme wie zum Beispiel Citavi, JabRef oder Zotero hilfreich. Bei Verwendung von Citavi sind die speziellen BibTeX-Optionen beim Exportieren der .bib-Datei zu deaktivieren (Großbuchstaben in geschweifte Klammern setzen, LaTeX-Notation verwenden, URL-Package verwenden).
* Die Vorlage umfasst u.a. das Literaturverzeichnis, ein Abkürzungsverzeichnis, ein Sachwortverzeichnis und ein Glossar. Damit diese dargestellt werden, müssen nach einer ersten Kompilierung die Befehle biber, makeindex und makeglossaries ausgeführt werden. Gute LaTeX-Editoren haben die entsprechenden Befehle hinterlegt. Danach muss das Projekt nochmals in einem zweiten Lauf kompiliert werden. Ggf. ist ein dritter Lauf erforderlich, damit alle Seitenreferenzen, z. B. im Sachwortverzeichnis, korrekt aktualisiert werden.

Für LaTeX-Neueinsteiger sind im [Wiki](https://github.com/tkibler/vorlage_latex_doku/wiki) eine Installationsanleitung und eine Kurzeinführung zum Arbeiten mit LaTeX beinhaltet.