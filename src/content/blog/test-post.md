---
title: "Devlog #1: Welcome to Duskvale"
description: "The journey begins – laying the foundation for our web-based MMO"
pubDate: "Apr 29 2025"
heroImage: "/blog-placeholder.png"
---

Welcome to the very first devlog for **Duskvale**, a passion project I’ve been building—a browser-based MMORPG set in a dark fantasy world filled with choices, consequences, and community-driven storytelling.

Over the past few months, I've been laying the groundwork for Duskvale's core systems: character creation, combat mechanics, and server-side logic. The game aims to bring back the feel of old-school MMOs, but with a modern, web-native twist. Everything runs in the browser, but underneath is a carefully structured architecture with turn-based combat, energy-based turn order, character classes and evolutions, and real-time player interactions.

### What’s Done So Far

- ✅ **Combat System:** A turn-based engine that calculates action priority based on energy and attack speed. Defensive stances, damage scaling, and stat-based modifiers are in place.
- ✅ **Character Classes:** A class and subclass structure with level-based evolution. Players can evolve into different roles, but only if they meet certain conditions—otherwise, expect a little "punishment" from the server. 😉
- ✅ **Database Integration:** User accounts, character stats, and progression are stored using PostgreSQL and managed with Drizzle ORM.
- ✅ **Basic UI & Dev Tools:** Testing the game using a simulated battle environment. Progress is tracked with unit tests and debug tools to help polish mechanics.

### What’s Next

- ⚒️ **Quests & Worldbuilding:** The tavern system will soon allow players to pick one of three randomized quests—an early step into procedural narrative.
- ⚒️ **PvE Encounters:** AI enemies are being added, starting with simple logic that escalates in difficulty.
- ⚒️ **Frontend Polish:** Once the mechanics are solid, I’ll shift more energy toward making the UI enjoyable and responsive.

This is just the beginning. Duskvale is a huge project, and I’ll be documenting my progress here step by step. Thanks for reading—and if you’re interested in helping test the game, stay tuned!

— _JCBK Dev_
