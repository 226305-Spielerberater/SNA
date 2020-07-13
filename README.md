# Datensatz Netzwerkforschung Spielerberater SNA_5

Codebuch Stand 2020-01-07
erstellt von 

Inhalt
Edges.csv (Edgelist)
Nodes.csv (Nodelist)
Codebuch.rm (Codierung der Datensätze)
Ursprung und Datenerhebung
xxx
Wir haben den Datensatz uber das Portal transfermarkt.de für den Kurs Netzwerkanalyse erhoben. 
Das Netzwerk ist ein gerichtetes two-mode Ego/Akteursnetzwerk. Es wurden folgende Fragen erhoben:
https://www.ran.de/fussball/bildergalerien/top-8-diese-spielerberater-kassierten-2018-die-hoechsten-provisionen

Edge-Attribute
relation
1=Geschäftsbeziehung zwischen Spielerberater und Fußballprofi
2=Liga-Beziehung (der Spieler spielt in der Liga)
3=Vereinsbeziehung
4=Nationalmannschaftsbeziehung



Node-Attribute

type
Netzwerk ist ein two-mode-Netzwerk mit zwei Typen von Akteuren/Knoten:

0=Personen (Spielerberater, Fußballprofis)
1=Organisationen/Vereine

age
1=18-21
2=22-25
3=26-29
4=30-33
5=34 und älter
nation
Nationalität
value
Marktwert der Spieler

1=5-10 Mio. Euro
2=11-20 Mio. Euro
3=21-30 Mio.
4=31-40 Mio.
5=41-50 Mio.
6=51-60 Mio.
7=61 Mio. und höher. 

position
Position der Profi-Fußballer. Bei Spielern, die mehrere Positionen spielen können, wird deren hauptsächliche Positionsrolle verwendet. 

1= Torwart
2=Verteidiger
3=Mittelfeldspieler
4=Angreifer


