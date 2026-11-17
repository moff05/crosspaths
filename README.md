# crosspaths.

**See when friends can actually meet between classes at the University of Miami, with walk times and lines built in.**

**Live demo:** https://crosspathing.lovable.app (tap **"see how it works"** for the guided tour; best viewed at phone width)

Built for the Lovable x UMiami Buildathon (AI Business Association), November 2026.

---

## The problem

College free time comes in 15 to 90 minute gaps between classes. "We should get lunch" rarely happens because nobody knows whether a friend's gap lines up with theirs, how far apart they are, or how long the line at the Rat is right now. Group chats can't answer that.

## What it does

Other social calendars (Saturn, Howbout) show **when** you're free. Crosspaths answers **whether you can actually meet, and where**: shared free windows, walk times from each person's class building, typical line waits, and the time you actually get together.

## The flow

1. **Open the app** and see your day as a timeline: classes, the gaps between them, and how many friends are free in each gap.
2. **Tap your next gap** to see who's free during it, where they're coming from, and how far away they are. Groups come first.
3. **Tap "meet"** on a friend or a group. A quick invite opens with suggested times and spots that work for everyone. No typing needed.
4. **Send.** Friends reply with one tap. When they're in, you get a notification, the plan shows up on your timeline, and one tap adds it to Google Calendar (or downloads an .ics for Apple Calendar).

## Features

- Day timeline built from your real class schedule
- Shared free windows with walk time and estimated line waits
- One-tap invites to friends and groups ("2:00 · peet's?")
- Group invites with live "2 of 2 in" progress
- Add to Google Calendar / .ics export
- Privacy first: nobody can search for or browse students. You add friends by exact username or invite link, and each friend sees only your free windows unless you choose to share more.
- Guided 7-step demo tour that runs on a real UM schedule with simulated friends

## Roadmap

- Partial group availability ("2 of 3 free") with a no-pressure heads-up to busy members
- Counter-proposals ("suggest another time/place") and custom time/place entry
- Schedule import from a screenshot or pasted class list
- Push notifications and automatic calendar sync
- Real line data from check-ins instead of estimates

## Built with

[Lovable](https://lovable.dev) · React · TypeScript · Vite · Tailwind CSS · shadcn/ui

> The app's source is developed in Lovable. This repo documents the project; the code can be synced here through Lovable's GitHub integration.
