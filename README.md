# Roadmap

## RSBot

### Improvements

- [ ] Decoupling of core logic from UI
- [ ] WebView wrapper
- [ ] Navigation, pathfinding API
- [ ] Communication protocol
- [ ] Redesign of config files
- [ ] SQLite based storage
- [ ] Auto-update
- [ ] XIGN fetching
- [ ] Auto-quests

### Known Bugs

- [ ] Conflict between speed potions and skills
- [ ] Conflict between Chinese and European pain quotas
- [ ] The bot sometimes incorrectly calculates the cooldowns for the Reflect and Devil’s Spirit skills
- [ ] Storing overly specific skill IDs in the profile and scripts (breaks when leveling up)
- [ ] Attacks are not canceled correctly when the bot is stopped (the bot continues to auto-attack)
- [ ] After disconnecting and logging back into the game, the bot doesn't realize that the party has been disbanded or that some players are no longer in the group
- [ ] Relogin sometimes infinitely retrying after gateway connection closed (probably only rusro related, logs on 2e797e5)
- [ ] Needed to move UI timers timerGrabByAbilityPet_Tick and timerUniqueChecker_Tick to the backend (blocks moving from SDUI task)
