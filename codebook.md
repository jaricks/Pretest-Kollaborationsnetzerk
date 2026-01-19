# Codebuch

## Edgelist (Edge-Attribute)

### from
Songs (Sender einer Beziehung:  Entspricht ID in der Nodelist. Keine Sonderzeichen, nur ein Wort)

### to
Akteure (Empfänger: Entspricht ID in der Nodelist. Keine Sonderzeichen, etc.)

### year

welches Chartjahr (definiert einen Zeitraum, in dem die Beziehung zwischen zwei Knoten stattgefunden hat)

### edge_role

NUR BEI type=2 (sonst NA); definiert die Art des Akteurs


## Nodelist (Node-Attribute)

### id

eindeutige Identifikation jedes einzelnen Knotens (vertex), der erfasst wird; damit wird dann in R gearbeitet

### name

Name oder Bezeichnung des Knotens, der dann im netzwerk auch angezeigt wird (also vollständig)

### sex

Geschlecht; bei Label und Songs NA

### type

Unterscheidung zwischen Songs und Akteuren; Akteure sind Künstler, Writer, Produzenten, Label (alles außer Songs)

### genre

NUR BEI type=1 (sonst NA); genaue Schreibweise beachten! und erweitern, wenn entsprechende Songs vorkommen.

### chart_rank

NUR BEI type=1 (sonst NA); die Chart-Platzierung als Zahl

### de_rank

Platz in unserem Ranking, also welchen Platz von den deutschsprachigen Songs in den deutschen Charts

### fans

definiert als Anzahl der monatlichen Hörer auf Spotify des Akteurs (gemessen auf Spotify im Februar 2026; nur bei Künstlern)

### country

Herkunftsland der Akteure

### succes

Erfolgsindikator (nur bei Songs)

### node_role

Typ des Knotens

### birth_year

Geburtsjahr des Akteurs/ Gründung der Labels
