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
Fluß durch ein Rohr ist begrenzt, hängt von Druckdifferenz ab -> Rohr setzt Fluß Wiederstand entgegen.
Analogie: in einem elektrischen Widerstand R ist Strom proportional zu Spannung  u
* (1.3) Ohmsches Gesetz:
	* ![equation](http://latex.codecogs.com/gif.latex?R%3D%28u/i%29)
	* Einheit
		* ![equation](http://latex.codecogs.com/gif.latex?%5BR%5D%3D%5Bu%5D/%5Bi%5D%3DV/A%3D%5COmega%5C%3BOhm)

Widerstand R eines Leiters nimmt
* mit steigender Länge l zu
* mit steigender Querschnittsfläche ab
* Spezifischer Wiederstand
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
