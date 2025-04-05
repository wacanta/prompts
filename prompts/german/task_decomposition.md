# Aufgabenstellung
Ziel ist es, eine  umfangreiche, komplexe Aufgabe zu bewältigen, indem du die Aufgabe in kleinere, überschaubare Teilaufgaben zerlegst und jeder Teilaufgabe geeignete Rollen zuweist, die von einem KI-Modell eingenommen werden kann, um die Teilaufgabe bestmöglichst zu lösen. 

# Kontext
Wenn Menschen mit einer großen, komplexen Aufgabe konfrontiert werden, an der mehrere Personen beteiligt sind, wenden sie einen systematischen Ansatz an, um die Aufgabe in leichter zu bewältigende Teilaufgaben zu zerlegen. Während des Zerlegungsprozesses definieren Menschen iterativ die Methodik für jede Teilaufgabe, die konkrete Anweisungen oder Algorithmen speziell für diese Teilaufgabe enthält. Jeder Schritt oder jede Anweisung innerhalb der Methodik sollte atomar, eindeutig und durchführbar sein, d. h. ohne weitere Zerlegung ausgeführt werden können. Auf der Grundlage der definierten Methodik wird der Umfang und die Komplexität jeder Teilaufgabe bewertet und gegebenenfalls in kleinere Schritte unterteilt. Dieser Prozess ist rekursiv, bis alle Teilaufgaben, Inputs, Outputs, Randbedingungen und Methoden vollständig definiert sind. Sobald die vollständige Struktur der Teilaufgaben festgelegt ist, weisen die Personen jeder Teilaufgabe auf der Grundlage des erforderlichen Fachwissens geeignete Rollen zu, bevor das vollständige Ergebnis der Teilaufgaben präsentiert wird. Sie setzen die Ausführung der Aufgabe fort, indem sie die zugewiesenen Rollen übernehmen und jede Teilaufgabe aktiv ausführen, wobei sie der entwickelten Methodik folgen und die Ergebnisse der vorhergehenden Schritte als Input für die nachfolgenden Aufgaben verwenden.

# Schrittweise Vorgehensweise. 
Analysiere die Aufgabe und zerlege sie in einzelne Schritte. Jeder Einzelschritt muss so strukturiert sein, dass ein KI-Modell, das nur mit einem Einzelschritt beauftragt wird, eindeutig erkennt, was in diesem Teilschritt verlangt wird. 

# STRUKTURIERTE AUSGABE
* Teilschritt [Name des Teilschritts]
* Beschreibung [Kurze und präzise Beschreibung, was in diesem Teilschritt getan werden soll]
* Ziel [Das spezifische Ergebnis, das durch diesen Schritt erreicht werden soll]
* Anleitung [Schrittweise, atomare Anweisungen zur Durchführung dieses Teilschritts]
* Inputs [Was wird benötigt, um den Schritt auszuführen?]
* Outputs [Was soll am Ende des Schritts herauskommen?]
* Randbedingungen [Einschränkungen oder Annahmen für diesen Schritt]
* Zugewiesene Rolle [Die Rolle, die diesen Schritt übernehmen soll, inkl. relevanter Eigenschaften oder Fähigkeiten]

# KOMPLEXE, ZU ZERLEGENDE AUFGABE
{{Aufgabe}}
