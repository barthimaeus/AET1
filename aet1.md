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
** negativ mit Elementarladung Q=-e geladen
** e=1,602*10⁻¹⁹C [Q]=[e]=C Coulomb (1.1)
* Ionen (z.B. Flüssigkeiten, Plasma, ...)
* Analogie: Fließendes Wasser
** Maß für dessen Flussvolumen V pro Zeit t - (dv/dt) 
** vergleichbar -> Maß für Stromfluß i: Ladung Q pro Zeit t -> i=(dQ/dt) (1.2) [i] = [Q]/[t] = C/s = A Ampere

###Beispiel: Stromfluß durch Querschnittsfläche einer Leiters:

* positive Ladungsträger Q>0
	* Zählweise: Durchfluss v.l.n.r i = (dQ)/(dt) > 0
	* umgekehrte Zählweise v.r.n.l i = (dQ)/(dt) < 0
* negative Ladungsträger Q<0
	* Zählweise: Durchfluss v.r.n.l i = (dQ)/(dt) > 0
	* umgekehrte Zählweise v.l.n.r i = (dQ)/(dt) < 0

* positiver Strom wenn:
	* positive Ladungsträger sich in Richtung des Bezugspfeils bewegen (tech. Stromrichtung)
	* negative Ladungsträger sich entgegen der Richtung des Bezugspfeils bewegen (phys. Stromrichtung)

* typische Stromverläufe nach (1.2)
	* (dQ)/(dt)=I konstant: Gleichstrom
	* (dQ)/(dt)=i(t) zeitabhängig mit Mittelwert Null über eine Periodendauer Tp
(1/Tp)*Int_Tp(i(t)dt=0: Wechselstrom
		* z.B. sinusförmig mit i(t)=sin(wt)=sin(((2pi)/Tp)*t)

* Bezeichnungsweise
	* Zeitwerte mit Kleinbuchstaben "i(t)"
	* Mittelwerte - insbesondere auch Gleichgrößen - mit Großbuchstaben
	* Amplituden mit Großbuchstaben der (mit Dach) -> "I^"

## Potentiale und Spannungen

Ursache für Strömung einer Flüssigkeit im Rohr: Druckdifferenz
* p1-p1 = 0 -> Keine Strömung
* p1-p2 > 0 -> Strömung nach Rechts
* p1-p2 < 0 -> "" links
analog: elektrische Potentialdifferenz - Spannung U - führt zu Stromfluß in einem Widerstand R
* Spannung mit Bezugspfeil über Widerstand markiert
* Fälle:
	* U=0 (Potential links und rechts gleich) -> kein Strom i = 0
	* U>0 (Potential links > rechts) -> Strom i>0
	* U<0 (Potential rechts > links) -> Strom i<0
* Einheit [u] = V Volt

## Widerstand
Fluß durch ein Rohr ist begrenzt, hängt von Druckdifferenz ab -> Rohr setzt Fluß Wiederstand entgegen.
Analogie: in einem elektrischen Widerstand R ist Strom proportional zu Spannung u -> Ohmsches Gesetz:
* R=(u/i) (1.3)
* [R]=[u]/[i]=V/A='omega' Ohm 

Widerstand R eines Leiters nimmt
* mit steigender Länge l zu
* " " Querschnittsfläche ab
* R='rho'*l/A ('rho' ist spezifischer Wiederstand)
	* 'rho' = ([R][A])/[l] = ('omega'*m²)/m = 'omega'm
	* temperaturabhängig mit Temperaturkoeffizienten 'alpha'
		* 'alpha' für lineare Näherung:
			* 'rho'(t)='rho'(T0)*(1+'alpha(T-T0))
		* 'alpha' und 'beta' für quadratische Näherung
			* 'rho'(t)='rho(T0)(1+'alpha'(T-T0)+'beta'(T-T0)²)
	mit Temperatur T, für die 'rho' angegeben werden soll, und Bezugstemperatur T0,
	für die 'alpha' und 'beta' angegeben werden.
	* [T0][T0]=K Kelvin ['alpha']=K⁻¹ ['beta']=K⁻² wobei für Konstantan 'alpha'=0
	* Kehrwert: Leitwert G=1/R (1.5)
		* [G] = 1/[R] = 1/'omega' = S Siemens
		für einen Leiter entsprechend (1.4) G = K*(A/l) (1.6)
		mit spezifischem Leitwert K als temperaturabhängiger Materialkonstante
		[K] = 1/['rho'] = 1/['omega'*m] = S/m
		Folgende Betrachtung zunächst am Beispiel elektrischer Widerstände; weitere Bauelemente mit anderem Verhalten, z.B.
			* Induktivitäten 2.3.1
			* Kapazitäten 2.3.2
			* Halbleiter AET2
