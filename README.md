## Erklärung zur Ordnerstruktur

- ./ beinhaltet die Systemarchitektur (MotorControl.slx), die Anforderungen (Requirements.slreqx), die Testdefinition (TestHarness.mldatx) und auch den Arduino Sketch
- artifacts beinhaltet die Subsystem References aus der Systemarchitektur; diese Modelle werden später teilweise auf den Arduino geladen
- der Arduino Sketch wird in späterer Folge auf die reale Hardware gespielt und nutzt dabei die virtuell getesteten Artefakte
- tests beinhaltet Unterordner für jede Systemkomponente, welche testbar ist bzw. Testdaten (Ein- oder Ausgangsdaten für den Test)

Die Dateinamen sind natürlich nur beispielhaft gewählt und auch andere Strukturen sind möglich