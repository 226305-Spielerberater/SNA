<h1>Datensatz Pretest Netzwerkforschung Spielerberater SNA_5</h1>

Codebuch Stand 2020-20-07 <p>
erstellt von Rippler, Volz, Palleit, Jung

<h2>Inhalt</h2>
<ul>
  <li>Edges.csv (Edgelist)</li>
  <li>Nodes.csv (Nodelist)</li>
  <li>Codebuch.md (Codierung der Datensätze)</li>
</ul>  
 
<h2>Ursprung und Datenerhebung<h2>

Wir haben den Datensatz uber das Portal transfermarkt.de für den Kurs Netzwerkanalyse erhoben. Wir untersuchen das Netzwerk der Spielerberatungsfirma Bahia Internacional. Wir haben diese Spielerberatungsfirma ausgewählt, da der Spielerberater Jose Otin dort arbeitet. Dieser belegt auf einer 
<a href="https://www.ran.de/fussball/bildergalerien/top-8-diese-spielerberater-kassierten-2018-die-hoechsten-provisionen">Liste der Spielerberater mit den meisten Provisionen 2018</a> Platz 5.
Liste der  Platz. Quelle:  https://www.ran.de/fussball/bildergalerien/top-8-diese-spielerberater-kassierten-2018-die-hoechsten-provisionen). 
Das Netzwerk ist ein gerichtetes two-mode Ego/Akteursnetzwerk. Es wurden folgende Fragen erhoben: Welche Profifußballer berät die Spielerberatungsfirma? Ist ein Muster erkennbar? 
Wir beschränken uns dabei auf die ersten 20 Spieler (Ceballos bis Camacho). Quelle: <a href="https://www.transfermarkt.com/bahia-internacional/beraterfirma/berater/1033">Transfermarkt</a>


<h2>Edge-Attribute</h2>

<h3>relation</h3>
1=Geschäftsbeziehung zwischen Spielerberater und Fußballprofi <p>
2=Liga-Beziehung (der Spieler spielt in der Liga) <p>
3=Vereinsbeziehung <p>
4=Nationalmannschaftsbeziehung /wenn Spieler aktuell in Nationalmannschaft spielt und bei transfermarkt.de im Kader derjeweiligen Nationalmannschaft gelistet ist) <p>



<h2>Node-Attribute</h2>

<h3>type</h3>
Netzwerk ist ein two-mode-Netzwerk mit zwei Typen von Akteuren/Knoten: <p>

1=Personen (Spielerberater, Fußballprofis)<p>
2=Organisationen/Vereine

<h3>age</h3>

1=18-21 <p>
2=22-25 <p>
3=26-29 <p>
4=30-33 <p>
5=34 und älter <p>

<h3>nation</h3>

1=Spanien

<h3>value</h3>
Marktwert der Spieler in Euro <p>

1=5-10 Mio. Euro <p>
2=11-20 Mio. Euro <p>
3=21-30 Mio. <p>
4=31-40 Mio. <p>
5=41-50 Mio. <p>
6=51-60 Mio. <p>
7=61 Mio. und höher. <p>

<h3>position</h3>

Position der Profi-Fußballer. Bei Spielern, die mehrere Positionen spielen können, wird deren hauptsächliche Positionsrolle verwendet. <p>

1= Torwart <p>
2=Verteidiger <p>
3=Mittelfeldspieler <p>
4=Angreifer <p>


