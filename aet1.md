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
	
### Reihenschaltung, Spannungsteiler
* reihengeschaltete Widerstände R_1...R_4 vom gleichen Strom durchflossen
* ![equation](http://latex.codecogs.com/gif.latex?U_k%20%3D%20R_k%20*%20i_0%20%5Cquad%20k%3D1...n)
* -> Spannungsteilung proportional zu den Widerständen
* Maschenregel
	* ![equation](http://latex.codecogs.com/gif.latex?U_0%20%3D%20%5Csum_%7Bk%3D1%7D%5E%7Bn%7DU_k%20%3D%20%5Csum_%7Bk%3D1%7D%5E%7Bn%7DR_k*i_0%20%3D%20i_0%20*%20%5Csum_%7Bk%3D1%7D%5E%7Bn%7D%20R_k)
* Gesamtwiderstand der Anordnung
	* ![equation](http://latex.codecogs.com/gif.latex?R_0%20%3D%20U_0/i_0%20%3D%20%5Csum_%7Bk%3D1%7D%5E%7Bn%7DR_k)
* Beispiel mit zwei Widerständen in Reihe
	* R_0 = R_1+R_2
		* Gesamtwiderstand R_0 > R_1 und R_0 > R_2
	* i_0 = U_0 / R_0 = U_0 / (R_1+R_2)
		* (2.8)
			* ![equation](http://latex.codecogs.com/gif.latex?U_2%20%3D%20R_2*i_0%20%3D%20U_0%20*%20%28R_2%29/%28R_1&plus;R_2%29) 
		* Spannungsteiler (Voraussetzung i_0 fließt durch beide Widerstände, kein Stromfluss im Mittelabgriff)
	* mögliche Realisierung mit Potentiometer
		* Strecke A-C mit Widerstand R
		* Abgriff B an Position A
			* R_{AB} = 0
			* R_{BC] = R
		* Abgriff B an Position C
			* R_{AB} = R
			* R_{BC} = 0
		* Zwischen Positionen A und C: R_{AB} und R_{BC} variabel
			* ![equation](http://latex.codecogs.com/gif.latex?R%20%3D%20R_%7BAB%7D&plus;R_%7BBC%7D) 
* Anwendung: Meßbereichserweiterung für Spannungsmeßer (Voltmeter)
	* Strom fließt durch Vorwiderstand R und Voltmeter mit Widerstand des Meßwerks R_m
		* Spannungsteiler nach 2.8
		* ![equation](http://latex.codecogs.com/gif.latex?U_m/U_0%20%3D%20R_m/%28R&plus;R_m%29)
	* Mit Vorwiderstand R = 99*R_m fällt z.B. nur ab:
		* ![equation](http://latex.codecogs.com/gif.latex?U_m/U_0%20%3D%20R_m/%2899*R_m&plus;R_m%29%3D1/100)
		
### Quellen und Leistungsanpassung
* Reale Quelle mit Innenwiderstand
	* z.B. Spannungsquelle: Klemmenspannung einer Autobatterie bleibt bei Stromentnahme (Anlasser) ein
		* Ersatzschaltbild (Innenwiderstand R_i als "virtuelles Bauteil in Reihe hinter der Quelle)
		* Spannungsteiler zwischen Innen- und Lastwiderstand
			* ![equation](http://latex.codecogs.com/gif.latex?U%3DU_0*R/%28R&plus;R_i%29)
		* Kennlinie Klemmenspannung (Laststrom) nach Maschenregel (2.10)
			* ![equation](http://latex.codecogs.com/gif.latex?U_0%20-%20U%20-%20U_%7BR_i%7D%20%3D%200)
			* ![equation](http://latex.codecogs.com/gif.latex?U%20%3D%20U_0%20*%20R_i%20*%20i)
		* Kennwerte Leerlaufspannungs 
			* ![equation](http://latex.codecogs.com/gif.latex?u%28i%3D0%29%20%3D%20U_0)
		* Kurzschlußstrom 
			* ![equation](http://latex.codecogs.com/gif.latex?i%28u%3D0%29%3DU_0/R_i)
		* Arbeitspunkt am Schnittpunkt von Quellen- und Lastenlinie, z.B. bei Widerstandslast mit Kennlinie
			* ![equation](http://latex.codecogs.com/gif.latex?U%3DR*i)
		* -> abgegebene Leistung (2.11)
			* ![equation](http://latex.codecogs.com/gif.latex?p_a%20%3D%20%5Cfrac%7BU%5E2%7D%7BR%7D%5Cfrac%7BR%7D%7BR&plus;R_i%7D%5Cfrac%7BU_0%5E2%7D%7BR%7D%3D%5Cfrac%7BR%7D%7B%28R&plus;R_i%29%5E2%7D*U_0%5E2%3D%5Cfrac%7B%5Cfrac%7BR%7D%7BR_i%7D%7D%7B%28%5Cfrac%7BR%7D%7BR_i%7D&plus;1%29%B2%7D%5Cfrac%7BU_0%B2%7D%7BR_i%7D)
		* maximal für R=R_i -> Leistungsanpassung
		* Wirkungsgrad
			* Verhältnis an Last R abgegebener Leistung zu von Quelle U_0 erzeugter Leistung - vgl. (2.9)
			* (2.12)
				* ![equation](http://latex.codecogs.com/gif.latex?%5Ceta%3D%28U*i%29/%28U_0/i%29%3DR/%28R&plus;R_i%29%3D%5Cfrac%7B%5Cfrac%7BR%7D%7BR_i%7D%7D%7B%5Cfrac%7BR%7D%7BR&plus;R_i%7D&plus;1%7D)
			* steigt mit R/R_i
				* -> Auslegung R_i<<R in der Energietechnik um Verluste zu minimieren - bei Leistungsanpassung z.B. nur eta > 50 %

### Allgemeine Netzwerke
Schaltung besteht aus Spannungsquelle, einem Widerstand in Reihe und dann zwei Widerständen parallel
* Knotengleichungen
	* oberer Knoten (zwischen R_1, R_2, R_3)
		* ![equation](http://latex.codecogs.com/gif.latex?i_1%3Di_2&plus;i_3)
	* unterer Knoten
		* ![equation](http://latex.codecogs.com/gif.latex?i_2&plus;i_3%3Di_1)
* Maschengleichungen
	* linke Masche (2.15)
		* ![equation](http://latex.codecogs.com/gif.latex?U_1&plus;U_2-U_0%20%3D%200)
	* rechte Masche (2.16)
		* ![equation](http://latex.codecogs.com/gif.latex?U_3-U_2%20%3D%200)
	* äußere masche (2.17)
		* ![equation](http://latex.codecogs.com/gif.latex?U_1&plus;U_3-U_0%20%3D%200)
	* drei Gleichungen, davon eine abhängige - Einsetzten von (2.16) in (2.15) ergibt (2.17)
		* allgemein Maschengleichungen linear unabhängig, wenn jeder Maschenumlauf mindestens einen Zweig (zwischen zwei Knoten) allein durchläuft
	* mit Ohmschen Gesetz
		* ![equation](http://latex.codecogs.com/gif.latex?U_1%3DR_1&plus;i_1%5Cquad%20%282.18%29)
		* ![equation](http://latex.codecogs.com/gif.latex?U_2%3DR_2&plus;i_2%5Cquad%20%282.19%29)
		* ![equation](http://latex.codecogs.com/gif.latex?U_3%3DR_3&plus;i_3%5Cquad%20%282.20%29)
	* Berechnung aller Größen:
		* (2.19) (2.20) in (2.16) 
			* ![equation](http://latex.codecogs.com/gif.latex?0%20%3D%20R_3*i_3%20-R_2*i_2%20%3D%3E%20i_3%3D%28R_2/R_3%29*i_2%5Cquad%20%282.21%29)
			* ![equation](http://latex.codecogs.com/gif.latex?%3D%3E%20i_1%3D%281&plus;%28R_2/R_3%29%29*i_2%20%5C%5C%3D%3E%20i_2%20%3D%201/%281&plus;%28R_2/R_3%29%29*i_1%3DR_3/%28R_2&plus;R_3%29%29*i_1%20%5Cquad%20%282.22%29)
			* ![equation](http://latex.codecogs.com/gif.latex?%3D%3E%20i_3%20%3D%20%281-%28R_3/%28R_2&plus;R_3%29%29%29*i_1%20%3D%20R_2/%28R_2&plus;R_3%29*i_1%20%5Cquad%20%282.23%29)
			* ![equation](http://latex.codecogs.com/gif.latex?U_0%3DR_1&plus;%28%28R_2*R_3%29/%28R_2&plus;R_3%29%29*i_1%5C%5C%20i_1%3DU_0/%28R_1&plus;%28%28R_2*R_3%29/%28R_2&plus;R_3%29%29%29%20%5Cquad%20%282.24%29%5C%5C%20i_2%20%3D%20%5Cfrac%7BR_3%7D%7BR_2&plus;R_3%7D*%5Cfrac%7BU_0%7D%7BR_1&plus;%5Cfrac%7BR_2*R_3%7D%7BR_2&plus;R_3%7D%7D%20%5Cquad%20%282.25%29%20%5C%5C%20i_3%3D%5Cfrac%7BR_2%7D%7BR_2&plus;R_3%7D%5Cfrac%7BU_0%7D%7BR_1&plus;%5Cfrac%7BR_2*R_3%7D%7BR_2&plus;R_3%7D%7D%20%5Cquad%20%282.26%29%20%5C%5C%20U_1%20%3D%20...%20%282.27%29%5C%5C%20U_2%20%3D%20...%20%282.28%29%5C%5C%20U_3%20%3D%20...%20%282.29%29%5C%5C)
		* Stromteiler bestehend aus R_2 parallel zu R_3 nach (2.22) (2.23)
		* Spannungsteiler bestehend aus dem Oberen Widerstand und einem der unteren Widerstände (2.27)(2.28)(2.29)
		* Widerstand der Gesamtschaltung nach (2.24)
			* ![equation](http://latex.codecogs.com/gif.latex?U_0/R_1%20%3D%20R_1&plus;%20%28%28R_2*R_3%29/%28R_2&plus;R_3%29%29)
		* abhängige Gleichungen (2.14) (2.17) nicht verwendet
