# Awesome Effect-TS [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of genuinely useful libraries, integrations, applications, and content built on or around [Effect](https://effect.website) — the TypeScript ecosystem for building robust, type-safe applications.

## Contents

- [Frontend & UI](#frontend--ui)
- [AI & LLM](#ai--llm)
- [Database & ORM](#database--orm)
- [Observability](#observability)
- [Messaging & Workflows](#messaging--workflows)
- [Cloud](#cloud)
- [Applications](#applications)
- [Learning & Starters](#learning--starters)
- [Articles & Blog Posts](#articles--blog-posts)
- [Videos & Talks](#videos--talks)
- [Podcasts](#podcasts)

## Frontend & UI

- [Foldkit](https://github.com/foldkit/foldkit) - A frontend framework built on Effect implementing The Elm Architecture: a single immutable model, one update function, and side effects returned as values. Ships `create-foldkit-app` and a Vite plugin with state-preserving HMR ([foldkit.dev](https://foldkit.dev/)).
- [effect-atom](https://github.com/tim-smart/effect-atom) - Reactive state toolkit for Effect by Tim Smart. Derived, effectful, and Stream-pulling atoms, a React adapter (`useAtomValue`/`useAtomSet`), and an `AtomRpc` module integrating `@effect/rpc`.
- [@hookform/resolvers](https://github.com/react-hook-form/resolvers) - React Hook Form ships an Effect Schema resolver, so you can validate forms with Effect Schema.

## AI & LLM

- [effect-uai](https://github.com/betalyra/effect-uai) - Agentic AI toolkit built on Effect: agent loops, tools, streaming, structured output, embeddings, speech, and music generation as composable primitives ([effect-uai.betalyra.com](https://effect-uai.betalyra.com/)).
- [CuttleKit](https://github.com/betalyra/cuttlekit) - Generative UI toolkit built on Effect for building AI-driven, dynamically generated interfaces ([cuttlekit.com](https://cuttlekit.com/)).

## Database & ORM

- [Drizzle ORM](https://orm.drizzle.team/docs/connect-effect-postgres) - The popular TypeScript ORM ships first-class Effect support; see also the official [`@effect/sql-drizzle`](https://github.com/Effect-TS/effect/tree/main/packages/sql-drizzle) integration for using Drizzle's query builder inside Effect's SQL layer.
- [confect](https://github.com/rjdellecese/confect) - Deep integration of Effect with [Convex](https://convex.dev): define schemas and validators with Effect Schema and build HTTP APIs (with Scalar OpenAPI docs) via Effect's HTTP modules ([confect.dev](https://confect.dev)).

## Observability

- [@sentry/effect](https://github.com/getsentry/sentry-javascript/tree/master/packages/effect) - Official Sentry integration for Effect; capture errors and traces from your Effect runtime ([docs](https://docs.sentry.io/platforms/javascript/guides/effect/)).

## Messaging & Workflows

- [effect-messaging](https://github.com/spiko-tech/effect-messaging) - Message-broker abstractions (e.g. AMQP) modeled as Effect services.

## Cloud

- [@effect-aws](https://github.com/floydspace/effect-aws) - Effect layers for the AWS SDK v3: clients, Lambda handlers, and helpers as composable services.
- [Distilled](https://github.com/alchemy-run/distilled) - Effect-native building blocks from the Alchemy infrastructure-as-code project.

## Applications

- [opencode](https://github.com/sst/opencode) - The open-source AI coding agent from the SST team, built on Effect.
- [Effect Community Discord Bot](https://github.com/Effect-TS/discord-bot) - The community Discord bot, a real, non-trivial Effect application.

## Learning & Starters

- [effect-crashcourse](https://github.com/pigoz/effect-crashcourse) - A hands-on crash course covering Effect fundamentals.
- [effect-introduction](https://github.com/antoine-coulon/effect-introduction) - An approachable introduction to why Effect exists and how to think in it.
- [effect-app](https://github.com/effect-app) - Core libraries ([libs](https://github.com/effect-app/libs)) and a [boilerplate](https://github.com/effect-app/boilerplate) for building full-stack apps with Effect.

## Articles & Blog Posts

- [Understanding Why You'd Use Effect TS](https://cm.xyz/blog/understanding-why-youd-use-effect-ts) - Cooper Maruyama. 
- [How to implement a backend with Effect](https://www.typeonce.dev/article/how-to-implement-a-backend-with-effect) - Sandro Maglione (Typeonce). In-depth walkthrough of a full Effect backend: `HttpApi`, routing, PostgreSQL, and a derived type-safe client.
- [PostgreSQL database with Effect and Drizzle](https://www.typeonce.dev/course/paddle-payments-full-stack-typescript-app/server-implementation/postgres-database-with-effect-and-drizzle) - Typeonce course chapter on wiring Drizzle into an Effect app.
- [A Type-Safe GraphQL Backend with Effect and Drizzle](https://dev.to/martinpersson/building-a-robust-backend-with-effect-graphql-and-drizzle-k4j) - Martin Persson.
- [Building Robust TypeScript APIs with the Effect Ecosystem](https://dev.to/martinpersson/building-robust-typescript-apis-with-the-effect-ecosystem-1m7c) - Martin Persson.

## Videos & Talks

- [Effect | TypeScript at Scale](https://www.youtube.com/c/EFFECT-TS) - The official Effect YouTube channel (Effect Days talks, Office Hours, and more).
- [Effect: The Origin Story](https://www.youtube.com/watch?v=7sJc3Z4mh1w) - Michael Arnaldi (Effect Days 2024).
- [Effect: A Functional Foundation for TypeScript](https://www.youtube.com/watch?v=BHuY6w9ed5o) - Michael Arnaldi (LambdaConf 2024).
- [Effect Days 2024 — Beginner / Intermediate Workshop](https://www.youtube.com/watch?v=Lz2J1NBnHK4) - Ethan Niser.

## Podcasts

- [Cause & Effect](https://effect.website/podcast/) - The official Effect podcast.
- [Lucas Barake](https://www.youtube.com/@lucas-barake/videos) - Channel with many in-depth episodes and videos about Effect.

## Contributing

Contributions are welcome! Read the [contribution guidelines](contributing.md) first. The bar for inclusion: actively maintained, genuinely useful, and clearly connected to Effect — no abandoned experiments.
