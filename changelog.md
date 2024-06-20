# Changelog Hausarbeit EEE 


## 2024-06-20 Jan
- Verteilleitung geändert von Standardwert (Begründung: Standardwert >154m ist vollkommen unrealistisch) auf 20 m
- EIngabe von Preisen für Wirtschaftlichkeit
- Exkurs in Kostenfunktionen Excel: 
    - Daten Übernommen: Heizlast, Wohnfläche, WE, Wärmeerzeuger
    - Baupreisindex & Ortsfaktor bestimmt
    - Baunebenkosten gem. pauschale integriert
## 2024-06-15 Jan
- Fenster auf Wert aus Aufgabenstellung korrigiert
- Anpassungen in Heizung, Standardkessel, Vorlauftemperatur, Fläche Solarkollektor, Brenner, Speicherbaujahr, u.a.
- Start Varianten:
    

## 2024-06-13 Jan
- Bauteile Fenster, Fortsetzung mit U Wert 2,1
    - Im EG Plan sind die WZ-Fenster nicht korrekt eingezeichnet, auf Fotor ist erkennbar, dass nicht bodentief - augenscheinlich aber größer als restl. EG Fenster. Aus den bekannten Maßen kann man ca. 1,5m abschätzen
    - Situation im Kinderzimmer nicht klar aus Plan erkennbar, lt. ergänzten Maßen  sind zwei bodentiefe Bauteile vorhanden, lt. Beschreibung mind. 1 Tür --> Annahme:  1x Tür 1x bodentiefes Fenster
- Himmelsrichtungen in den Wänden ergänzt
- Kellerdecke als Bauteil angelegt
- Giebelwände als Bauteil angelegt. (Luftschicht im Gefach als zusätzliche Schicht mit Gefachung umgesetzt)
    - Fenster in Giebelwänden zugefügt
- Dachseiten als Bauteil angelegt
    - Dachneigung (38°) & Giebellänge (6,56m) über Trigonometrie bestimmt
    - Dachbauteil vernachlässigt alle Schichten oberhalb der belüfteten. Ggf. hier ein vermutl. vernachlässigbarer Fehler weil Sparren theoretisch in belüftete Ebene reinragen, aber vernachlässigbar
- Innenwände Richtung Keller als Bauteile angelegt.
    - Kein Aufbau verfügbar, wird daher aus Außenbauschichten approximiert. Naheliegenderweise auch Ständerbauweise in übl. Bauholzmaßen mit Plattenbeschichtung identisch zu den Innenseiten der Außenwände. Kleinere Ungereimtheiten bzgl. Dicke ggü. des Grundrisses werden im Sinne des Realismus akzeptiert
- Treppe Richtung DG als Vollholztreppe mit 40mm  Stärke + Gipsbeplankung angenommen. Erscheint für Bauweise plausibel. 
- ??????Heizbedarf Wizard mal ausprobiert. Ergebnis für Bedarf ergibt sich jetzt, ist aber viel zu schlecht ???????

# 2024-06-12 Jan

- Festlegung Fragestellung thermische Hüllfläche im Kellertreppenbereich. 
    - Möglichkeit 1: Dämmen der an TRH anliegenden Wände im Erdgeschuss und der Treppe zum OG von unten, Einbau einer Wärmeschutztür im EG
    - Möglichkeit 2: Dämmen der an TRH anliegenden Wände im im Keller, Einbau einer zusätzlichen Wärmeschutztür am Fuß der Treppe, Dämmen der Treppe soweit wie möglich im Keller, Dämmen Kellerboden innerhalb der thermischen Hüllfläche, sowie die Außenwand des TRH von innen.
    - Wahl von Möglichkeit 2 - Begründung: Maßnahme erfordert keine bauliche Änderung im Wohnbereich, daher keine Belastung der Bewohner während der Bauzeit. Zwar sollten die Wände des TRH im EG ebenfalls Ständerbauweise sein, bei einer Stärke von nur 92mm und der Annahme, dass der Aufbau der abgebildeten Außenwände ähnelt, dann ist die Gefachtiefe 50mm oder weniger und eine zusätzliche Innenwanddämmung wird notwendig, um auf die erforderlichen U-Werte zu kommen. 
        - Entscheidung beeinflusst die thermische Hüllflache und dementsprechend das Volumen. Angenähert kommen zusätzlich 2.47x(0,75+2x0,24)x3,52/2 (m³) = 5.35m³ dazu. Zusätzliche Eingabe im Gebäudevolumen
        
    -Bautechnik
        - Belüftung: über Durchlässe und Fenster, Fall III
        - unterer Gebäudeabschluss: Weil Keller nicht beheizt und aufgrund Festlegung im TRH "angrenzend an unbeheizten Keller ohne Perimeterdämmung
        - Bodenfläche ist Bruttofläche (10,28x10,52) (m²) - (0,75+2x0,24)x(3,52+0,365)(m²) = 103,67m², ist scheinbar nicht relevant daher nur Eingabe Bodenfläche (Vermutlich weil Fläche über die entsprechende Bauteilfläche später eingegeben werden)
        - Umfang Bodenfläche ist der Rohbauumfang 2x10,28+2x10,52 (Kellertür übermessen weil ohnehin unbeheizt)
        - Gebäudeautomation: keine Änderung an den Eingaben
    - Bauteile:
        - Südwand EG Kinderzimmer & Rest zugefügt. Konstruktion für Wand EG angelegt und in DB gespeichert. FÜr Konstruktion die Bauteilwerte für Faserzementplatte recherchiert.
        - restlichen Wände EG ergänzt aus Katalogteil. Offener Punkt ist der einzelne Balken zwischen den Doppelfenstern, hier weicht die Konstruktion vermutlich ab.
        - Haustür zugefügt, Fenster Nordwand zugefügt. Problem: Lt Prospektauszug dins die Fenster dreifach verglast, in Helena gibt es nur die Option zur Zweifachverglasung aus der Bauzeit. Internetrecherche hat auch keine ausreichenden Infos zur "korrekten" Berechnung mit psi, Ug & Uf Werten ergeben. 
            - Frage: Lt Prospekt "alle" Bauteile 40% besser als Wärmeschutzverordnung, das wären dann 3,5W/m²K x 0,6 also ca. 2,1 W/m²K (erscheint mir zu gut für das Baujahr...). Diesen Wert verwenden

## 2024-06-10 Jan

- neues Projekt gestartet
- Angaben zum Projekt gefüllt
    - Projektdaten eingegeben
    - Gebäudedaten eingegeben
    - Auftraggeber & Aussteller ausgefüllt
    - Bilder fehlen noch
- Berechnungsverfahren
    - Verbrauch & Bedarf aktiviert
    - Art des GEG Nachweises auf Neubau gestellt
    - zusätzliche Berechnung für BEG Effizienzhaus anwählen, Verrechnung Nachtstrom deaktivieren
- Bei zusätzliche Berechnung Ökonomie, sommerl. Wärmeschutz, Nutzung erneuerbarer Energien für Heizung & Gebäudeheizlast nach DIN 12831 an
- Haken bei Angabe iSFP, Energieausweis & Bauteilanforderungen für Einzelmaßnahmen an
- Bei Angaben zur BEG Gebäudekategorie, WE und Wohnfläche eingetragen
    - Annahme: Auftraggeber ist Eigentümer, weil Beschreibung das nahelegt, daher dito für Art der Antragstellung
- Erfassung Energieverbrauch:
    - allg. Daten: Nutzfläche füllt sich durch spätere Eingaben des Bruttovolumens unter Bautechnik
    - Auswahl zusammenhängender Zeitraum >36 Monate, weil für 2023 ist Bedingung jüngster Abrechnungszeitraum erfüllt
    - Annahme: aus Beschreibung 1.1 ist impliziert, dass kein Leerstand bestand.
    - Energieträger Heizöl, Berücksichtigung WW pauschal & mittels Anlage zur solaren WW-Erzeugung
    - Anfang & Enddatum für die Berücksichtung im Ausweis eingetragen
- Bautechnik:
    Gebäudedaten, Angaben: Bruttovolumen geheizte Fläche (EG + DG -> 10,328x10,568x(2,53+0,18) + 10,568x10,328x(4,07+0,21)/2 (m³)), so noch nicht richtig weil Treppenhaus noch nicht klar definiert innerhalb der therm. Hüllfläche
    Randbedingungen: Ständerbauweise daher Bauweise leicht, Wärmebrückenkorrektur 0,10W/m²K, nur zentral beheizt, keine Lüftungsanlage, unteren Gebäudeabschluss mit Korrekturfaktor weil unbeheizter Keller, Warmwasserbedarf vorhanden