# Hinweise zu diesem Fork

Fork von [mattpocock/skills](https://github.com/mattpocock/skills), angelegt am 19.08.2026 als Sicherung fuer den Coder-Workspace.

Einzige Abweichung vom Original: In `.claude-plugin/plugin.json` ist die Liste `skills` auf `./skills/productivity/teach` gekuerzt. Alle uebrigen Skill-Ordner bleiben im Repo erhalten, werden aber nicht in Claude Code geladen. Damit bleibt der Fork eine vollstaendige Sicherung und der Dauerkontext klein.

Weitere Skills freischalten: den Pfad in `.claude-plugin/plugin.json` ergaenzen, pushen, danach `claude plugin marketplace update mattpocock`.

Abgleich mit dem Original: `gh repo sync immo24/skills-mattpocock`. Konflikte sind nur in `.claude-plugin/plugin.json` zu erwarten; dort gilt unsere gekuerzte Liste.

Nicht uebernommen wegen Namenskollision: `code-review` (gibt es in Claude Code eingebaut) und `grill-me` (eigener Skill unter `/root/.claude/skills/grill-me`).
