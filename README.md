# First-Time Chat Timeline

Every viewer's first recorded message in **hekimae**'s Twitch chat,
2016 to 2026.

**15,034 chatters. 1,101 streams. 159 games.**
Found by reading 3,198,894 chat messages.

## What this is

11 years of archived Twitch chat, reduced to a single moment per person:
the first message the archive has of them. Everyone appears exactly once, on the
earliest stream they turn up in, oldest first.

This is **not** a complete history of the channel's chat. It covers only the
VODs that were still available to download, so plenty is missing, the early
years especially.

## Viewing it

Open `index.html` in any browser. Keep the `assets` folder beside it: that is
where the emote images and the typeface live. Nothing is loaded from the
internet, so it works offline and needs no server.

GitHub will not render the page from the file listing. Either enable GitHub
Pages for this repository, or download the folder and open `index.html`
locally.

## Using it

- **Look for yourself.** Search your name to find your first recorded message.
- Whatever you search or filter for is kept in the address bar, so you can share
  the link and it opens on the same view.
- Press **/** to jump to the search box, **Escape** to clear it.
- Filter by year or by game, and every stream heading is a permanent link.

## Notes

- Timestamps are positions in the VOD, so `[0:42:15]` is 42 minutes into that
  stream.
- Names appear as the archive recorded them. If someone has since changed their
  Twitch name, searching either one will still find them.
- The early years are thin. Only VODs that still existed when this was captured
  could be read, so some long-time regulars turn up later here than they really
  arrived.
- 2,611 emote images are stored alongside the page, so it keeps rendering
  even if Twitch retires an emote. A few emotes were never saved in the source
  logs and appear as plain text.
- Chat bots are left out. Their first message is command output, not a person
  arriving.
- Messages appear exactly as they were sent.

## Contents

| Path | What it is |
|------|------------|
| `index.html` | The timeline |
| `assets/emotes/` | Emote images used in the messages |
| `assets/fonts/` | Inter, the typeface Twitch uses (SIL Open Font License) |

Built 11 August 2026 from hekimae's VOD chat logs. This is a read-only
snapshot and does not update on its own.
