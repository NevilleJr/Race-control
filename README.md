# Under Investigation

Du bist Rennleiter: Flaggen setzen, Vorfälle untersuchen, Strafen verteilen. Mit Karriere, Online-Lobbys, eigenen Strecken und 24-Stunden-Rennen.

**Jetzt spielen:** https://nevillejr.github.io/under-investigation/

## Mehrspieler
Online → Lobby eröffnen oder einer offenen Lobby beitreten. Der PC des Hosts berechnet das Rennen. Die Verbindung läuft wenn möglich direkt zwischen den Spielern (PeerJS/WebRTC), sonst automatisch über einen öffentlichen WebSocket-Relay (MQTT).

Zum Testen des Relay-Wegs: `?relay=1` an die Adresse hängen.