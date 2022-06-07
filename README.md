# Discord Bot Template (v13)

## Todo

#### Discord
- [x] [discord.js](https://github.com/discordjs/discord.js/) implementation
- [x] [discord.ts](https://github.com/oceanroleplay/discord.ts) implementation
- [ ] Events
    - [x] `ready`
    - [x] `interactionCreate`
    - [ ] ...
- [ ] Custom events
    - [ ] `guildAdminAdd`
    - [ ] `guildAdminRemove`
- [ ] Guards implementations
    - [x] user is bot
    - [x] nsfw
    - [x] cooldown
    - [x] maintenance
    - [x] dm
    - [ ] permissions
    - [x] enabled
- [x] Guards fallback message

#### Data
- [x] SQLite database
- [ ] Other databases
- [x] ORM (w/ [mikro-orm](https://github.com/mikro-orm/mikro-orm))
- [x] EAV pattern implementation for single data types
- [x] State store system (no database)
- [ ] Users/Guilds sync with database
- [x] Built-in entities
    - [x] User
    - [x] Guild
    - [x] Stats

#### Utilities
- [x] Localization
- [ ] Stats
- [x] Logger
- [x] Cron tasks

#### Built-in commands
- [ ] General
    - [ ] `help`
    - [ ] `stats`
- [ ] Owner
    - [ ] `eval`
    - [ ] `maintenance`

#### DevOps
- [ ] Docker
- [ ] Unit tests (jest)
- [ ] CI/CD

#### Other
- [ ] JDoc
- [ ] ESlint / Prettier

#### Bonus
- [ ] Online dashboard for stats viuzalisation, monitoring, etc (using [Next.js](https://nextjs.org/) and [@discordx/koa](https://www.npmjs.com/package/@discordx/koa))
- [ ] Convert the template as an `npx` auto generated boilerplate (using [plop](https://github.com/plopjs/plop))
- [ ] CLI to generates (also using *plop*) :
    - [ ] Entities (maybe a simple wrapper of *mikro-orm* CLI)
    - [ ] Commands
    - [ ] Guards
    - [ ] Events
- [ ] Multiple database server instances connections