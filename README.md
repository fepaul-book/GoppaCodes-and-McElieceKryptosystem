# Goppa Codes und das McEliece Kryptosystem

Dieses Repository enthält den Code zum Buch "Goppa Codes und das McEliece-Kryptosystem" von Felix Paul.

Der Code ist in SageMath geschrieben und kann einfach über [cocalc](https://cocalc.com/share/public_paths/17b07fa7f0dbaeff34f51c697d03e9c86ddc06df) 
ausprobiert werden. (Beachte: Um alle Outputs zu sehen, muss man in den Output-Zellen nach unten scrollen!) 

Für eine lokale Ausführung des Codes, installiere SageMath und Jupyter Notebooks. 

Die Programmierung erlaubt verschiedene Level der "verbosity" zu wählen, sodass man beim Ausprobieren des Codes einstellen kann, wie viele Erklärungen in der Kommandozeile angezeigt werden.

Für eine schnelle Analyse des Codes können auch die pdf-Dateien als Referenz genutzt werden.


Der Code ermöglicht:

Goppa Codes
--------------

- das praktische Erzeugen von Goppa Codes
	- verschiedene Verfahren zur Wahl des Goppa Polynoms
	- verschiedene Verfahren zur Wahl des Supports
	- Erzeugung der Kontroll- und Generatormatrix
	- Konvertierung der Matrizen von F_{2^m} ins Binäre

- die praktische Anwendung von Goppa Codes
	- Codierung
	- verschiedene Verfahren zur Fehlervektorerzeugung
	- Decodierung nach Patterson

McEliece Kryptosystem
-----------------------

- Key Generierung
- Verschlüsselung
- Entschlüsselung

Niederreiter Kryptosystem
-----------------------

- Key Generierung
- Verschlüsselung
- Entschlüsselung

Beispiele
-----------

- deterministisches Beispiele zu McEliece und Niederreiter
- Änderung der Supportreihenfolge
- Demonstration, dass McEliece nicht CCA-2 sicher ist





