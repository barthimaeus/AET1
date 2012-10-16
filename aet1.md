# Literatur

* Bronstein 
* Philippow - Grundlagen der Elektrotechnik
* Busch - Elektrotechnik und Elektronik (Bibo)

# Anwendungen von Elektrotechnik

* Energieversorgung (Haushalte, Industrie, ...)
* Stromversorgungstechnik
* Antriebstechnik
* Datenverarbeitung - Informationstechnik
* Kommunikationstechnik

# Einführung - Grundbegriffe

## Ladung und Strom

Strom = Bewegung von Ladungsträgern
* Elektronen (z.B. in Metallen)
	* negativ mit Elementarladung ![equation](http://latex.codecogs.com/gif.latex?Q%3D-e) geladen
	* ![equation](http://latex.codecogs.com/gif.latex?e=1,602*10⁻¹⁹C)
	* ![equation](http://latex.codecogs.com/gif.latex?[Q]=[e]=C) Coulomb (1.1)
* Ionen (z.B. Flüssigkeiten, Plasma, ...)

Analogie: Fließendes Wasser
* Maß für dessen Flussvolumen V pro Zeit t
	* ![equation](http://latex.codecogs.com/gif.latex?%5Cfrac%7Bdv%7D%7Bdt%7D)
* vergleichbar -> Maß für Stromfluß i: Ladung Q pro Zeit t (1.2) 
	* ![equation](http://latex.codecogs.com/gif.latex?i%3D%5Cfrac%7BdQ%7D%7Bdt%7D) 
	* Einheit
		* ![equation](http://latex.codecogs.com/gif.latex?%5Bi%5D%3D%5BQ%5D/%5Bt%5D%3DC/s%3DA%5C%3BAmpere)

###Beispiel: Stromfluß durch Querschnittsfläche einer Leiters:

* positive Ladungsträger Q>0
	* Zählweise: Durchfluss v.l.n.r 
		* ![equation](http://latex.codecogs.com/gif.latex?i%20%3D%20%28dQ%29/%28dt%29%20%3E%200)
	* umgekehrte Zählweise v.r.n.l 
		* ![equation](http://latex.codecogs.com/gif.latex?i%20%3D%20%28dQ%29/%28dt%29%20%3C%200)
* negative Ladungsträger Q<0
	* Zählweise: Durchfluss v.r.n.l 
		* ![equation](http://latex.codecogs.com/gif.latex?i%20%3D%20%28dQ%29/%28dt%29%20%3E%200)
	* umgekehrte Zählweise v.l.n.r 
		* ![equation](http://latex.codecogs.com/gif.latex?i%20%3D%20%28dQ%29/%28dt%29%20%3C%200)

* positiver Strom wenn:
	* positive Ladungsträger sich in Richtung des Bezugspfeils bewegen (tech. Stromrichtung)
	* negative Ladungsträger sich entgegen der Richtung des Bezugspfeils bewegen (phys. Stromrichtung)

* typische Stromverläufe nach (1.2)
	* Gleichstrom: konstant
		* ![equation](http://latex.codecogs.com/gif.latex?%28dQ%29/%28dt%29%3DI) 
	* Wechselstrom: zeitabhängig mit Mittelwert Null über eine Periodendauer Tp
		* ![equation](http://latex.codecogs.com/gif.latex?%28dQ%29/%28dt%29%3Di%28t%29%5Cqquad%281/T_p%29*%5Cint_T_p%28i%28t%29dt%29%3D0)
			* z.B. sinusförmig
				* ![equation](http://latex.codecogs.com/gif.latex?i%28t%29%3D%5Chat%7BI%7Dsin%28wt%29%3D%5Chat%7BI%7Dsin%28%28%282%5Cpi%29/T_p%29*t%29)

* Bezeichnungsweise
	* Zeitwerte mit Kleinbuchstaben
		* ![equation](http://latex.codecogs.com/gif.latex?i%28t%29)
	* Mittelwerte - insbesondere auch Gleichgrößen - mit Großbuchstaben
		* ![equation](http://latex.codecogs.com/gif.latex?I)
	* Amplituden mit Großbuchstaben der (mit Dach)
		* ![equation](http://latex.codecogs.com/gif.latex?%5Chat%7BI%7D)

## Potentiale und Spannungen

Ursache für Strömung einer Flüssigkeit im Rohr ist die Druckdifferenz:

![equation](http://latex.codecogs.com/gif.latex?%5Cbegin%7Bmatrix%7D%20p1-p2%20%3D%200%20%26%20-%20%5C%5C%20p1-p2%20%3E%200%20%26%20v.l.n.r%20%5C%5C%20p1-p2%20%3C%200%20%26%20v.r.n.l%20%5Cend%7Bmatrix%7D)

Analogie: Elektrische Potentialdifferenz - Spannung U - führt zu Stromfluß in einem Widerstand R

![equation](http://latex.codecogs.com/gif.latex?%5Cbegin%7Bmatrix%7D%20U%3D0%20%26%20i%3D0%5C%5C%20U%3E0%20%26%20i%3E0%5C%5C%20U%3C0%20%26%20i%3C0%20%5Cend%7Bmatrix%7D)

Einheit 

![equation](http://latex.codecogs.com/gif.latex?%5Bu%5D%20%3D%20V%5C%3BVolt)

## Widerstand
Fluß durch ein Rohr ist begrenzt, hängt von Druckdifferenz ab -> Rohr setzt Fluß Widerstand entgegen.
Analogie: in einem elektrischen Widerstand R ist Strom proportional zu Spannung  u
* (1.3) Ohmsches Gesetz:
	* ![equation](http://latex.codecogs.com/gif.latex?R%3D%28u/i%29)
	* Einheit
		* ![equation](http://latex.codecogs.com/gif.latex?%5BR%5D%3D%5Bu%5D/%5Bi%5D%3DV/A%3D%5COmega%5C%3BOhm)

Widerstand R eines Leiters nimmt
* mit steigender Länge l zu
* mit steigender Querschnittsfläche ab
* Spezifischer Widerstand
	* ![equation](http://latex.codecogs.com/gif.latex?R%3D%5Cvarrho*1/A) 
	* ![equation](http://latex.codecogs.com/gif.latex?%5Cvarrho%3D%28%5BR%5D%5BA%5D%29/%5Bl%5D%20%3D%20%5Cfrac%7B%28%5COmega*m%5E2%29%7D%7Bm%7D%20%3D%20%5COmega%20m)
	* temperaturabhängig mit Temperaturkoeffizienten 'alpha'
		* 'alpha' für lineare Näherung:
			* ![equation](http://latex.codecogs.com/gif.latex?%5Cvarrho%28t%29%3D%5Cvarrho%28T_0%29*%281&plus;%5Calpha%20%28T-T_0%29%29)
		* 'alpha' und 'beta' für quadratische Näherung
			* ![equation](http://latex.codecogs.com/gif.latex?%5Cvarrho%28t%29%3D%5Cvarrho%28T_0%29%281&plus;%5Calpha%28T-T_0%29&plus;%5Cbeta%28T-T0%29%5E2%29)
			* mit Temperatur T, für die 'rho' angegeben werden soll, und Bezugstemperatur T0, für die 'alpha' und 'beta' angegeben werden.
	* ![equation](http://latex.codecogs.com/gif.latex?%5BT%5D%5BT0%5D%3DK%5C%3BKelvin%20%5Cquad%5B%5Calpha%5D%3DK%5E%7B-1%7D%5B%5Cbeta%5D%3DK%5E%7B-2%7D)
		* wobei für Konstantan 'alpha'=0
	* (1.5) Kehrwert ist der Leitwert 
		* ![equation](http://latex.codecogs.com/gif.latex?G%3D1/R)
		* Einheit
			* ![equation](http://latex.codecogs.com/gif.latex?%5BG%5D%20%3D%201/%5BR%5D%20%3D%201/%5COmega%20%3D%20S%5C%3B%20Siemens)
			* für einen Leiter entsprechend (1.4) 
				* ![equation](http://latex.codecogs.com/gif.latex?G%20%3D%20K*%28A/l%29) (1.6) mit spezifischem Leitwert K als temperaturabhängiger Materialkonstante
				* Einheit
					* ![equation](http://latex.codecogs.com/gif.latex?%5BK%5D%20%3D%201/%5B%5Cvarrho%5D%20%3D%201/%5B%5COmega*m%5D%20%3D%20S/m)

Folgende Betrachtung zunächst am Beispiel elektrischer Widerstände; weitere Bauelemente mit anderem Verhalten, z.B.
* Induktivitäten 2.3.1
* Kapazitäten 2.3.2
* Halbleiter AET2


## Leistung und Energie

auf eine "Scheibe" A in einem Rohr wirkt wegen Druckdifferenz zwischen Rohrenden eine Kraft
* ![equation](http://latex.codecogs.com/gif.latex?F%3D%28p_1-p_2%29*a)
* A werde mit Geschwindigkeit ![equation](http://latex.codecogs.com/gif.latex?v%20%3D%20dl/dt) verschoben
* -> innerhalb eines Zeitintervalls dt wird ein Volumen A*dl verschoben
	* Leisung ![equation](http://latex.codecogs.com/gif.latex?p%20%3D%20F*%28dl/dt%29%3D%28p_1-p_2%29*A*%28dl/dt%29)
* Analogie: elektrische Leistung bei Stromfluß mit Spannungsabfall
	* (1.7) ![equation](http://latex.codecogs.com/gif.latex?p%28t%29%3Du%28t%29*%28dQ/dt%29%3Du%28t%29*i%28t%29%29%29)
	* Einheit
		* ![equation](http://latex.codecogs.com/gif.latex?%5Bp%5D%3D%5Bu%5D%5Bi%5D%3DV*A%3DW%5C%3BWatt)
	* verrichtete Arbeit 
		* (1.8) ![equation](http://latex.codecogs.com/gif.latex?W%20%3D%20%5Cint%20p%28t%29dt%3D%20%5Cint%20u%28t%29*%28du/dt%29*dt)
	* bei konstanter Spannung u(t)=u
		* (1.9) ![equation](http://latex.codecogs.com/gif.latex?W%3DU*%5Cint%20%28dQ/dt%29dt%3DU*Q)
	* Einheit
		* ![equation](http://latex.codecogs.com/gif.latex?%5BW%5D%3D%5Bu%5D%5BQ%5D%3DV*A*s%3DWs%3DJ%20%5C%3BWattsekunden/%20Joule)
	* Widerstand R nimmt bei Stromfluß i elektrische Leistung auf -> Umwandlung in Wärme
		* (1.10) ![equation](http://latex.codecogs.com/gif.latex?p%28t%29%3Du%28t%29*i%28t%29%3Du%5E%7B2%7D/R%3DR*i%5E%7B2%7D)

## Quellen
Leistung, die u.a. in Widerständen verbraucht wird muß wegen Energieerhaltung an anderer Stelle abgegeben werden - z.B. von
* Spannungsquellen 
	* ![schaltsymbol](http://upload.wikimedia.org/wikipedia/commons/thumb/5/56/Quelle_U-Schaltzeichen.svg/150px-Quelle_U-Schaltzeichen.svg.png)
	* U ist vorgegeben, i stellt sich abhängig von der Last ein
		* ![equation](http://latex.codecogs.com/gif.latex?i%3D%28U/R%29)
	* ![equation](http://latex.codecogs.com/gif.latex?p%3Du*i)
		* kann positiv sein -> Spannungsquelle gibt Leistung ab z.B. in Verbindung mit Widerstand (R)
		* kann negativ sein -> Spannungsquelle nimmt Leistung auf
* Stromquellen
	* ![schaltsymbol](http://upload.wikimedia.org/wikipedia/commons/thumb/c/c0/International_graphic_symbols_of_current_source.png/330px-International_graphic_symbols_of_current_source.png)
	* i ist vorgegeben, U stellt sich abhängig von der Last ein, hier
		* ![equation](http://latex.codecogs.com/gif.latex?u%20%3D%20R%20*%20i)
	* ![equation](http://latex.codecogs.com/gif.latex?p%20%3D%20u*i)
		* kann positiv sein -> Stromquelle gibt Leistung ab, z.B. in Verbindung mit einem Widerstand
		* kann negativ sein -> Stromquelle nimmt Leistung auf
* Zählweisen
	* Verbraucher-Bezugspfeilsystem (z.B. am Widerstand)
		* Element nimmt Leistung auf, für 
			* ![equation](http://latex.codecogs.com/gif.latex?p%20%3D%20u*i%20%3E0)
		* Element gibt Leistung ab, für 
			* ![equation](http://latex.codecogs.com/gif.latex?p%20%3D%20u*i%20%3C0)
	
	* Erzeuger-Bezugspfeilsystem
		* Element gibt Leistung ab, für 
			* ![equation](http://latex.codecogs.com/gif.latex?p%20%3D%20u*i%20%3E0)
		* Element nimmt Leistung auf, für
			* ![equation](http://latex.codecogs.com/gif.latex?p%20%3D%20u*i%20%3C%200)
	* Vorzeichen der Größen in Abhängigkeit von Bezugspfeilen zu beachten!

# Stromkreise

## Grundregeln
* Strom fließt im Stromkreis
	* Beispiel: Autobatterie mit Gleichspannung
		* U=12V speist Scheinwerferlampe mit p=55W 
		* ![equation](http://latex.codecogs.com/gif.latex?I%3DP/U%3D55W/12V%3D55VA/12V%3D%2855/12%29A%3D4%2C6A)
		* Batterie gibt Leistung ab, Glühlampe setzt in Wärme und Licht um
		* mit Sicherung ![schaltsymbol](http://upload.wikimedia.org/wikipedia/commons/thumb/3/3b/Fuse_symbol_Europe.svg/90px-Fuse_symbol_Europe.svg.png)
			* dünner Draht, wird bei Stromfluß heiß, brennt bei Überstrom durch
			* zusätzlicher Spannungsabfall U_Sicherung -> U_Bat != U_Lampe
	* im Stromkreis mit mehr als zwei Elementen können mehrere Knoten und Maschen vorhanden sein
		* Knoten (Verknüpfungspunkte mehrerer Leitungen)
		* Maschen (Kleinere Kreise im Stromkreis)

* Knotenregel (Kirchhoff)
	* Rohrnalogie: in Rohrverzweigung fließt gleich viel Flüssigkeit hinein wie hinaus
	* Die Summe aller auf einen Knoten zufließenden Ströme ist gleich der Summe aller der von diesem Knoten wegfließenden Ströme
		* einfachster Fall ![equation](http://latex.codecogs.com/gif.latex?i_1%3Di_2&plus;i_3)
		* i_1 fließt auf Knoten zu, i_2, i_3 fließen von Knoten weg

* Maschenregel
	* Rohranalogie: Über verschiedene Leitungsverbindungen fällt die gleiche Druckdifferenz p_1-p_2 ab
	* Die Summe aller Spannungen beim vollständigen Umlauf einer Masche ist Null
	* Zählweise
		* Spannungen in Richtung des Umlaufes positiv
		* Spannungen gegen die Richtung des Umlaufs negativ
		
## Berechnung von Netzwerken mit Widerständen

### Parallelschaltung, Stromteiler
* an Widerständen R_1...R_n liegt bei Parallelschaltung die gleiche Spannung U_0 an
* ![equation](http://latex.codecogs.com/gif.latex?i_k%3DU_0/R_k)
	* Stromaufteilung antiproportional zu den Widerständen R_k
* (2.1)
	* ![equation](http://latex.codecogs.com/gif.latex?i_0%20%3D%20%5Csum%20_%7Bk%3D1%7D%5E%7Bn%7DU_0/R_k%3DU_0*%5Csum_%7Bk%3D1%7D%5E%7Bn%7D1/R_k)
* (2.2)
	* ![equation](http://latex.codecogs.com/gif.latex?R_0%3DU_o/i_0%3D1/%28%5Csum_%7Bk%3D1%7D%5En1/R_k%29)
* Beispiel mit zwei Widerständen R_1, R_2
	* (2.3) 
		* ![equation](http://latex.codecogs.com/gif.latex?R_0%20%3D%201%20/%20%28%281/R_1%29&plus;%281/R_2%29%29%20%3D%20%28R_1*R_2%29/%28R_1&plus;R_2%29)
	* Gesamtwiderstand R_0 < R_1 und R_0 < R_2 !
	* Anteiliger Stromfluß durch R_1 -> Stromteiler (2.4)
		* ![equation](http://latex.codecogs.com/gif.latex?%28i_1/i_0%29%20%3D%20%28i_1/%28i_1&plus;i_2%29%29%20%3D%20%28U_0/R_1%29/%28%28U_0/R_1%29&plus;%28U_0/R_2%29%29)
* Beispiel mit n gleichen Widerständen parallelgeschaltet
	* ![equation](http://latex.codecogs.com/gif.latex?R_0%3D1/%28n/r%29%3DR/n)
	* Anwendung: Meßbereichserweiterung für Strommeßer (Amperemeter)
		
	
