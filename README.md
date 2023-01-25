# Yubing_Timing.github.io

Hallo Martin,

Das ist mein neuer Code.

Wenn sich der Servomotor um 45 Grad dreht, bedeutet dies, dass der Zeiger auf das zu messende Objekt gerichtet ist.

Zu Beginn wird der Code so eingestellt, dass der Pfeil auf die Person zeigt, wenn sich die Person im Bereich von 30-50 cm(Erkennbare Entfernung: 100 cm) vor dem Sensor befindet (dieser Bereich wird als " richtige Bereich X " bezeichnet). In diesem Fall pendelt der Pfeil stark, wenn die Person näher als 30 cm vom Sensor entfernt steht, und er pendelt leicht, wenn die Person weiter als 50 cm vom Sensor entfernt steht.

Wenn die Person 3 Sekunden lang im "richtigen Bereich X" steht, beginnt sich der "richtige Bereich X" zufällig zu bewegen (innerhalb eines erkennbaren Bereichs von 100 cm), und die Person muss entscheiden, ob sie sich vor oder zurück bewegt, um den "richtigen Bereich X" zu finden, je nachdem, wie der Pfeil reagiert (wie schnell oder langsam er pendelt). Wenn sich die Person wieder im "richtigen Bereich X" befindet, geht der Kreislauf weiter.

Wenn innerhalb des gesamten Erfassungsbereichs keine Person erkannt wird, bleibt der Zeiger auf 0 Grad stehen, und der " richtige Bereich X " wird auf einen Wert zwischen 30 und 50 cm zurückgesetzt.

mit freundlichen Grüßen,
Yubing Cao
