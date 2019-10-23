## Unfallatlas 2018 Berlin

### Deutsch

Diese Datensätze basieren auf dem <a href="https://unfallatlas.statistikportal.de/">Unfallatlas 2018</a> der Statistischen Ämter des Bundes und der Länder, der unter der
<a href="www.govdata.de/dl-de/by-2-0">Datenlizenz Deutschland – Namensnennung – Version 2.0</a> veröffentlicht wurde.

Der wesentliche Unterschied zwischen diesem Datensatz und dem hier vorliegenden Datensatz ist, dass die Unfälle hier den
jeweiligen Straßensegmenten des Berliner Verkehrsnetzes zugeordnet wurden. Die Straßensegmente sind dem Datensatz "Detailnetz"
des Berliner Senats entnommen: https://fbinter.stadt-berlin.de/fb/index.jsp

Der Datensatz unfaelle_berlin_2018.geo.json enthält alle Unfälle mit Angaben zu:
* Monat des Unfalls: UMONAT.
* Uhrzeit des Unfalls: USTUNDE.
* Kategorie des Unfalls: UKATEGORIE. (1 = Unfall mit Getöteten, 2 = Unfall mit Schwerverletzten, 3 = Unfall mit Leichtverletzten)
* Lichtverhältnisse beim Unfall: ULICHTVERH
* Beteiligte Verkehrsteilnehmer nach Typ: IstRad, IstPKW, IstFuss, IstKrad, IstGkfz, IstSonstig
* Zustand der Fahrbahn: STRZUSTAND
* Bezirk und Ortsteil: bezirk, oteil
* Segment ID des Straßenabschnittes: dn_id

Der Datensatz unfaelle_berlin_2018_abschnitte.geo.json enthält alle Straßensegmente mit Angaben zu:
* Segment ID des Straßenabschnittes: dn_id
* Name der Straße: str_name
* Bezirk und Ortsteil: bezirk, oteil
* Anzahl der Unfälle auf diesem Segment: n_total
* Länge des Straßensegments: laenge

Die dn_id kann dem Senatsdatensatz zugeordnet werden: z.B. dn_id=1 entspricht im original Detailnetz-Datensatz OBJECTID=s_vms_detailnetz_spatial_gesamt.1


### English

These data sets are based on the <a href="https://unfallatlas.statistikportal.de/">Accident Atlas 2018</a> of the statistical offices of the german state and the federal states, which is available under the
<a href="www.govdata.de/dl-de/by-2-0">"Data License Germany - Attribution - Version 2.0"</a>.

The main difference between this data set and the data sets is that the accidents have been allocated to the respective road segments of the Berlin transport network. The road segments are taken from the data set "Detailnetz"
from the Berlin Senate: https://fbinter.stadt-berlin.de/fb/index.jsp

The dataset unfaelle_berlin_2018.geo.json contains all accidents with information about:
* Month of the accident: UMONAT.
* Time of the accident: USTUNDE.
* Category of the accident: UKATEGORIE. (1 = Accident with fatalities, 2 = Accident with serious injuries, 3 = Accident with light injuries)
* Light conditions in the event of the accident: ULICHTVERH
* Participating road users by type: IstRad, IstPKW, IstFuss, IstKrad, IstGkfz, IstSonstig
* Road condition: STRZUSTAND
* District und 'Ortsteil': bezirk, oteil
* Segment ID of the road segment: dn_id

The dn_id can be assigned to the Senate data set: e.g. dn_id=1 corresponds to OBJECTID=s_vms_detailnetz_spatial_gesamt.1 in the "Detailnetz" data set.
