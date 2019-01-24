# Evented-Navigation (englisch/deutsch)

Using the number pad for navigation will raise an event sending the room information and used direction.

This will be useful if more than one function like to get information about the players movements. 
Using this code, they just have to add the event "movedirection" using the arguments event, room and direction.
Direction will contain the used direction while room is a field containing the room information included the room id.

I wrote it for some specific scripts for the game Morgengrauen. 
Hence, if you like to use it for other game, you have to change the reference to the field within gmcp.

Die Nutzung des Nummernfeldes wird damit nun ein Event ausloesen, welches die Rauminformationen und die benutze Richtung sendet.

Dies ist sinnvoll, wenn mehr als eine Funktion auf Informationen ueber die Spielerbewegung zugreifen will.
Wenn man diesen Code nutzt, dann braucht man nur das Event "movedirection" mit den Argumenten event, room und direction hinzuzufuegen.
Direction beinhaltet die benutzte Richtung, waehrend room ein Array mit den Rauminformationen, einschliesslich die Raum-ID, ist.

Ich habe dies fuer ein Paar spezielle Skripte fuer das Spiel Morgengrauen geschrieben.
Wenn du daher dies fuer ein anderes Spiel benutzen willst, dann musst du die Referenz auf das Array in gmcp anpassen.
