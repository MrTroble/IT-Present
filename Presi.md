# Hierarchische Datenbanken
* Datenbank mit Hierarchie
* Jedes Element hat einen Überelement (Parent)
* Jedes Element kann unter Elemente besitzen (Children)
* Wird oft als umgekehrter Baum dargestellt

## Vor und Nachteile

### Vorteile
* Es ist einfach zu verstehen, da es hierarchische structuren aus der echten Welt gut darstellen kann
* Einfacher Zugriff auf zusammenhängende strukturen, da die Struktur an sich sehr einfach ist.
* Schneller Zugriff bei bekannten Pfaden, da die Zugriffsstruktur bekannt ist.

### Nachteile
* Unflexibel, da die Struktur behalten werden muss
* Zugriff nur durch die Hierarchie möglich
* Keine bidirektionalen Beziehungen

## Beispiele
* Deutschland (Root node, Start element)
  * Bundesländer (e.g. Baden-Württemberg, Bayern, Hessen)
    * Regierungsbezirk (e.g. Freiburg)
      * Ladkreis (e.g. Konstanz)
        *  Stadt (e.g. Singen, Konstanz)