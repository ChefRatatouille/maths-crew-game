# PolyCrew

A chapter-based maths mission game for learning and revising Chapter 6, Multiplication of Polynomial, from *Maths Olympiad: Unleash the Maths Olympian in You! The Next Lap* (ages 12–14).

The source project is provided as [`maths-crew-game-source.zip`](maths-crew-game-source.zip). Extract it to work with the Vinext app, D1 room backend, generated migration, and original Chapter 6 practice questions. The hosted game is at https://maths-crew-game.focaldisco3.chatgpt.site.

The chapter picker includes the book's 22 topics, with Chapter 6 enabled. Other chapters need their book pages before accurate lessons can be added. The game uses original visuals and map art and does not include copied book pages.

## Quick start

Requires Node.js 22.13+.

```sh
npm install
npm run db:generate
npm run build
```

For room-code multiplayer, configure a Cloudflare D1 binding named `DB` and apply the migration in `drizzle/`.
