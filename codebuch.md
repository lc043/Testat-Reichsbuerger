# Datensatz zum Testat Reichsbürger #
Codebuch Stand 2022-12
erstellt von Lisa Conzelmann (lc043@hdm-stuttgart.de)

## Inhalt
- Edges.csv (Edgelist)
- Nodes.csv (Nodelist)
- Codebuch.md (Codierung der Datensätze)

## Ursprung und Datenerhebung
Ich habe den Datensatz mithilfe von OSINT-Recherche erhoben. Als Quellen dienten vor allem die TAZ und Belltower, aber auch sonstige Online-Medien.

Das Netzwerk ist ein *gerichtetes two-mode Akteursnetzwerk*. Es wurden folgende Daten erhoben:

# EDGE-Attribute

**from**
initiierender Knoten

**to**
erhaltender Knoten

**relation**
Beziehungsart zwischen den Akteuren: Bekannte, Mitglied (auch ehemalige Mitgliedschaft ist hier inkludiert), Unterstützer, Zusammenarbeit, Gründer oder Private Verbindung

# NODE-Attribute  
  
**id**  
(eindeutige Codierung des Knoten)   
codiert von 1 bis 33, jede ID entspricht einem Akteur, dh. einer realen Person oder einer Organisation

**name**
Vor- und Nachname einer Person oder Bezeichnung der Organisation

**type**
Typ des Akteurs, also reale Person oder Organisation

**sector**    
Zugehörigkeit der Person oder Organisation zu gesellschaftlichen Teilsystem

