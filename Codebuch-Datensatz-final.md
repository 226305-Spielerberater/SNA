<h1>finaler Datensatz Netzwerkforschung Spielerberater SNA_5</h1>

Codebuch Stand 2020-27-10 <p>
erstellt von Rippler, Volz, Palleit, Jung


<h2>Inhalt</h2>
<ul>
<li>Edges.csv (Edgelist)</li>
<li>Nodes.csv (Nodelist)</li>
<li>Codebuch.rm (Codierung der Datensätze)</li>
</ul>
<h2>Ursprung und Datenerhebung</h2>

Wir haben den Datensatz uber das Portal transfermarkt.de für den Kurs Netzwerkanalyse erhoben. Die Basis bildet ein <a href="https://www.ran.de/fussball/bildergalerien/top-8-diese-spielerberater-kassierten-2018-die-hoechsten-provisionen">Ranking der erfolgreichsten Spielerberater nach Provisionen im Jahr 2018.</a>

<p>Untersucht werden die Klienten der Spielerberater oder Spielerberaterfiirmen von Jorge Mendes (Agentur: "Gestifute"), Jonathan Barnett (Agentur: "Stellar Football Ltd."), Mino Raiola, Volker Struth (Agentur: "Sports Total"), Jose Otin (Agentur: "Bahia Internacional"), Meissa N'Diaye, Thomas Kroth (Agentur: "Pro Profil GmbH") und Fernando Felicevich.</p>

<p>Das Netzwerk ist ein gerichtetes two-mode Teilnetzwerk. Es wurden folgende Fragen erhoben: Welche Profifußballer beraten die Spielerberatungsfirmen/Spielerberater? Ist ein Muster erkennbar? Und welche Beziehungen bestehen zwischen den Spielern der einzelnen Spielerberatern?</p>
Wir beschränken uns dabei auf die jeweils 20 wertvollsten Spieler nach Marktwert in Euro.
<p> Ausgangslage ist die Rückrunde der Saison 19/20 - die zwei Transferperioden von Juli bis Oktober 2020 werden also nicht berücksichtigt. </p>




<h2>Edge-Attribute</h2>
<h3>relation</h3>
<p>1=Geschäftsbeziehung zwischen Spielerberater und Fußballprofi </p>
2=Liga-Beziehung (der Spieler spielt in der Liga) <p>
3=Vereinsbeziehung (der Spieler spielt in diesem Verein) <p>
4=Nationalmannschaftsbeziehung (Spieler spielt in Nationalmannschaft: hierbei zählt der Nationalmannschaftskader des jeweiligen Landes von transfermarkt.de im Jahr 2019, da bis Septmeber 2020 wegen Corona wenig bis gar keine Länderspiele stattgefunden haben) <p>
5=Teamkollegen im Verein (zwei Spieler spielen im selben Verein) <p>
6=Teamkollegen in der Nationalmannschaft (zwei Spieler spielen in der gleichen Nationalmannschaft) <p>



<h2>Node-Attribute</h2>
<h3>type</h3>
Netzwerk ist ein two-mode-Netzwerk mit zwei Typen von Akteuren/Knoten:

0=Personen (Spielerberater, Fußballprofis) <p>
1=Organisationen(Vereine, Ligen, Nationalmannschaften) <p>

<h3>age</h3>
1=18-21 <p>
2=22-25 <p>
3=26-29 <p>
4=30-33 <p>
5=34 und älter <p>
  
<h3>nation</h3>
bei doppelter Staatsbürgerschaft wird die erste Nation genommen <p>

1=spanisch <p>
2=deutsch <p>
3=schweiz <p>
4=französisch <p>
5=malisch (Mali) <p>
6=Österreich <p>
7=Portugisisch <p>
8=brasilianisch <p>
9=argentinisch <p>
10=Kolumbien <p>
11=Italien <p>
12=Norwegen <p>
13=Niederlande <p>
14=Griechenland <p>
15=Mexiko <p>
16=Algerien <p>
17= Zentralafrikanische Repuplik <p>
18=Marokko <p>
19=Belgien <p>
20=Kongo <p>
21=Luxemburg <p>
22=Japan <p>
23=Luxemburg <p>
24=Chile <p>
25=Venezuela <p>
26=Peru <p>
27=England <p>
28=Polen <p>
29=Urgugay <p>
30=Schottland <p>
31=Wales <p>
32=Albanien <p>
33=Kroatien <p>
34=Island <p>
35=Marokko <p>
36=Irland <p>
  
<h3>value</h3>
Marktwert der Spieler in Euro. Gegebenenfalls wird gerundet. <p> 

1 = unter 1 Mio. <p>
2= 1 - 5 Mio. <p>
3=6-10 Mio. <p>
4=11-20 Mio. <p>
5=21-30 Mio. <p>
6=31-40 Mio. <p>
7=41-50 Mio. <p>
8=51-60 Mio. <p>
9=61 Mio. und höher. <p> 
  
<h3>position</h3>
Position der Profi-Fußballer. Bei Spielern, die mehrere Positionen spielen können, wird deren hauptsächliche Positionsrolle verwendet. Flügelspieler zählen als Angreifer.

1= Torwart <p>
2=Verteidiger <p>
3=Mittelfeldspieler <p>
4=Angreifer <p>
  
<h3>agency</h3>
von welchem Spielerberater/von welcher Spielerberateragentur wird der Spieler beraten? 

1= Jorge Mendes (JM) <p>
2= Jonathan Barnett (JB) <p>
3=Mino Raiola(MR) <p>
4= Volker Struth / Sports Total (ST) <p>
5= Jose Otin / Bahia Internacional  (BI) <p>
6= Meissa N'Diaye  (MN) <p>
7= Thomas Kroth / Pro Profil GmbH (PROP) <p>
8= Fernando Felicevich (FF) <p>



<h3> league</h3>
In welcher Liga spielt der Spieler? Stand: Rückrunde Saison 19/20 <p>

1= 1. Bundesliga Deutschland <p>
2= 2. Bundesliga Deutschland <p>
3=Premier League England <p>
4= Championship (zweite englische Liga) <p>
5= BBVA / La Liga (erste spanische Liga) <p>
6=Segunda Division (zweite spanische Liga) <p>
7= dritte spanische Liga Gruppe 3 <p>
8= Serie A Italien <p>
9=Ligue 1 Frankreich <p>
10= Ligue 2 Frankreich <p>
11= Eredivise Holland <p>
11= Süper Lig Türkei <p>
12= Liga NOS Portugal <p>
13= Premier Russland <p>
14= Ungarn 1.Liga  <p>
15= J1 League Japan <p>
16= MLS USA <p>
17= Liga_MX Mexiko <p>
18= Serie_A_Brasilien <p>
19= Primera_Division Chile <p>
20= Superliga Argentinien <p>
21= Liga_One_Peru <p>
 
<h3>club</h3>
Bei welchem Verein spielt der Spieler? Stand: Rückrunde Saison 19/20 <p>
1=Arsenal London <p>
2=Real Sociedad San Sebastian <p>
3=Atletico Madrid <p>
4= FC Bayern München <p>
5=FC Chelsea <p>
6=Deportivo Alaves <p>
7=Atletic Bilbao <p>
8=Liverpool FC <p>
9=Betis Sevilla <p>
10=Levante UD <p>
11=FC Sevilla <p>
12=FC Barcelona B (zweite Mannschaft!!) <p>
13=UD Las Palmas <p>
14=FC Gijon <p>
15=Racing Santander <p>
16=Real Madrid <p>
17=RB Leipzig <p>
18= Borussia Dortmund <p>
19= Schalke 04 <p>
20= SC Freiburg <p>
21= FC Augsburg <p>
22= Newcastle <p>
23= Hertha BSC Berlin <p>
24= 1. FC Köln <p>
25=Eintracht Frankfurt <p>
26=VfL Wolfsburg <p>
27= Fortuna Düsseldorf <p>
28= Manchester City <p>
29 = Juventus Turin <p>
30 = Wolverhampton Wanderers <p>
31 = FC Barcelona <p>
32 = Benfica Lissabon <p>
33 = Paris Saint Germain <p>
34 = Leicester City <p>
35 = AC Mailand <p>
36= FC Valencia <p>
37= LOSC Lille <p>
38= FC Southampton <p>
39 = Brighton Holve & Albion <p>
40= Olympique <p>
41= AC Florenz <p>
42= Lazio Rom <p>
43= Manchester United <p>
44= FC Everton <p>
45= Aston Villa <p>
46= SSC Neapel <p>
47= Borussia Mönchengladbach <p>
48= PSV Eindhoven <p>
49= AS Rom <p>
50= AZ Alkmaar <p>
51= Genua <p>
52= Inter Mailand <p>
53= FC Fulham <p>
54= TSG 1899 Hoffenheim <p>
55= Ajax Amsterdam <p>
56= Crystal palace <p>
57= OGC Nizza <p>
58= West Ham united <p>
59= Tottenham Hotspurs <p>
60= Nottingham Forest <p>
61= FC Lorient<p>
62= FC Toulouse <p>
63= CD Nacionale <p>
64= FK Ufa <p>
65= Mol Fehera <p>
66= AJ Auxerre <p>
67= FSV Mainz 05 <p>
68= Huddersfield Town <p>
69= Bayer 04 Leverkusen <p>
70= Cerezo_Osaka <p>
71= Hannover 96 <p>
72= SD Huesca <p>
73= Union Berlin <p>
74= Nagoya <p>
75= Yokohama Marinos <p>
76= FC Tokyo <p>
77= Heracles Almelo <p>
78= Quakes <p>
79= Monarcas <p>
80= UANL Tigres <p>
81= Necaxa <p>
82= Atletico_MG <p>
83= Alanyaspor <p>
84= Bologna <p>
85= SD Eibar <p>
86= Kansas <p>
87= CDUC <p>
88= CD_Everton <p>
89= Universidad <p>
90= Racing <p>
91= Colo_Colo <p>
92= Cesar_Vallejo <p>
93= Huachipato <p>
94= AS Monaco <p>

<h3>international</h3>
Ist der Spieler aktueller Nationalspieler? (Stand: Nationalmannschaftskader 2019)
Und wenn ja, von welchem Team? <p>

0= kein aktueller Nationalspieler <p>
1= Nationalspieler Deutschland <p>
2= Nationalspieler Frankreich <p>
3=Nationalspieler Spanien <p>
4=Nationalspieler Italien <p>
5= Nationalspieler Mali <p>
6=  Nationalspieler Schweiz <p>
7= Nationalspieler Portugal <p>
8= Nationalspieler Brasilien  <p>
9 = Nationalspieler Kolumbien  <p>
10= Nationalspieler Irland <p>
11= Nationalspieler England <p>
12= kroatien <p>
13= Marokko <p>
14= Albanien <p>
15= Wales <p>
16= Schottland <p>
17= Uruguay <p>
18=Polen <p>
19= Norwegen <p>
20=Niederlande <p>
21= Armenien <p>
22= Zentralafrikanische Republik <p>
23= Elfenbeinküste <p>
24= Belgien <p>
25= Kongo <p>
26= Luxemburg <p>
27= Ungarn <p> 
28= Österreich <p>
29= Japan <p>
30= Chile <p>
31= Venezuela <p>


<h2>Abkürzungen</h2>


<h3>Abkürzungen Spielerberater/-firmen</h3> 
BI = Bahia Internacional <p>
ST = Sports Total <p>
MR = Mino Raiola <p>
PROP = Pro Profil GmBH <p>
FF = Fernando Felicevich <p>
JM= Jorge Mendes <p>
JB= Jonathan Barnett <p>
MN= Meissa N'diaye<p>

<h3>Abkürzungen Spieler</h3> 
Javi Martinez = Martinez_Javi <p>
Florian Müller = Mueller_Florian <p>
Alexis Sanchez = Alexis_Sanchez <p>
Junior Fernandes = Junior_Fernandes <p>


<h3>Abkürzungen Vereine</h3>
Betis Sevilla = Betis_Sevilla <p>
FC Sevilla = Sevilla_FC <p>
Deportivo Alaves = Alaves <p>
Real Sociedad = Sociedad <p>
Barcelona B = Barcelona_B <p>
Real Madrid = Real <p>
UD Las Palmas = Palmas <p>
Manchester City = ManCity <p>
Manchester United= Manu <p>
Dortmund = BVB <p>
RB Leipzig = RB_Leipzig <p>
AS Rom = Rom_AS <p>
AC Mailand = Mailan_AC <p>
Juventus Turin = Juventus <p>
Paris St Germain = PSG <p>
SSC Neapel = Neapel <p>
Inter Mailand = Inter <p>
Ajax Amsterdam = Ajax <p>
Crystal Palace = Crystal_Palace <p>
West Ham United = West_Ham <p>
<h3>Abkürzungen Ligen</h3>
Barclays Premier League 1. Liga England = BPL <p>
Championship= CS <p>
Erste Spanische Liga = BBVA <p>
Zweite spanische Liga (Segunda División) = SD <p>
Dritte Spanische Liga Gruppe 3 (Segunda Division B Grupo Tres) = SDBGTres <p>
Serie A= Serie_A <p>
Eredivise= Ere <p>
Ligue 1 = Ligue_un <p>
Ligue 2= Ligue_deux <p>
Süper Lig= Sueper <p>
Liga Nos= NOS <p>
Premier Liga= Premier <p>
1.Liga ungarn= NB <p>
J1 League = J_One_League <p>
2. Bundesliga = Zweite_Bundesliga <p>
MLS = Major League Soccer <p>
Liga MX = Liga_MX <p>
Serie A (Brasilien) = Serie_A_Brasilien <p>
Primera Division (Chile) = Primera_Division <p>
Superliga/Primera Division (Argentinien) = Superliga <p>
Liga 1 (Peru) = Liga_One <p>


