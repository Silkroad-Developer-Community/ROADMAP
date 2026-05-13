<h1>Roadmap</h1>

<details open><summary><h2><a href="https://github.com/Silkroad-Developer-Community/RSBot">RSBot (OasisBot)</a></h2></summary>

<details open><summary><h3>Improvements</h3></summary>

- [x] [Decoupling of core logic from UI](https://github.com/Silkroad-Developer-Community/RSBot/pull/1)
- [ ] [Name change](https://github.com/Silkroad-Developer-Community/RSBot/pull/9)
- [ ] WebView wrapper
  - [ ] Tauri executable
  - [ ] Library that can speak to the UI on demand (requires a manager based on IPC to manage such requests)
  - [ ] Complete removal of SDUI
- [ ] Communication protocol
  - [ ] [Prior work](https://github.com/myildirimofficial/RSBot/pull/953)
- [ ] Redesign of config files
  - [x] [Cross-profile "General" config](https://github.com/Silkroad-Developer-Community/RSBot/pull/8)
  - [x] [Profile system fixes](https://github.com/Silkroad-Developer-Community/RSBot/pull/8)
  - [ ] Switch to JSON
- [ ] SQLite based storage
- [ ] Auto-quests

</details>

<!--  -->

<details open><summary><h3>Known Bugs</h3></summary>

- [ ] Conflict between speed potions and skills
- [ ] Conflict between Chinese and European pain quotas
- [ ] The bot sometimes incorrectly calculates the cooldowns for the Reflect and Devil’s Spirit skills
- [ ] Storing overly specific skill IDs in the profile and scripts (breaks when leveling up)
- [ ] Attacks are not canceled correctly when the bot is stopped (the bot continues to auto-attack)
- [ ] Relogin sometimes infinitely retrying after gateway connection closed (probably only rusro related, logs on 2e797e5)

</details>

<!--  -->

<details><summary><h3>Done</h3></summary>

- [x] [Auto-update](https://github.com/Silkroad-Developer-Community/RSBot/pull/8)
- [x] [Pathfinding](https://github.com/Silkroad-Developer-Community/RSBot/pull/4)
- [x] [After disconnecting and logging back into the game, the bot doesn't realize that the party has been disbanded or that some players are no longer in the group](https://github.com/Silkroad-Developer-Community/RSBot/pull/3)
- [x] [XIGN search](https://github.com/Silkroad-Developer-Community/RSBot/pull/2)
- [x] [Needed to move UI timers timerGrabByAbilityPet_Tick and timerUniqueChecker_Tick to the backend (blocks moving from SDUI task)](https://github.com/Silkroad-Developer-Community/RSBot/pull/1)

</details>

</details>

<!-- PROJ -->

<details open><summary><h2><a href="https://github.com/Silkroad-Developer-Community/Silkroad-NavLink">Silkroad-NavLink</a></h2></summary>

- [ ] [Fix for last move command](https://github.com/Silkroad-Developer-Community/RSBot/pull/10), [issue](https://github.com/Silkroad-Developer-Community/Silkroad-NavLink/issues/1)
- [ ] Plugin for contribution
- [ ] xSROMap fork that can listen to the plugin
- [ ] Load button to the `Script Recorder` to easily expand upon
- [ ] Map completion

</details>

<!-- PROJ -->

<details open><summary><h2>Other</h2></summary>

- [ ] Repo & site for community plugins

</details>