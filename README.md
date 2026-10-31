# heal.sk - Simples Heilsystem für Minecraft-Server.

Dieses Skript fügt den Befehl `/heal <player>` hinzu. Damit kann ein Spieler sich selbst oder einen anderen online befindlichen Spieler vollständig heilen. Die Berechtigung wird abhängig davon geprüft, ob das Ziel der Aufrufer selbst oder ein anderer Spieler ist.<br><br>

Alle Nachrichten sowie die Berechtigungen sind frei anpassbar.<br>

## Berechtigungen

| Berechtigung | Zweck |
| --- | --- |
| `volpe.skript.heal.self` | Erlaubt `/heal <player>` mit dem eigenen Spielernamen als Ziel. |
| `volpe.skript.heal.others` | Erlaubt `/heal <player>` mit einem anderen Spieler als Ziel. |<br><br>

## Installation

1. Lege `heal.sk` in `plugins/Skript/scripts/` ab.
2. Lade das Skript im Spiel oder in der Konsole mit `/sk reload heal`.
3. Weise die gewünschten Berechtigungen mit deinem Permissions-Plugin zu.<br>

## Dependencies

- [PaperMC](https://papermc.io/downloads/paper/) – [Dokumentation](https://docs.papermc.io/paper/)
- [Skript](https://github.com/SkriptLang/Skript) – [Dokumentation](https://docs.skriptlang.org/)
- [LuckPerms](https://luckperms.net/)* - [Dokumentation](https://luckperms.net/wiki/Home)

*Alternativ sind wahrscheinlich auch andere Permission-Plugins wie [PermissionsEx](https://www.spigotmc.org/resources/permissionsex.108323/) möglich.<br>
Diese wurden allerdings nicht auf vollständige Funktionalität getestet, weshalb [LuckPerms](https://luckperms.net/) als moderne Standardlösung empfohlen wird.<br>

## Weitere Skripts

Auf meinem GitHub-Profil findest du weitere, kostenfreie .sk-Dateien, die du einfach personalisieren und deinem Server hinzufügen kannst.<br>
Ich versuche mit diesen Skripts neue Server-Admins zu unterstützen.<br>
Wenn dir meine Arbeit und die Projekte gefallen, würde ich mich über einen Stern auf GitHub freuen.
