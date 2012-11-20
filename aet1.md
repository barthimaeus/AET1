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

# 1 - Einführung - Grundbegriffe

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

# 2 - Stromkreise

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
* Vorgehensweise
	* Alle Ströme und Spannungen im Schaltbild markieren (willkürliche Polarität)
	* für k-1 von k Noten Knotengleichungen aufstellen
	* m Maschengleichungen so aufstellen, dass jede Masche mindestens einen Zweig als einzige durchläuft
	* Strom-Spannungs-Beziehungen für die Elemente aufstellen
	* Gleichungssystem mit k-1+m Unbekannnten nach den Punkten 2,3,4 lösen
* Überlagerungssatz:
	* Der Gesamtstrom in einem Zweig eines linearen Netzwerks ergibt sich aus der Summe der von den einzelnen Spannungsquellen herrührenden Teilströme.
		* Gilt für Netzwerke mit linearen Elementen, z.B. Widerständen mit U=R*i nach (1.3)


## Berechnung von Netzwerken mit Induktivitäten und Kapazitäten
### Induktivität
"speichert Fluss" - Analogie: von Flüssigkeit durchströmtes langes Rohr
* Änderung des Flusses (entspricht "i") erfordert Beschleunigung der Flüssigkeit -> Überwindung der Massenträgheit durch Druckdifferenz. p_⁻p_2 (entspricht "u")
	* Spannung proportional zur Ableitung des Stromes
	* ![equation](http://latex.codecogs.com/gif.latex?u%3DL*%5Cfrac%7Bdi%7D%7Bdt%7D)
	* ![Schaltsymbol](http://upload.wikimedia.org/wikipedia/de/thumb/9/91/Spule.svg/200px-Spule.svg.png)
	* Einheit
		* ![equation](http://latex.codecogs.com/gif.latex?%5BL%5D%3D%5Cfrac%7Bu%7D%7B%5Cfrac%7Bi%7D%7Bt%7D%7D%3D%5Cfrac%7BVs%7D%7BA%7D%5C%3BH%20Henry)
		* Lenzsche Regel
			* induzierte Spannung wirkt der Stromänderung entgegen
* Parallelschaltung
	* Knotengleichung 
		*![equation](http://latex.codecogs.com/gif.latex?i_0%20%3D%20%5Csum_%7Bk%3D1%7D%5Enik)
	* ![equation](http://latex.codecogs.com/gif.latex?%5Cfrac%7Bdi_0%7D%7Bdt%7D%3D%5Csum_%7Bk%3D1%7D%5E%7Bn%7D%5Cfrac%7Bdi_k%7D%7Bdt%7D)
	* ![equation](http://latex.codecogs.com/gif.latex?%5Cfrac%7Bdi_0%7D%7Bdt%7D%3Du_0*%5Csum_%7Bk%3D1%7D%5E%7Bn%7D%5Cfrac%7B1%7D%7BL_k%7D)
	* (2.49)
		* ![equation](http://latex.codecogs.com/gif.latex?L_0%20%3D%20%5Cfrac%7B1%7D%7B%5Csum_%7Bk%3D1%7D%5En%5Cfrac%7B1%7D%7BL_k%7D%7D)
* Reihenschaltung
	* Maschengleichung
		* ![equation](http://latex.codecogs.com/gif.latex?u_0%3D%5Csum_%7Bk%3D1%7D%5E%7Bn%7Du_k)
	* mit (2.48)
		* ![equation](http://latex.codecogs.com/gif.latex?u_0%3D%5Cfrac%7Bdi_0%7D%7Bdt%7D*%5Csum_%7Bk%3D1%7D%5E%7Bn%7DL_k)
		* (2.50)
		* ![equation](http://latex.codecogs.com/gif.latex?L_0%3D%5Csum_%7Bk%3D1%7D%5E%7Bn%7DL_k)
	* Addition der Induktivitäten
		* z.B. für 2 Induktivitäten L1 in Reihe
			* ![equation](http://latex.codecogs.com/gif.latex?L_0%3D2*L_1)
* Verbindung mit Gleichspannungsquelle U_0 (Stromkreis aus Quelle, Schalter S und Induktivität L)
	* Für t<=t_0, i=0
	* Schalter S ab t=t_0 geschlossen
		* Für t>=t_0 gilt mit (2.48)
			* ![equation](http://latex.codecogs.com/gif.latex?U_0%3Du%3DL*%5Cfrac%7Bdi%7D%7Bdt%7D)
			* ![equation](http://latex.codecogs.com/gif.latex?i%3D%5Cfrac%7BU_0%7D%7BL%7D*%5Cint_%7Bt_0%7D%5E%7Bt%7Dd%5Ctau)
		* Linearer Anstieg des Stroms (2.51)
			* ![equation](http://latex.codecogs.com/gif.latex?i%3D%5Cfrac%7BU_0%7D%7BL%7D*%28t-t_0%29)
		* gespeicherte Energie
			* ![equation](http://latex.codecogs.com/gif.latex?W%28t%29%3D%5Cint_%7Bt_0%7D%5E%7Bt%7Du%28%5Ctau%29*i%28%5Ctau%29d%5Ctau)
			* (2.51)
			* ![equation](http://latex.codecogs.com/gif.latex?W%28t%29%3D%5Cfrac%7BU_0%5E2%7D%7BL%7D%5Cint_%7Bt_0%7D%5E%7Bt%7D%28%5Ctau-t_0%29d%5Ctau)
			* ![equation](http://latex.codecogs.com/gif.latex?W%28t%29%3D%5Cfrac%7B1%7D%7B2%7D%5Cfrac%7BU_0%5E2%7D%7BL%7D%28t-t_0%29%5E2)
			* erneute Anwendung (2.51) ergibt (2.52)
			* ![equation](http://latex.codecogs.com/gif.latex?W%28i%29%3D%5Cfrac%7B1%7D%7B2%7DL*i%5E2)
	* Anmerkung - Abschalten von S für i>0
		* ![equation](http://latex.codecogs.com/gif.latex?%5Cfrac%7Bdi%7D%7Bdt%7D%3C%3C0)
		* nach (2.48) U<<0
		* Funkenbildung an Kontakten, bei Halbleiterschaltern; Freilauf erforgerlich
		
### Kapazität - Kondensator
Speichert Ladung - Analogie: durch Membran unterbrochenes, flüssigkeitgefülltes Rohr
* Änderung der Druckdifferenz p_1-p_2 (ent. "U")
* Fluss (ent. "i")
* Stromfluss proportional zur Ableitung der Spannung (2.53)
	* ![equation](http://latex.codecogs.com/gif.latex?i%3DC*%5Cfrac%7Bdu%7D%7Bdt%7D)
* Schaltzeichen
	* ![Schaltzeichen](http://upload.wikimedia.org/wikipedia/commons/thumb/5/5f/Kondensatoren-Schaltzeichen-Reihe.svg/500px-Kondensatoren-Schaltzeichen-Reihe.svg.png)
	* Elektrolytkondensator (Elko) darf nur mit Spannungen U>=0 betrieben werden
* Einheit der Kapazität
	* ![equation](http://latex.codecogs.com/gif.latex?%5BC%5D%3D%5Cfrac%7B%5Bi%5D%7D%7B%5Cfrac%7Bu%7D%7Bt%7D%7D%3D%5Cfrac%7BAs%7D%7BV%7D%3DF%5C%3B%20Farad)
* (2.53)
	* i=0 für Gleichspannung mit (du/dt)=0
	* i!=0 für Wechselspannung - mit (du/dt)!=0
* Parallelschaltung
	* Knotengleichung
	* ![equation](http://latex.codecogs.com/gif.latex?C_0%3D%5Csum_%7Bk%3D0%7D%5E%7Bn%7DC_k)
	* Addition der Kapazitäten z.b. für zwei parallele Kapazitäten C_1
		* ![equation](http://latex.codecogs.com/gif.latex?C_0%3D2*C_1)
* Reihenschaltung
	* Maschengleichung
	* ![equation](http://latex.codecogs.com/gif.latex?%5Cfrac%7Bdu_0%7D%7Bdt%7D%3D%5Csum_%7Bk%3D1%7D%5E%7Bn%7D%5Cfrac%7Bdu_k%7D%7Bdt%7D)
	* ![equation](http://latex.codecogs.com/gif.latex?%5Cfrac%7Bdu_0%7D%7Bdt%7D%3D%5Csum_%7Bk%3D1%7D%5E%7Bn%7D%5Cfrac%7Bi_0%7D%7BC_k%7D)
	* ![equation](http://latex.codecogs.com/gif.latex?i_0%3D%5Cfrac%7B1%7D%7B%5Csum_%7Bk%3D1%7D%5E%7Bn%7D%5Cfrac%7B1%7D%7BC_k%7D%7D*%5Cfrac%7Bdu_0%7D%7Bdt%7D)
	* (2.55)
		* ![equation](http://latex.codecogs.com/gif.latex?i_0%3DC_0%5Cfrac%7Bdu%7D%7Bdt%7D)
	* (2.56)
		* ![equation](http://latex.codecogs.com/gif.latex?C_0%3D%5Cfrac%7B1%7D%7B%5Csum_%7Bk%3D1%7D%5E%7Bn%7D%5Cfrac%7B1%7D%7BC_k%7D%7D)
	* Addition der Kehrwerte der Kapazitäten, z.B. für 2 Kapazitäten C1 in Reihe
		* ![equation](http://latex.codecogs.com/gif.latex?C_0%3D%5Cfrac%7BC_1%7D%7B2%7D)
* Entladung über Widerstand (Reihenschaltung aus Kondensator, Schalter S, Widerstand R)
	* Für t<=t_0 u=U_0
	* Schalter S ab t=t_0 geschlossen
	* Für t>=t_0 gilt (2.53)
		* ![equation](http://latex.codecogs.com/gif.latex?-i%3DC*%5Cfrac%7Bdu%7D%7Bdt%7D)
	* Ohmsches Gesetz i=(U/R) implizier Differentialgleichgung
		* ![equation](http://latex.codecogs.com/gif.latex?%5Cfrac%7Bdu%7D%7Bdt%7D%3D-1%5Cfrac%7B1%7D%7BRC%7D*U)
	* Lösung:
		* ![equation](http://latex.codecogs.com/gif.latex?u%28t%29%3DU_A*e%5E%28-%5Cfrac%7Bt-t_0%7D%7BR*C%7D%29)
		* Anfangsbedingung: 
			* ![equation](http://latex.codecogs.com/gif.latex?u%28t_0%29%3DU_0%3DU_a*e%5E%7B-%5Cfrac%7B0%7D%7BR*C%7D%7D)
		* Allgemeine Lösung (2.57):
			* ![equation](http://latex.codecogs.com/gif.latex?u%28t%29%3DU_0*e%5E%7B-%5Cfrac%7Bt-t_0%7D%7BR*C%7D%7D)
			* ![equation](http://latex.codecogs.com/gif.latex?%5Clim%5Climits_%7Bt%20%5Crightarrow%20%5Cinfty%7D%7Bu%28t%29%7D%3D0)
		* mit (2.54) ergibt sich für den Strom (2.58)
			* ![equation](http://latex.codecogs.com/gif.latex?i%3D%5Cfrac%7BU_0%7D%7BR%7D*e%5E%7B-%5Cfrac%7Bt-t_0%7D%7BR*C%7D%7D)
			* ![equation](http://latex.codecogs.com/gif.latex?%5Clim%5Climits_%7Bn%20%5Crightarrow%20%5Cinfty%7D%7Bi%28t%29%7D%3D0)
		* Abgegebene Leistung mit (1.7)
			* ![equation](http://latex.codecogs.com/gif.latex?p%28t%29%3Du%28t%29*i%28t%29)
			* ![equation](http://latex.codecogs.com/gif.latex?p%28t%29%3D%5Cfrac%7BU_0%5E2%7D%7BR%7D*e%5E%7B-%5Cfrac%7B2%28t-t_0%29%7D%7BRC%7D%7D)
		* Abgegebene Energie mit (1.8)
			* ![equation](http://latex.codecogs.com/gif.latex?W%3D%5Cfrac%7BU_0%5E2%7D%7BR%7D%5Cint_%7Bt%3Et_0%7D%5E%7B%5Cinfty%7De%5E%7B-%5Cfrac%7B2%28t-t0%29%7D%7BRC%7D%7Ddt)
			* (2.59)
				* ![equation](http://latex.codecogs.com/gif.latex?W%3D0.5*C*U_0%5E2)
				
# 3 - Wechselgrößen

## Einführung, Grundbegriffe

* Anwendung
	* Netz
	* elektrische Maschine
* Hergeleitete Regeln gelten auch für Wechselgrößen
	* Knotenregel (2.1.1)
	* Maschenregel (2.1.2)
	* Strom und Spannung an
		* Widerständen (1.3)
		* Induktivitäten (2.49)
		* Kapazitäten (2.54)
* Einführung von Berechnungen vereinfachender Darstellung zweckmäßig
	* Kenngrößen
	* Zeiger (3.2)
* Mittelwert Null von Wechselgrößen
	* Einführung der Kenngröße _Effektivwert_
	* Wechselspannung mit Effektivwert U bzw. Wechselstrom mit Effektivwert I setzt in Widerstand R gleiche über Periodendauer T_p=(2pi/Omega) gemittelte Leistung wie eine entsprechende Gleichspannung oder entsprechender Gleichstrom um.
		* ![equation](http://latex.codecogs.com/gif.latex?u%28t%29%3D%5C%5E%7BU%7Dsin%28%5Comega%20t%29)
		* ![equation](http://latex.codecogs.com/gif.latex?i%28t%29%3D%5Cfrac%7B%5C%5E%7BU%7D%7D%7BR%7Dsin%28%5Comega%20t%29)
		* ![equation](http://latex.codecogs.com/gif.latex?%3D%5C%5E%7BI%7Dsin%28%5Comega%20t%29)
	* Leistung (3.1)
		*  ![equation](http://latex.codecogs.com/gif.latex?p%28t%29%3D%5Cfrac%7B%5C%5E%7BU%7D%7D%7BR%7Dsin%5E2%28%5Comega%20t%29)
		* Mittelwert über T_p
			* ![eq](http://latex.codecogs.com/gif.latex?P%3D%5Cfrac%7B1%7D%7BR%7D%5Cfrac%7B1%7D%7BT_p%7D%5C%5E%7BU%7D%5E2%5Cint_%7B0%7D%5E%7BT_p%7Dsin%5E2%5Comega%20t%5C%20dt)
			* ![eq](http://latex.codecogs.com/gif.latex?P%3D%5Cfrac%7B1%7D%7BR%7D%5Cfrac%7B1%7D%7BT_p%7D%5C%5E%7BU%7D%5E2%5B%5Cfrac%7Bt%7D%7B2%7D%5Cfrac%7B1%7D%7B4%5Comega%7Dsin%282%5Comega%20t%29%5D_0%5E%7BT_p%7D)
			* (3.2)
				* ![eq](http://latex.codecogs.com/gif.latex?P%3D%5Cfrac%7B1%7D%7BR%7D%5Cfrac%7B%5C%5EU%5E2%7D%7B2%7D)
			* (3.3)
				* ![eq](http://latex.codecogs.com/gif.latex?P%3D%5Cfrac%7BU%5E2%7D%7BR%7D)
			* mit Effektivwert 
				* (3.4)
					* ![eq](http://latex.codecogs.com/gif.latex?U%3D%5Csqrt%7B%5Cfrac%7B1%7D%7BT_p%7D%5Cint_%7B0%7D%5E%7BT_p%7Du%5E2%28t%29dt%7D)
				* für u(t)=sin\^Usin(\omega t) = \^U/R (3.5)
				* (3.6)
					* ![eq](http://latex.codecogs.com/gif.latex?I%3D%5Csqrt%7B%5Cfrac%7B1%7D%7BT_p%7D%5Cint_%7B0%7D%5E%7BT_p%7Di%5E2%28t%29dt%7D)
				* für i(t)=\^Isin(\omega t)=\^I/\sqrt(2) (3.7)
	* Graphisch:
		* ![graph](https://raw.github.com/barthimaeus/AET1/master/1.png)
				
## Zeiger

### Grundlagen
* Beschreibung einer Wechselgröße mit Amplitude und Zeitfunktion
	* z.B. U(t)=\^U sin(\omega t + \phi u)
	* sinusförmige Größe fester Frequenz
		* ![eq](http://latex.codecogs.com/gif.latex?f%3D%5Cfrac%7B%5Comega%7D%7B2%5Cpi%7D%5C%3B%20%5Bf%5D%3D%5Cfrac%7B1%7D%7B%5BT_p%5D%7D%3D%5Cfrac%7B1%7D%7Bs%7D%3DHz)
		* mit Amplitude und Phasenlage vollständig beschrieben; Anwendung: z.B. Größe im Netz
		* Darstellung mit Zeiger - vergleichbar mit Vektor, vgl. (4.3.1)
* Mathematische Grundlagem
	* siehe Bronstein.
		* komplexe Schreibweise für Sinus, Cosinusfunktion (3.8), (3.9)
		* Darstellung eine komplexen Zahl in Polarkoordinaten (3.10)
		* Real- und Imaginärteil einer komplexen Zahl
		* Darstellung in der komplexen Ebene

* Idee: Darstellung von Wechselspannungen und -strömen durch komplexe Zeiger, z.B. von 
	* (3.16)
		* ![eq](http://latex.codecogs.com/gif.latex?u%3D%5C%5EUcos%28%5Comega%20t&plus;%5Cvarphi%20u%29)
	* durch (3.17)
		* ![eq](http://latex.codecogs.com/gif.latex?%5Cunderline%7BU%7D%3D%5C%5EUe%5E%7Bj%5Cvarphi%20u%7D*e%5E%7Bj%5Comega%20t%7D)
	* mit (3.18)
		* ![eq](http://latex.codecogs.com/gif.latex?u%20%3D%20Re%5C%7B%5Cunderline%7BU%7D%5C%7D)
		* ![eq](http://latex.codecogs.com/gif.latex?%3D%20%5C%5EURe%5C%7Be%5E%7Bj%5Cvarphi%20u%7D*e%5E%7Bj%5Comega%20t%7D%5C%7D)
	* Zeiger \underline{U}
		* der Länge \^U oder U (Effektivwertzeiger)
		* der Phasenlage \varphi u für t = 0
		* rotierend mit \omega t
		
### Spannungs und Stromzeiger für Widerstände, Kondensatoren, Induktivitäten

* Strom durch Widerstand R
	* mit (1.3)
		* ![eq](http://latex.codecogs.com/gif.latex?i%3D%5Cfrac%7Bu%7D%7BR%7D)
	* mit (3.19)
		* ![eq](http://latex.codecogs.com/gif.latex?i%3D%5Cfrac%7B%5C%5EU%7D%7BR%7DRe%5C%7Be%5E%7Bj%5Cvarphiu%7D*e%5E%7Bj%5Comega%20t%7D%5C%7D)
	* entsprechend (3.18)
		* ![eq](http://latex.codecogs.com/gif.latex?%3D%20Re%5C%7B%5Cunderline%7BI%7D%5C%7D)
	* (3.20)
		* ![eq](http://latex.codecogs.com/gif.latex?%5Cunderline%7BI%7D%3D%5Cfrac%7B%5C%5EU%7D%7BR%7De%5E%7Bj%5Cvarphi%20u%7De%5E%7Bj%5Comega%20t%7D)
	* mit (3.17) ergibt sich (3.21)
		* ![eq](http://latex.codecogs.com/gif.latex?%5Cunderline%7BI%7D%3D%5Cfrac%7B%5Cunderline%7BU%7D%7D%7BR%7D)
	* Zeiger \underline{I}
		* der Länge \^U/R oder U/R (^=Effektivwertzeiger)
		* der Phasenlage \varphi u für t=0 wie Spannungszeiger \underline{U}
		* rotierend mit \omega t
		
* Strom durch Kondensator C
	* mit (2.54)
		* ![eq](http://latex.codecogs.com/gif.latex?i%3DC*%5Cfrac%7Bdu%7D%7Bdt%7D)
	* mit (3.19)
		* ![eq](http://latex.codecogs.com/gif.latex?i%3DC*%5C%5EU*Re%5C%7Be%5E%7Bj%5Cvarphi%20u%7De%5E%7Bj%5Comega%20t%7D*j%5Comega%5C%7D)
	* wegen
		* ![eq](http://latex.codecogs.com/gif.latex?j%3De%5E%7Bj*%5Cfrac%7Bpi%7D%7B2%7D%7D)
	* gilt
		* ![eq](http://latex.codecogs.com/gif.latex?i%3DRe%5C%7B%5Cunderline%7BI%7D%5C%7D)
	* mit (3.17) ergibt sich (3.23), (3.24)
		* ![eq](http://latex.codecogs.com/gif.latex?%5Cunderline%7BI%7D%3Dj%5Comega%20C*%5Cunderline%7BU%7D)
		* ![eq](http://latex.codecogs.com/gif.latex?%5Cunderline%7BU%7D%3D-%5Cfrac%7Bj%7D%7B%5Comega%20C%7D*%5Cunderline%7BI%7D)
	* mit frequenzabhängiger kapazitiver Blindwiderstand
		* ![eq](http://latex.codecogs.com/gif.latex?X_c%3D-%5Cfrac%7B1%7D%7B%5Comega%20C%7D)
	* Zeiger \underline{I}
		* der Länge \omega * C * \^U oder \omega * C * U (^=Effektivwertzeiger)
		* der Phasenlage \varphi u * (\pi/2) für t = 0
		* rotierend mit \omega t
		
* Spannung an Induktivität L
	* durchflossen von Strom (3.26)
		* ![eq](http://latex.codecogs.com/gif.latex?i%3D%5C%5EIcos%28%5Comega%20t&plus;%5Cvarphi%20u%20-%20%5Cfrac%7B%5Cpi%7D%7B2%7D%29)
	* entsprechend (3.18) ergibt sich (3.27)
		* ![eq](http://latex.codecogs.com/gif.latex?i%3DRe%5C%7B%5Cunderline%7BI%7D%5C%7D)
	* ![eq](http://latex.codecogs.com/gif.latex?%5Cunderline%7BI%7D%3D%5C%5EIe%5E%7Bj%28%5Cvarphi%20u-%5Cfrac%7B%5Cpi%7D%7B2%7D%29%7D)
	* ![eq](http://latex.codecogs.com/gif.latex?u%3DL*%5Cfrac%7Bdi%7D%7Bdt%7D)
	* ...
	* ![eq](http://latex.codecogs.com/gif.latex?u%3DRe%5C%7BU%5C%7D)
	* mit (3.27) ergibt sich (3.29)
		* ![eq](http://latex.codecogs.com/gif.latex?%5Cunderline%7BU%7D%3Dj%5Comega%20L%5Cunderline%7BI%7D)
	* Zeiger \underline{U}
		* der Länge \omega L \^I oder \omega L I (^= Effektivwertzeiger)
		* der Phasenlage \varphi u für t=0
		* dem Stromzeiger \underline{I} um \pi/2 vorauseilend
		* rotierend mit \omega t
* ![graph](https://raw.github.com/barthimaeus/AET1/master/ImRe.png)	
	
* Schlußfolgerung
	* mit \omega t rotierende Zeiger für Spannung \underline{U} und Strom \underline{I}
	* an
		* Widerstand R (3.17)
		* Kapazität C (3.17)
		* Induktivität L (3.28)
	* Beziehungen zwischen Zeigern gegeben für
		* Widerstand R (3.21)
		* Kapazität C (3.24)
		* Induktivität L (3.29)
		* ohne Einfluss der Rotation \omega t
	* Berechnung stationärer Wechselgrößen möglich
		* mit ruhenden Zeigern ^=t=0
		* mit Blindwiderständen statt Differentialgleichungen
	* mit Blindwiderstand X statt Differentialgleichung
		* Kapazität C kapazitiv (3.24)
			* ![eq](http://latex.codecogs.com/gif.latex?%5Cfrac%7B-1%7D%7B%5Comega%20C%7D)
		* Induktivität L induktiv (3.24)
			* ![eq](http://latex.codecogs.com/gif.latex?%5Comega%20l)
	* vereinfachte Netzwerkberechnung

### Berechnung von Netzwerken
* Parallelschaltung von R,L,C
	* ![schaltung](https://www.dropbox.com/s/gzfheyhqxhpmq66/2012-11-20%2009.29.37.jpg)
	* Maschenregel: u liegt an R,C,L an
		* mit (3.21)
			* ![eq](http://latex.codecogs.com/gif.latex?%5Cunderline%7BI%7D%3D%5Cfrac%7BU%7D%7BR%7D)
		* mit (3.23)
			* ![eq](http://latex.codecogs.com/gif.latex?%5Cunderline%7BI_c%7D%3Dj*%5Comega*C*%5Cunderline%7BU%7D)
		* mit (3.24)
			* ![eq](http://latex.codecogs.com/gif.latex?%5Cunderline%7BI_L%7D%3D%5Cfrac%7B1%7D%7Bj*%5Comega*L%7D*%5Cunderline%7BU%7D)
		* Knotenregel (3.30)
			* ![eq](http://latex.codecogs.com/gif.latex?%5Cunderline%7BI%7D%3D%5Cunderline%7BI_R%7D&plus;%5Cunderline%7BI_C%7D&plus;%5Cunderline%7BI_L%7D%20%5C%5C%20%3D%5Cunderline%7BU%7D%28%5Cfrac%7B1%7D%7BR%7D&plus;j*%28%5Comega*C-%5Cfrac%7B1%7D%7B%5Comega*L%7D%29%29%29)
		* komplexe Impedanz (3.31), (3.32)
			* ![eq](http://latex.codecogs.com/gif.latex?%5Cunderline%7BZ%7D%3D%5Cfrac%7B%5Cunderline%7BU%7D%7D%7B%5Cunderline%7BI%7D%7D%20%5C%5C%20%3D%20%5Cfrac%7B1%7D%7B%5Cfrac%7B1%7D%7BR%7D&plus;j%28%5Comega%20C-%5Cfrac%7B1%7D%7B%5Comega%20C%7D%29%7D%20%5C%5C%20%3D%20%5Cfrac%7B%5Cfrac%7B1%7D%7BR%7D-j%28%5Comega%20C-%5Cfrac%7B1%7D%7B%5Comega%20L%7D%29%7D%7B%5Cfrac%7B1%7D%7BR%7D&plus;%28%5Comega%20C-%5Cfrac%7B1%7D%7B%5Comega%20L%7D%29%5E2%7D)
		* Wirkwiderstand (3.33)
			* ![eq](http://latex.codecogs.com/gif.latex?Re%5C%7BZ%5C%7D%3D%5Cfrac%7B1%7D%7B%5Cfrac%7B1%7D%7BR%7D&plus;R*%28%5Comega%20C-%5Cfrac%7B1%7D%7B%5Comega%20L%7D%29%5E2%7D)
		* Blindwiderstand (3.34), (3.35)
			* ![eq](http://latex.codecogs.com/gif.latex?X%3DIm%5C%7B%5Cunderline%7BZ%7D%5C%7D%5C%5C%20%3D%5Cfrac%7B%5Cfrac%7B1%7D%7B%5Comega%20C%7D-%5Comega%20C%7D%7B%5Cfrac%7B1%7D%7BR%5E2%7D&plus;%28%5Comega%20C-%5Cfrac%7B1%7D%7B%5Comega%20L%7D%29%5E2%7D)
		* Scheinwiderstand
			* ![eq](http://latex.codecogs.com/gif.latex?%7CZ%7C%20%3D%20%5Cfrac%7B%5Csqrt%7B%5Cfrac%7B1%7D%7BR%5E2%7D&plus;%28%5Comega%20C%20-%20%5Cfrac%7B1%7D%7B%5Comega%20L%7D%29%5E2%7D%7D%7B%5Cfrac%7B1%7D%7BR%5E2%7D&plus;%28%5Comega%20C-%5Cfrac%7B1%7D%7B%5Comega%20L%7D%29%5E2%7D%20%5C%5C%20%3D%5Cfrac%7B1%7D%7B%5Csqrt%7B%5Cfrac%7B1%7D%7BR%5E2%7D&plus;%28%5Comega%20C%20-%20%5Cfrac%7B1%7D%7B%5Comega%20L%7D%29%5E2%7D%7D)
		* Zeigerdarstellung
			* ![img](https://www.dropbox.com/s/3ltdd5mmsjp3brz/2012-11-20%2009.29.43.jpg)
			* Geometrische Addition der Stromzeiger nach (3.30)
* Reihenschaltung von R,C,L
	* ![schaltung](https://www.dropbox.com/s/64ux573m6gybmll/2012-11-20%2009.29.52.jpg)
	* mit
		* (3.21) ![eq](http://latex.codecogs.com/gif.latex?%5Cunderline%7BU_R%7D%3DR*%5Cunderline%7BI%7D)
		* (3.24) ![eq](http://latex.codecogs.com/gif.latex?%5Cunderline%7BU_C%7D%3D%5Cfrac%7B-j%7D%7B%5Comega%20C%7D*%5Cunderline%7BI%7D)
		* (3.29) ![eq](http://latex.codecogs.com/gif.latex?%5Cunderline%7BU_L%7D%3Dj%20%5Comega%20L*%5Cunderline%7BI%7D)
	* Maschenregel (3.37)
		* ![eq](http://latex.codecogs.com/gif.latex?%5Cunderline%7BU%7D%3D%5Cunderline%7BU_L%7D&plus;%5Cunderline%7BU_C%7D&plus;%5Cunderline%7BU_L%7D%5C%5C%20%3D%5Cunderline%7BI%7D%28R&plus;j%28%5Comega%20L%20-%5Cfrac%7B1%7D%7B%5Comega%20C%7D%29%29)
	* Komplexe Impedanz (3.38)
		* ![eq](http://latex.codecogs.com/gif.latex?%5Cunderline%7BZ%7D%3DR&plus;j%28%5Comega%20L-%5Cfrac%7B1%7D%7B%5Comega%20C%7D%29)
	* Wirkwiderstand (3.39)
		* ![eq](http://latex.codecogs.com/gif.latex?Re%5C%7BZ%5C%7D%3DR)
	* Blindwiderstand (3.40)
		* ![eq](http://latex.codecogs.com/gif.latex?X%3D%5Comega%20L-%5Cfrac%7B1%7D%7B%5Comega%20C%7D)
	* Scheinwiderstand (3.41)
		* ![eq](http://latex.codecogs.com/gif.latex?%7CZ%7C%3D%5Csqrt%7BR%5E2&plus;%28%5Comega%20C-%5Cfrac%7B1%7D%7B%5Comega%20C%7D%29%5E2%7D)
	* Zeigerdarstellung
		* ![img](https://www.dropbox.com/s/v69qf7vlzsl5om8/2012-11-20%2009.29.57.jpg)
		* Geometrische Addition der Spannungszeiger nach (3.37)
* Sonderfall: Resonanz (3.42)
	* ![eq](http://latex.codecogs.com/gif.latex?%5Comega_0%20L%3D%5Cfrac%7B1%7D%7B%5Comega_0%20C%7D%20%5C%5C%20%3D%3E%20%5Comega_0%3D%5Cfrac%7B1%7D%5Csqrt%7B%7B%5Comega%20C%7D%7D)
	* Blindwiderstand des Parallelschwingkreises (3.35) X=0
	* Serienschwingkreises (3.40) X=0
	* Kreisfrequenz \omega_0, bei der sich die Zeiger von C und L kompensieren
	* Parallelschwingkreis
		* \omega -> 0, Kein Spannungsabfall tritt auf an L
			* ![eq](http://latex.codecogs.com/gif.latex?%5Clim_%7B%5Comega%20%5Crightarrow%200%7D%7CZ%7C%3D0)
			* ![eq](http://latex.codecogs.com/gif.latex?%5Comega%20%3D%20%5Comega_0)
			* ![img](https://www.dropbox.com/s/2ejw6sgavyapmn0/2012-11-20%2009.30.21.jpg)
			* Schwingung zwischen L und C
				* ![eq](http://latex.codecogs.com/gif.latex?%5Cunderline%7BI_L%7D%3D-%5Cunderline%7BI_C%7D)
				* unabhängig von \underline{i} => \underline{Z} = R
		* \omega -> \infty, kein Spannungsabfall an C
			* ![eq](http://latex.codecogs.com/gif.latex?%5Clim_%7B%5Comega%20%5Crightarrow%20%5Cinfty%7D%20%7CZ%7C%3D0)
			* ![img](https://www.dropbox.com/s/2w6c5rjaipuv21p/2012-11-20%2009.30.18.jpg)
	* Serienschwingkreis
		* \omega -> 0: Kein Stromfluß durch C
			* ![eq](http://latex.codecogs.com/gif.latex?%5Clim_%7B%5Comega%20%5Crightarrow%200%7D%20%7CZ%7C%3D%5Cinfty)
			* ![eq](http://latex.codecogs.com/gif.latex?%5Comega%20%3D%20%5Comega_0)
			* ![img](https://www.dropbox.com/s/ervpjy08p5un1hk/2012-11-20%2009.30.30.jpg)
			* Schwingung zwischen L und C
				* ![eq](http://latex.codecogs.com/gif.latex?%5Cunderline%7BU_L%7D%3D-%5Cunderline%7BU_C%7D)
				* unabhängig von \underline{U}, \underline{Z} = R
		* \omega -> \infty: kein Stromfluß durch L
			* ![eq](http://latex.codecogs.com/gif.latex?%5Clim_%7B%5Comega%20%5Crightarrow%20%5Cinfty%7D%7CZ%7C%3D%5Cinfty)
			* ![img](https://www.dropbox.com/s/ru8wsm42br8zwk9/2012-11-20%2009.30.25.jpg)
			
## Leistung
Von Verbraucher - z.B. Schwingkreisen - aufgenommene Leistung
	* ![eq](http://latex.codecogs.com/gif.latex?u%28t%29%3D%5C%5E%7BU%7Dcos%28%5Comega%20t%20&plus;%20%5Cvarphi%20u%29%5C%5C%20i%28t%29%3D%5C%5E%7BI%7Dcos%28%5Comega%20t%20&plus;%20%5Cvarphi%20u%20-%20%5Cvarphi%29)
	* mit (1.7)
		* ![eq](http://latex.codecogs.com/gif.latex?p%28t%29%3D%5C%5EU%5C%5EIcos%28%5Comega%20t&plus;%20%5Cvarphi%20u%29cos%28%5Comega%20t%20&plus;%5Cvarphi%20u%20-%20%5Cvarphi%29%5C%5C%20%3D%5Cfrac%7B%5C%5EU%5C%5EI%7D%7B2%7D%28cos%28%5Cvarphi%29&plus;cos%282%5Comega%20t&plus;2%5Cvarphi%20u-%5Cvarphi%29%29%5C%5C%20%3DUI*%28cos%28%5Cvarphi%29*%281&plus;cos%282%5Comega%20t&plus;2%5Cvarphiu%29%29%29&plus;sin%28%5Cvarphi%29*sin%282%5Comega%20t&plus;2%5Cvarphi%20u%29)
		* ![img](https://dl-web.dropbox.com/get/Camera%20Uploads/2012-11-20%2010.32.31.jpg?w=d17bdaa4)
	
