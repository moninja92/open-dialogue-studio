# Open Dialogue Studio

A standalone Windows app for writing branching game dialogue: no game engine, no code.

Build conversations as node graphs: lines, player choices, skill checks with dice,
conditions and variables, item and quest gates. Play them in a live preview as you go,
then export plain JSON that your game reads. A free runtime addon plays it in Godot 4.8;
the format is engine-neutral, so other engines can follow.

## What you can do
- **Write in a graph:** cards for lines and responses, drag to connect, Validate to catch
  dead ends and broken references.
- **Branch on anything:** variables, dice checks with critical outcomes, items, quests,
  and your own databases (factions, characters, whatever your game needs).
- **Reuse patterns:** schematics turn a common beat (a bribe, a locked door) into one card.
- **Fill text at runtime:** `{player.name}`, pronouns and database values in any line.
- **Preview before export:** play the conversation, pick any choice, force a dice roll.
- **Export cleanly:** one folder of JSON plus the databases it uses, ready to drop into a game.

## Download
Get the latest `OpenDialogueStudio.exe` from [Releases](../../releases). It runs on its own,
with nothing to install. Windows may warn that the app is unrecognized: choose
**More info → Run anyway**.

To play exported dialogue in a game, copy `addons/open_dialogue` from the release zip into
your Godot 4.8 project.

## License
MIT. Forked from bitemdev/DesignerFriendlyDialogueTool; the spell-check word list is from SCOWL.
See LICENSE and THIRD-PARTY-NOTICES.md.
