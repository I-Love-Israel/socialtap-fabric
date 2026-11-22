# socialtap-fabric

Source snapshot: source.zip (extract to work on the project). File hashes are in source-manifest.json. AGENTS.md records the required commit-and-push workflow.

socialtap-fabric-1.21.4-1.4.0.jar and socialtap-fabric-26.2-1.4.0.jar were built from this source snapshot on 2026-11-22 with `gradlew clean build` (Java 25). Version 1.4.0 shows who you are in a call with in a box at the top of the screen, drawn at 50% opacity, and adds `/respond <username> <message>`, which sends a message to your one-to-one Social Tap chat with that person (usernames tab-complete; quote names with spaces). Sending needs the `chat.send` scope: add it to the OAuth app in the Social Tap developer dashboard, then run `/socialtap login` again once. If the dashboard lacks a scope, login retries with fewer scopes instead of failing. Version 1.3.0 (loot guard) was withdrawn, so 1.4.0 builds on 1.2.0.

socialtap-fabric-1.21.4-1.2.0.jar and socialtap-fabric-26.2-1.2.0.jar were built from this source snapshot on 2026-11-10 with `gradlew build` (Java 25). Version 1.2.0 adds the Social Tap activity card: Minecraft version, server address or singleplayer game mode, and time played. Older jars are preserved earlier builds. Desktop installers are in GitHub Releases. Build caches and personal runtime data are excluded.

grass-block.png is the background of the activity card. The mod links to it at its raw.githubusercontent.com address, so keep it at the repository root on the main branch.
