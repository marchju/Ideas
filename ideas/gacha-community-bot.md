# Gacha Community Bot for Server Owners

**Status:** Idea · **Type:** Side hustle (build once, sell many) · **Added:** 2026-11-20

## One-liner

A Discord bot that keeps gacha fan and guild servers active. It is built for the people who **run** servers, not for individual players.

## Problem

Gacha communities (Genshin Impact, Honkai: Star Rail, Zenless Zone Zero, and others) are busy around patches and quiet in between. Server admins have no easy way to keep members engaged. Existing bots, such as Hoyo Buddy, mostly serve individual players rather than the server as a whole.

## Target customer

- **Payer:** admins and mods of gacha fan servers, guild servers and content-creator community servers.
- **Users:** the members of those servers.

## Core features

### Reminders and timers
- Shared server calendar for events, banners and patches
- Daily and weekly reset pings and patch countdowns, posted to a chosen channel

### Stats and build lookups
- Members link their in-game UID
- In-chat profile and build cards that anyone can look up

### Server engagement
- Server-wide pull-luck leaderboards ("luckiest/unluckiest of the week")
- Achievements and auto-assigned roles for milestones
- Automatic weekly recap post

## Business model

- **Free tier:** calendar, reminders, basic lookups, one leaderboard
- **Premium:** $3–5/month **per server**, paid by the admin. Includes custom branding, extra leaderboards, recap posts and an admin dashboard.
- Each admin brings in a whole server, so growth comes through servers rather than one player at a time.

## Why it fits me

- Needs only a few hours a week, and hosting costs are close to $0
- Uses tech and coding skills
- I play these games, so I know the pain points firsthand
- Paying customers (server admins) are easy to find and reach

## Competition and positioning

| Existing bots | This bot |
|---|---|
| Player-first (my stats, my reminders) | Server-first (community calendar, leaderboards, recaps) |
| Free, no clear premium for admins | Admin-facing premium tier |

## MVP (v1)

1. Event and banner calendar with reset reminders
2. One server-wide leaderboard
3. Test in 3–5 servers I'm already in

**Success signal:** admins keep the bot installed and ask for more features.

## Open questions

- Which game to launch with first: Genshin, HSR or ZZZ?
- Where to get data for events, banners and profiles (community APIs, Enka.Network, official sources), and whether the terms of service allow it
- Tech stack (discord.py vs discord.js) and cheap hosting options
- How to import pull history safely, given the privacy and authentication concerns
- Which premium features are worth paying for
