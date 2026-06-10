# Bewegingen



##### Les 1

prijs kWh -> stroomvoorspeller.be

mondeling examen (10% herexamen) -> 2 delen, enkel gefaald deel opnieuw doen in augustus

GEEN TELEFOONS

"AA IE gaat je niet helpen"

rare shit met zelf mechanisme aanpassen

vraag: aanpassing aan code -> voorspel (bv. 5 kopies aandrijven=>uit fase, betere verspreiding) -> naar kritieke stangen kijken

"tradeoffs zijn belangrijk voor uw tradeoffs"

"correct antwoord, maar niet juist"

"We nummer de links... met nummertjes"

driehoekig mechanisme -> toepassing naar examen meebrengen



##### Les 2

###### Examenvragen:

* mechanisme vs. mechatronisch
* hoe is de transmissiehoek op het meest kritische moment?
* Welke configuraties? Zijn er slechten? Hoe vermijd je ze?
* animaties met extra snelheden/krachten/versnellingen: als goede reden ervoor

"Oefeningen" \~ vrageuurtjes -> vragen stellen over Notebooks die we al hebben

systematische methode: werkt altijd, niet altijd efficiënt <-> 'ad hoc' \~ inzicht



##### Les 3

###### Examenvragen:

* lineaire/kwadratische/... afhankelijkheid van sommige parameters
* welke grootteorde is 10 kN -> 1 ton opheffen
* Steiner -> inertie in ander assenstelsel
* oppassen voor tekens (+-)!
* hoe instrumenteer je de schaafmachine om te testen of ze goed werkt?
* plots met meetnauwkeuriger -> niet nodig, maar wel als je er iets interessant over kan zeggen

kinetische energie met

\-> encoder: positie -> afleiden ->  meetfouten

\-> accelerometer: integreren beter geconditioneerd dan afleiden ->MAAR drift

meetinstrumentent: encoder, acceleromenter, rekstrookje, newtonmeter, laser...

TLDR: wet van Newton inbrengen via



##### Les 4

###### Examenvragen:

* Wat als ik een stang doorsnij? -> inzicht, geen berekening (gewricht?)
* Vraag over vliegwielen -> tradeoffs +stabilisatie -kostprijs, gewicht groottes



##### Les 5

###### Examenvragen:

* plots met krachten in de notebooks
* welke krachten zijn de onbalanskracchten?
* Stel ik verdubbel de massa -> wat verandert?
* zware stangen, maar kleinen krachten -> hoezo? (zwaartekracht \& wrijving verwaarloosd)
* notebook: tabel van alle curves met relatieve eigenschappen
* waarom wel/niet zachte functie?



Bewegingswetten: beweging -> mechanismes --> nokken \~ heffingswetten

oneindig zachte functie: consinus



##### Les 6

###### Examenvragen:

* Wat als je 2x sneller gaat -> bepaalde kosten niet-lineair omhoog
* sluitingsmechanismes nokken, bv. veer/zwaartekracht, groef, 2 volgers...
* VERMOGENSANALYSE -> wrijving !



centriciteit nok, drukhoek (hoe groter, hoe slechter),



krachten: specificatie of beperking?

drukhoek alfa < 30°/35°

excentrische volger -> drukhoek veranderen (wat je wint, verlies je ook -> vaak minder belangrijk deel beweging)

formule nok: 'is wat ze is' -> niet moeten uitleggen

kromtestraal volger <-> lokale kromtestraal => ondersnijding bij  ...

tradeoff: veer voorspannen -> waar kracht nodig?, praktische aspecten -> constanten, dus k niet te precies nodig

niet teveel tijd in optimisatie steken (+ veel onbekende parameters) -> 3 BC







##### Vragen

* Gaan de vier vragen uit de lijst enkel over het stangenmechanisme, of ook over de nokken?
* Er is een vraag over een vliegwiel. Heeft iederen groep een vliegwiel? -> ja



* heffingswet: strict lineaire beweging, of beweging op het einde volbracht?
* verdeling van het werk ok?
* toepassing nok?
* demping?





Op het mondelinge examen kiezen we vier van de onderstaande hoofdvragen, elk goed voor een deelscore van 2.5/10. Deze vragen zijn heel algemeen, en dus relevant voor heel veel onderdelen van jullie project.







1\. waarvoor gebruikt de industrie het mechanisme of de nok? Hoe zou je het ontwerp aanpassen (geometrische parameers, positie van de motor, verandering van de timing in één cyclus,...) voor een andere toepassing? 

nok: kurken van portoflessen (geen andere toepassing gevonden).

mechanisme: hoogwerker, chirurgische lamp (veer ipv zuiger, wrijving verhogen).



2\. hoe optimiseer je het ontwerp voor precisie? voor energieverbruik? voor krachtgeneratie?

nok: precisie -> geen loshechting, hogeregraadspolynoom. energieverbruik -> zo min mogelijk veerkracht, lage drukhoek. krachtengeneratie -> zo min mogelijk veerkracht.



mechanisme: precisie \& krachten -> zuiger verplaatsen. energie -> zo efficient mogelijke gewrichten?

3\. vliegwiel: welke afwegingen ("trade offs") heb je gemaakt, en waarom?

vliegwiel heeft zin (piek-koppel >> gemiddeld koppel)

schijfvliegwiel ipv velg (massa geen probleem, goedkoper)

R = 300 mm (vrij arbitrair)

4\. keuze van bewegings-traject: welke afwegingen ("trade offs") heb je gemaakt, en waarom?

nok: 5de graadspolynoom -> laagste versnelling voor eindige jerk (fundamentele wet van nokkenontwerp) + lagere productiekosten dat eindige Djerk





6\. heeft je ontwerp dode punten ("singulariteiten")? Is dat erg?







7\. wat zijn de onbalans-eigenschappen van je onwerp? Vormen die een probleem?

(nok: < 1 N)





8\. wat zijn de relatieve invloeden van inertie, wrijving en stijfheid op je toepassing?

nok: inertie \& (veer)stijfheid -> zie krachtengrafiek

\\//



9\. hoe verandert je ontwerp als je verschillende kopies van je mechanisme in parallel laat aandrijven door dezelfde motor.

nok: reeds 2x in fase -> 2x met 180° verschil kan zin hebben om koppel te balanceren, maar wordt mechanisch complexer.

\\//

10\. verander een parameter in je ontwerp, voorspel wat het effect zal zijn, en bereken de bijhorende numerieke analyse. 

nok: m, n, k ...





We stellen  altijd de volgende bijvraag: hoeveel kost de motor voor je machine, en hoeveel kost het energieverbruik?

Motor kost €327, energieverbruik \~ € 40 over 5 jaar nonstop.

