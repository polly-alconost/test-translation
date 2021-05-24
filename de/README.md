# Node.JS Chat

Dies ist eine Chat-Anwendung von node.js, die von SockJS und Express bereitgestellt wird und die Hauptfunktionen bietet, die Sie von einem Chat erwarten, z. B. Emojis, private Nachrichten, ein Administrationssystem usw.

---

## Kauf mir einen Kaffee

Egal, ob Sie dieses Projekt verwenden, etwas daraus gelernt haben oder es einfach mögen, bitte unterstützen Sie es, indem Sie mir einen Kaffee kaufen, damit ich mehr Zeit für Open-Source-Projekte wie dieses verwenden kann :)

---

## Eigenschaften

- Material Design
- Emoji-Unterstützung
- User @mentioning
- Private Nachrichten
- Löschen von Nachrichten (für Administratoren)
- Fähigkeit, Benutzer zu treten / zu sperren (für Administratoren)
- Siehe die IPs anderer Benutzer (für Administratoren)
- Weitere großartige Funktionen müssen noch implementiert werden

#### Es gibt 3 Administrationsstufen:

- **Helfer:** Kann Chat-Nachrichten löschen
- **Moderator:** Das oben Genannte sowie die Möglichkeit, Benutzer zu treten und zu sperren
- **Administrator:** Alle oben genannten Punkte sowie das Senden globaler Warnungen und das Heraufstufen / Herabstufen von Benutzern

---

## Einrichten

Klonen Sie dieses Repo auf Ihren Desktop und führen Sie `npm install` , um alle Abhängigkeiten zu installieren.

Möglicherweise möchten Sie in `config.json` , um den zu verwendenden Port zu ändern und ein SSL-Zertifikat einzurichten.

---

## Verwendung

Nachdem Sie dieses Repo auf Ihren Desktop geklont haben, wechseln Sie in das Stammverzeichnis und führen Sie `npm install` , um die Abhängigkeiten zu installieren.

Sobald die Abhängigkeiten installiert sind, können Sie `npm start` ausführen, um die Anwendung zu starten. Sie können dann unter localhost: 3000 darauf zugreifen

Um sich Administratorrechte für den Chat zu erteilen, müssen Sie in der App-Konsole `/role [your-name]`

---

## Lizenz

> Die vollständige Lizenz können Sie [hier einsehen](https://github.com/IgorAntun/node-chat/blob/master/LICENSE)

Dieses Projekt ist unter den Bedingungen der **MIT-** Lizenz lizenziert.
