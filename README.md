# Dokumentation:
Container starten build läuft.

1. Wie können mehrere Container miteinander genutzt werden?
Mehrere Container können miteinander genutzt werden, indem sie über eine Netzwerkverbindung miteinander kommunizieren. Eine Möglichkeit, um dies zu erreichen, ist die Verwendung von Docker Compose. Docker Compose ist ein Tool, mit dem Entwickler mehrere Docker-Container definieren, konfigurieren und ausführen können. Dabei können die Container miteinander kommunizieren und Dienste über Ports bereitstellen.

2. Welche Vorteile bietet diese modulare Auftrennung?
Die modulare Aufteilung von Anwendungen in mehrere Container bietet einige Vorteile, wie z.B. eine einfachere Skalierbarkeit, eine bessere Isolation von Komponenten, eine einfachere Aktualisierung und Wartung von Container-Images, eine verbesserte Flexibilität und eine höhere Ausfallsicherheit.

3. Wie ist ein docker-compose.yml aufgebaut?
Ein docker-compose.yml-File ist eine YAML-Datei, die die Konfiguration von Docker-Containern beschreibt. In der Regel besteht es aus den folgenden Abschnitten:
Version: Die verwendete Version von Docker Compose
Services: Eine Liste der definierten Docker-Container und ihrer Konfigurationen
Networks: Eine Liste von Netzwerken, die von den Containern genutzt werden
Volumes: Eine Liste von Volumes, die von den Containern genutzt werden

4. Welche Punkte müssen bei Docker Compose und CI/CD Pipelines beachtet werden?
Bei der Verwendung von Docker Compose und CI/CD-Pipelines gibt es einige wichtige Punkte zu beachten, wie z.B.:
Sicherheit: Container müssen sicher konfiguriert werden, um Angriffe zu vermeiden.
Versionskontrolle: Docker Compose-Dateien sollten in der Versionskontrolle gespeichert werden, damit sie bei Bedarf wiederhergestellt werden können.
Umgebungskonfiguration: Die Umgebungskonfiguration muss konsistent gehalten werden, um Probleme bei der Ausführung der Pipeline zu vermeiden.
Registrierung von Container-Images: Die Container-Images sollten in einem Container-Registry gespeichert werden, damit sie von der CI/CD-Pipeline verwendet werden können.
