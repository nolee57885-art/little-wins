# THE SYSTEM — WARRIOR

A Solo Leveling-inspired real-life progression dashboard.

## Current prototype
- Responsive dark / blue holographic dashboard
- Player level, XP bar, ranks and six attributes
- Daily quests, Monday/Wednesday/Friday workout quest
- Custom quest creation
- Achievements and a persistent System Log
- Local browser persistence (localStorage)

## Schedule configured
- Wake: 07:00
- Sleep: 23:00
- Strength training: Monday, Wednesday, Friday

## Open the prototype
Visit [the app](./index.html).

## Important prototype limitations
This first version saves data in the current browser only. It does **not** yet sync between devices, send push notifications, or calculate streak penalties. Cloud sync requires a backend and credentials (for example, Supabase or Firebase), plus authentication and security rules. Do not store medical or financial account details in this prototype.

## Roadmap
1. Core progression and quests
2. Skill tree, streak rules, boss battles and penalty/recovery quests
3. Notifications, sound and richer animations
4. Cloud sync, authentication, installable PWA and analytics
