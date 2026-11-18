# socialtap-fabric

Source snapshot: source.zip (extract to work on the project). File hashes are in source-manifest.json. AGENTS.md records the required commit-and-push workflow.

socialtap-fabric-1.21.4-1.3.0.jar and socialtap-fabric-26.2-1.3.0.jar were built from this source snapshot on 2026-11-18 with `gradlew build` (Java 25). Version 1.3.0 adds the loot guard: after you kill an enemy player and no other enemy is within 30 blocks of the body, world clicks lock for 1.5 seconds, and a friend's death always locks them for 2 seconds. It is on by default. `/socialtap lootguard true|false` turns it on or off, and `/socialtap friend add|remove|list <name>` manages the friends list, whose players are never counted as enemies.

socialtap-fabric-1.21.4-1.2.0.jar and socialtap-fabric-26.2-1.2.0.jar were built from this source snapshot on 2026-11-10 with `gradlew build` (Java 25). Version 1.2.0 adds the Social Tap activity card: Minecraft version, server address or singleplayer game mode, and time played. Older jars are preserved earlier builds. Desktop installers are in GitHub Releases. Build caches and personal runtime data are excluded.

grass-block.png is the background of the activity card. The mod links to it at its raw.githubusercontent.com address, so keep it at the repository root on the main branch.
