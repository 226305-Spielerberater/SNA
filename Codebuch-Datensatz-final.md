<h1>finaler Datensatz Netzwerkforschung Spielerberater SNA_5</h1>

Codebuch Stand 2020-02-10 <p>
erstellt von Rippler, Volz, Palleit, Jung

Codebuch Stand 2020-24-07
erstellt von Volz, Rippler, Palleit und Jung

<h2>Inhalt</h2>
<ul>
<li>Edges.csv (Edgelist)</li>
<li>Nodes.csv (Nodelist)</li>
<li>Codebuch.rm (Codierung der Datensätze)</li>
</ul>
<h2>Ursprung und Datenerhebung</h2>

Wir haben den Datensatz uber das Portal transfermarkt.de für den Kurs Netzwerkanalyse erhoben. Die Basis bildet ein <a href=”"https://www.ran.de/fussball/bildergalerien/top-8-diese-spielerberater-kassierten-2018-die-hoechsten-provisionen"<Ranking der erfolgreichsten Spielerberater nach Provisionen im Jahr 2018.</a>

<p>Untersucht werden die Klienten der Spielerberater oder Spielerberaterfiirmen von Jorge Mendes, Jonathan Barnett, Mino Raiola, Volker Struth / Sports Total, Jose Otin / Bahia Internacional, Meissa N'Diaye, Thomas Kroth / Pro Profil GmbH, Fernando Felicevich.</p>

<p>Das Netzwerk ist ein gerichtetes two-mode Teilnetzwerk. Es wurden folgende Fragen erhoben: Welche Profifußballer beraten die Spielerberatungsfirmen/Spielerberater? Ist ein Muster erkennbar? Und welche Beziehungen bestehen zwischen den Spielern?</p>
Wir beschränken uns dabei auf die jeweils 20 wertvollsten Spieler nach Marktwert in Euro.
<p> Ausgangslage ist die Rückrunde der Saison 19/20 - die zwei Transferperioden von Juli bis Oktober 2020 werden also nicht berücksichtigt. </p>




<h2>Edge-Attribute</h2>
<h3>relation</h3>
1=Geschäftsbeziehung zwischen Spielerberater und Fußballprofi
2=Liga-Beziehung (der Spieler spielt in der Liga)
3=Vereinsbeziehung (der Spieler spielt in diesem Verein)
4=Nationalmannschaftsbeziehung (Spieler spielt in Nationalmannschaft;: hierbei zählt der Nationalmannschaftskader des jeweiligen Landes von transfermarkt.de im Jahr 2019, da bis Septmeber 2020 wegen Corona wenig bis gar keine Länderspiele stattgefunden haben)
5=Teamkollegen im Verein (zwei Spieler spielen im selben Verein)
6=Teamkollegen in der Nationalmannschaft (zwei Spieler spielen in der gleichen Nationalmannschaft) 



<h2>Node-Attribute</h2>
<h3>type</h3>
Netzwerk ist ein two-mode-Netzwerk mit zwei Typen von Akteuren/Knoten:

0=Personen (Spielerberater, Fußballprofis) <p>
1=Organisationen/Vereine

<h3>age</h3>
1=18-21
2=22-25
3=26-29
4=30-33
5=34 und älter
<h3>nation</h3>
bei doppelter Staatsbürgerschaft wird die erste Nation genommen <p>

1=spanisch <p>
2=deutsch <p>
3=schweiz <p>
4=französisch <p>
5=malisch (Mali) <p>
6=Österreich
7=Portugisisch 
8=Brasilianisch 
9=argentinisch
10=Kolumbien 
11=Italien
12=Norwegen
13=Niederlande
14=Griechenland
15=Mexiko
16=Algerien
17= Zentralafrikanische Repuplik
18=Marokko
19=Belgien
20=Kongo
21=Luxemburg
22=Japan
23=Luxemburg
24=Chile
25=Venezuela
26=Peru
27=England
28=Polen
29=Urgugay
30=Schottland
31=Wales
32=Albanien
33=Kroatien
34=Island
35=Marokko
<h3>value</h3>
Marktwert der Spieler in Euro. Gegebenenfalls wird gerundet. <p> 

1 = unter 1 Mio. <p>
2= 1 - 5 Mio.
3=6-10 Mio. 
4=11-20 Mio.
5=21-30 Mio.
6=31-40 Mio.
7=41-50 Mio.
8=51-60 Mio.
9=61 Mio. und höher. 
<h3>position</h3>
Position der Profi-Fußballer. Bei Spielern, die mehrere Positionen spielen können, wird deren hauptsächliche Positionsrolle verwendet. Flügelspieler zählen als Angreifer.

1= Torwart
2=Verteidiger
3=Mittelfeldspieler
4=Angreifer


<h3>Abkürzungen Spielerberater/-firmen</h3> 
BI = Bahia Internacional 
ST = Sports Total
MR = Mino Raiola
PROP = Pro Profil GmBH
FF = Fernando Felicevich

<h3>Abkürzungen Spieler</h3> 
Javi Martinez = Martinez_Javi
Florian Müller = Mueller_Florian
Alexis Sanchez = Alexis_Sanchez
Junior Fernandes = Junior_Fernandes


<h3>Abkürzungen Vereine</h3>
Betis Sevilla = Betis_Sevilla
FC Sevilla = Sevilla_FC
Deportivo Alaves = Alaves
Real Sociedad = Sociedad
Barcelona B = Barcelona_B
Real Madrid = Real
UD Las Palmas = Palmas
Manchester City = ManCity
Manchester United= Manu
Dortmund = BVB
RB Leipzig = RB_Leipzig
AS Rom = Rom_AS
AC Mailand = Mailan_AC
Juventus Turin = Juventus
Paris St Germain = PSG
SSC Neapel = Neapel
Inter Mailand = Inter 
Ajax Amsterdam = Ajax
Crystal Palace = Crystal_Palace
West Ham United = West_Ham
<h3>Abkürzungen Ligen</h3>
Barclays Premier League 1. Liga England = BPL
Championship= CS
Erste Spanische Liga = BBVA
Zweite spanische Liga (Segunda División) = SD
Dritte Spanische Liga Gruppe 3 (Segunda Division B Grupo Tres) = SDBGTres
Serie A= Serie_A
Eredivise= Ere
Ligue 1 = Ligue_un
Ligue 2= Ligue_deux
Süper Lig= Sueper
Liga Nos= NOS
Premier Liga= Premier
1.Liga ungarn= NB
J1 League = J_One_League
2. Bundesliga = Zweite_Bundesliga
MLS = Major League Soccer
Liga MX = Liga_MX
Serie A (Brasilien) = Serie_A_Brasilien
Primera Division (Chile) = Primera_Division
Superliga/Primera Division (Argentinien) = Superliga
Liga 1 (Peru) = Liga_One


