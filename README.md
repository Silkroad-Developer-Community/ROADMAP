# Roadmap

## RSBot

### Improvements

- [ ] [Decoupling of core logic from UI](https://github.com/Silkroad-Developer-Community/RSBot/pull/1)
- [ ] WebView wrapper
- [x] [Pathfinding](https://github.com/Silkroad-Developer-Community/RSBot/pull/4)
- [ ] Communication protocol
- [ ] Redesign of config files
- [ ] SQLite based storage
- [ ] Auto-update
- [x] [XIGN search](https://github.com/Silkroad-Developer-Community/RSBot/pull/2)
- [ ] Auto-quests

### Known Bugs

- [ ] Conflict between speed potions and skills
- [ ] Conflict between Chinese and European pain quotas
- [ ] The bot sometimes incorrectly calculates the cooldowns for the Reflect and Devil’s Spirit skills
- [ ] Storing overly specific skill IDs in the profile and scripts (breaks when leveling up)
- [ ] Attacks are not canceled correctly when the bot is stopped (the bot continues to auto-attack)
- [x] [After disconnecting and logging back into the game, the bot doesn't realize that the party has been disbanded or that some players are no longer in the group](https://github.com/Silkroad-Developer-Community/RSBot/pull/3)
- [ ] Relogin sometimes infinitely retrying after gateway connection closed (probably only rusro related, logs on 2e797e5)
- [x] [Needed to move UI timers timerGrabByAbilityPet_Tick and timerUniqueChecker_Tick to the backend (blocks moving from SDUI task)](https://github.com/Silkroad-Developer-Community/RSBot/pull/1)
