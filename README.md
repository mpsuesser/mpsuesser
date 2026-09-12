## Actively maintained

[opencode-effect-enforcer](https://github.com/mpsuesser/opencode-effect-enforcer): Dozens of Effect skills, an agent-write-time pattern matcher/catcher with dozens of Effect-first AST-detected patterns with detailed remediation guidance, small handful of guidance docs injected near the top of the context window to set the Effect frame of mind, and programmatic guarantees that this stuff carries across the compaction threshold. Greatly increases my confidence that the code is correct and keeps agents decisively in the Effect latent space rather than treating it as an afterthought. Common advice from the Effect team and frequent users is that it is optimal to give your agent a direct reference to the Effect repo source code with minimal extra guidance or maybe just a single `effect` skill, but I think they are wrong about that.

[opencode-imagen](https://github.com/mpsuesser/opencode-imagen): So that I can say "use imagen to make a sick backsplash for this page that fits the aesthetic based on what you see in @docs/vibes/" and it actually happens. Uses `gpt-image-2` and tokens are billed not separately but through the hooked-up monthly Codex subscription

[starred](https://github.com/mpsuesser/starred): A categorized and easier-to-skim list of every repo I have starred on GitHub

[workspace](https://github.com/mpsuesser/workspace): Mostly dotconfigs, little bit of binding code for terminal apps

[images](https://github.com/mpsuesser/images): 350+ images saved for vibe transmogrification purposes

[scrape-docs](https://github.com/mpsuesser/scrape-docs): OpenCode v2 has a feature where you can add a reference to a public GitHub repo and OpenCode then maintains a clone of it locally so I can `@reference` it in any chat and the agent is able to navigate it with bash/filesystem tools. So this repo is a scraper that scrapes the following documentation sites every 5 minutes and maintains a separate repo for each of them, effectively ensuring I am always able to e.g. `@foldkit-docs` in an OpenCode session and trust that I am pointing the agent to the most up-to-date version of that documentation as a locally-cached collection of markdown files: [Alchemy](https://github.com/mpsuesser/scraped-docs-alchemy), [Better Auth](https://github.com/mpsuesser/scraped-docs-better-auth), [Drizzle](https://github.com/mpsuesser/scraped-docs-drizzle), [Electron](https://github.com/mpsuesser/scraped-docs-electron), [Ent (Go)](https://github.com/mpsuesser/scraped-docs-ent-go), [Ent (TypeScript)](https://github.com/mpsuesser/scraped-docs-ent-ts), [Foldkit](https://github.com/mpsuesser/scraped-docs-foldkit), [LadybugDB](https://github.com/mpsuesser/scraped-docs-ladybugdb), [Pi](https://github.com/mpsuesser/scraped-docs-pi), [PlanetScale](https://github.com/mpsuesser/scraped-docs-planetscale), [ts-morph](https://github.com/mpsuesser/scraped-docs-ts-morph), [Turborepo](https://github.com/mpsuesser/scraped-docs-turborepo)

[effect-oxlint](https://github.com/mpsuesser/effect-oxlint): Wraps the oxlint plugin SDK with Effect so it's more ergonomic to write all your custom oxlint rules Effect-firstly. Kinda pointless but I do use it and some other people do too

[oxlint-plugin-effect](https://github.com/mpsuesser/oxlint-plugin-effect): Custom lint rules for my projects, mostly the lint-rulified versions of the patterns enforced at write-time by [opencode-effect-enforcer](https://github.com/mpsuesser/opencode-effect-enforcer)

[yazi](https://github.com/mpsuesser/yazi): Fork of the original [yazi](https://github.com/sxyazi/yazi) because I use it so much and had some bespoke customizations I wanted to make

[effect-prodigi](https://github.com/mpsuesser/effect-prodigi): Good binding for a Print-on-Demand SaaS app

## Inactive

[Dojo](https://github.com/mpsuesser/Dojo): A collection of specialized interfaces for getting information out of ones head and into something maximally legible to an agent as efficiently as possible. I'm proud of this and think there's a real gap in the market for something like this, a sidecar "game" to make working with agents more fun and engaging, like a video game. The only reason I'm not planning to take it further is because I'm all in on something else. There are plan details in the PLAN.md in case the dear reader might be interested in picking it up or doing something similar.

[interview-me-phonecall](https://github.com/mpsuesser/interview-me-phonecall): I had an 8-hour drive the next day, wanted to talk out some ideas and be sure I could use the transcripts after

[pi-effect-harness](https://github.com/mpsuesser/pi-effect-harness): This became [opencode-effect-enforcer](https://github.com/mpsuesser/opencode-effect-enforcer) when I switched from Pi to OpenCode around the time they released the v2 beta

[pi-compound](https://github.com/mpsuesser/pi-compound): Had too many things going on when this was incepted so I did not spend the time to ingratiate it and thus it never stuck

[effect-autoagent](https://github.com/mpsuesser/effect-autoagent): Low effort few-prompt experiment in applying the then-novel effect harness to reproduce the then-novel original [autoagent](https://github.com/thirdlayerinc/autoagent) project but with Effect. In hindsight this was a terrible fit and serves merely as a cautionary tale

[effect-claudecode](https://github.com/mpsuesser/effect-claudecode): I do not use Claude Code but when Fable was released I brought this up to date with Claude Code's plugin spec at the time but then it got pulled, so I never really used it. Maybe one day

[oxlint-plugin-alchemy](https://github.com/mpsuesser/oxlint-plugin-alchemy): Too much stuff, and moving too fast, and also not the greatest fit for a lint plugin to begin with

[oxlint-plugin-foldkit](https://github.com/mpsuesser/oxlint-plugin-foldkit): Devin released an [official](https://foldkit.dev/tooling/oxlint-plugin) Foldkit plugin and to my delight harvested whichever rules from this repo were worthy so now I just use that

[opencode-sketch](https://github.com/mpsuesser/opencode-sketch): I think this worked but I quickly thereafter moved my primary sketching surface to Dojo

[wxt-github-readme](https://github.com/mpsuesser/wxt-github-readme): Tiny web extension to add copy-to-clipboard buttons to the front-pages of GitHub repos for copying the README, so that if I just want to copy the README I don't need to spend an extra 5 seconds / 1 page load / 2 clicks. I forget why I stopped using it

## Unity games

For about three years my obsession was indie game development, and I worked exclusively on multiplayer client-server games.

### RUN Football

RUN Football was to [WaLK Football](https://www.youtube.com/watch?v=8vnnrjnj3q4) what DotA 2 was to DotA.

[RFB_Client](https://github.com/mpsuesser/RFB_Client-archive)

[RFB_Server](https://github.com/mpsuesser/RFB_Server-archive)

### Spire Two

Spire Two was the WoW Challenge Mode experience crystallized into a game that would never ask you to level up a character or to procure the optimal set of gear to qualify for participation; all about the dungeon run.

[SpireTwo](https://github.com/mpsuesser/SpireTwo-archive)

[SpireTwoServer](https://github.com/mpsuesser/SpireTwoServer-archive)

### Line Tower Wars 2

Line Tower Wars 2 was to [Line Tower Wars](https://www.youtube.com/watch?v=n66dx6VyKC0) what DotA 2 was to DotA.

[LTW2](https://github.com/mpsuesser/LTW2-archive)

## Real oldies

[USP-Ninjas](https://github.com/mpsuesser/USP-Ninjas-archive): This was like my first big project, wrote this when I was 14, it's a plugin for Counter Strike 1.6. There were maybe 200 people who would regularly play this game [USP Ninjas](https://www.youtube.com/watch?v=19NfFuY6dHk) on a custom map that was made specifically for it. But it was just a map, and there were rules to the game, so sometimes people would break the rules, and the only way to referee was to yell about it in all chat. And you had to manually facilitate picking teams, restarting the rounds, keeping track of the real score, and so on. This plugin formalized and enforced all of that stuff so that we could all just play the game.

[wc3fball-discord-lobby-bot](https://github.com/mpsuesser/wc3fball-discord-lobby-bot-archive): We had a small community of people who loved to play [WaLK Football](https://www.youtube.com/watch?v=8vnnrjnj3q4), which requires 8 people to play. It's a Warcraft 3 custom game so you have to launch the game, log in, join the lobby, and wait for 8 people. But there's all these subtle frictions that come with requiring people to sit waiting in the in-game lobby for 30+ minutes. So this was a Discord bot where people could !ready and !unready in Discord, and when the ready count got to 8 it would ping everybody so we could all fire up the game and join the lobby and go.
