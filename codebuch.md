# Datensatz zum Testat Reichsbürger #
Codebuch Stand 2022-12
erstellt von Lisa Conzelmann (lc043@hdm-stuttgart.de)

## Inhalt
- Edges.csv (Edgelist)
- Nodes.csv (Nodelist)
- Codebuch.md (Codierung der Datensätze)

## Ursprung und Datenerhebung
Ich habe den Datensatz unter den Studierenden des dritten Semesters im Kurs Netzwerkanalyse erhoben. Die Daten sind nach der Erhebung nach einem Zufallsprinzip anonymisiert worden.

Das Netzwerk ist ein *gerichtetes two-mode Akteursnetzwerk*. Es wurden zwei getrennte Fragen erhoben:

# EDGE-Attribute

**id**  
(eindeutige Codierung des Knoten)   
codiert von 1 bis xx, jede ID entspricht einem Akteur, dh. einer realen Person oder einer Organisation

**from**
initiierender Knoten

**to**
erhaltender Knoten

**relation**
Beziehungsart zwischen den Akteuren
1 = *work* Projektbasierte Beziehung: Bei einem gerichteten Netzwerk präferiert der Sender (erste Spalte) die Zusammenarbeit mit der genannten Zielperson (zweite Spalte).  
2 = *help* Unterstützungsbeziehung: Bei einem gerichteten Netzwerk fragt der Sender (erste Spalte) die genannte Person (zweite Spalte) um Rat.  
3 = *love* Liebesbeziehung zwischen Akteuren, codiert nach dem Attribut *complicated*

# NODE-Attribute  
  
**id**  
Identische ID wie aus der edgelist zur Identifikation der Knoten von 1 bis xx.

**name**
Vor- und Nachname einer Person oder Bezeichnung der Organisation

**type**
Typ des Akteurs, also reale Person oder Organisation

**sector**    
Zugehörigkeit der Person oder Organisation zu gesellschaftlichen Teilsystem

