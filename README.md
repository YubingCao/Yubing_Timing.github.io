# Yubing_Timing.github.io

Hallo Martin,

Der Code ermöglicht nun, dass der Abstandssensor die Drehung des Servomotors steuert. Ich möchte noch manche Komplexe Funktionen schaffen.

Wenn sich der Servomotor um 45 Grad dreht, bedeutet dies, dass der Zeiger auf das zu messende Objekt gerichtet ist.

Der Abstandssensor ist so eingestellt, dass er Entfernungen im Bereich von 0-300 cm erfasst, wobei die Intervalle auf 50 cm eingestellt sind (insgesamt gibt es 6 Intervalle, die mit ABCDEFG bezeichnet werden).

Das Programm wählt nach dem Zufallsprinzip ein Intervall aus (z. B. Intervall C), und wenn das Objekt weiter als Intervall C entfernt ist, dreht sich der Motor mit einer kleinen Amplitude (z. B. minus 15 Grad - 15 Grad) und mit einer langsamen Geschwindigkeit hin und her.

Wenn der gemessene Abstand näher am Intervall C liegt, dreht sich der Motor mit einer größeren Amplitude (z. B. minus 45 Grad - 45 Grad) und einer höheren Geschwindigkeit hin und her.

Wenn sich das Objekt genau in Intervall C befindet, zeigt der Zeiger auf das Objekt und ein Atemlicht blinkt im Inneren des Steins auf.

Wenn sich das Objekt länger als 5 Sekunden in der angegebenen Zone befindet, wählt das Programm eine neue Zone nach dem Zufallsprinzip aus und wiederholt die obige Anweisung.
