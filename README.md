## Jose Montalvo

Designer of 25 years. I now spend most of my time building and shipping web applications.

### What I build with

Cloudflare Pages and Workers, D1, R2, Wrangler. Stripe for billing, Resend for transactional email. Python for build and release tooling. Luau and Rojo for Roblox.

### Live work

**[Spellframe](https://spellframe.app)** is my main project. A single Worker backend of about 1,300 lines behind a static front end, with accounts, sessions, password hashing, email verification, an admin dashboard gated by a deploy-time secret, and Stripe billing across both one-time purchases and subscriptions. Schema changes ship as numbered migration files that run before the deploy.

**[Volthaven](https://github.com/chasenbud75/Volthaven)** is a round-based team arena shooter for Roblox, about 9,500 lines of Luau. The arena, HUD, weapons and effects are all generated at runtime, so it runs the moment Rojo syncs it into an empty baseplate. One command builds and publishes it, and the script refuses to run with debug enabled or the audit dirty.

Most of my other work is private or belongs to clients, so the contribution graph carries more than the repository list does.

### How I work

I build with a coding CLI every day. I decide the architecture, I read every change before it lands, and I do my own debugging and deploys.

Based in Naugatuck, Connecticut. Bilingual in English and Spanish.
