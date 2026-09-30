# Chatso

**A desktop chat and moderation app for Kick.com.**

🇹🇷 [Türkçe README](README.tr.md)

![Chatso main window](docs/screenshots/01-main-chat.png)


---

## Highlights

- **Multi-channel tabs** — every channel you moderate in one window, with live status, viewer count and stream title.
- **Fast moderation** — timeouts and bans on keyboard shortcuts, ban with your own reason, message deletion, bulk moderation and word-based auto moderation.
- **Subscriptions and KICKS** — subs, gifted subs, KICKS gifts and channel-point redemptions, both inline in chat and in a separate filterable window.
- **Streamer panel** — stream title and category, subscriber counts, KICKS leaderboard, channel point rewards and ad breaks.
- **Giveaways** — keyword entry, subscriber luck multiplier, participant search, and one click from a winner to their chat history.
- **Smooth chat** — no message cap; a virtualised list keeps the flow smooth even on modest hardware.

---

## A closer look

### Subscriptions and KICKS

Every subscription, gifted sub, KICKS gift and reward redemption in one list. Filter by type, channel, user or message text, and by a minimum KICKS amount. The window can stay on top while you work.

![Subscriptions and KICKS window](docs/screenshots/02-events-window.png)

### Moderation history

Every action taken through the app, searchable and filterable by action type, channel, moderator and time range. You choose which channels get recorded in the first place.

![Moderation history](docs/screenshots/08-moderation-history.png)

### Giveaways

Collects viewers who type your keyword, gives subscribers a luck multiplier and blocks duplicate entries. Participants are searchable, and clicking a winner opens their profile and chat history.

![Giveaway window](docs/screenshots/03-giveaway-window.png)

### Notifications

Get notified when you are mentioned, when your keywords appear, or when a channel goes live — including channels you do not have open as a tab. Three notification designs, screen position, duration and a custom sound.

![Notification settings](docs/screenshots/06-settings.png)

### Bot messages

Timed messages and warning messages per channel. A "minimum new messages" condition keeps the bot from talking to an empty room, and messages can be sent from your own account.

![Bot messages](docs/screenshots/07-bot.png)

### Vertical chat window

A narrow chat window made for a second screen while you stream: send messages, change font size, toggle timestamps and keep it always on top.

![Vertical chat window](docs/screenshots/05-vertical-chat.png)

### Highlighted messages

Messages matching your highlight keywords are collected in their own window so you can come back to them after the stream.

![Highlights window](docs/screenshots/04-highlights-window.png)

---

## Full feature list

**Chat**
- Kick global and channel emotes, plus 7TV emotes
- Emote autocomplete with `:`, replies, message deletion
- The channel's pinned message shown above the chat
- Role colours (broadcaster / moderator / VIP-OG / viewer) and per-badge visibility
- Searchable viewer list grouped by role
- No message cap; scrolling up pauses the flow and one click returns to live

**Moderation**
- Timeout and ban on keyboard shortcuts
- Plain ban sends no reason; "Ban with reason" lets you write your own
- Message deletion and per-user chat history from the profile view
- Bulk moderation (ban/unban from a list)
- Auto moderation: ban and timeout words, spam and emote-spam protection
- See which moderator took which action, inline in chat
- Moderation history with filters, and per-channel recording control

**Streamer panel**
- Stream title, category and tags — also from a shortcut in the chat window
- Subscriber counts, KICKS leaderboard, channel point rewards and redemptions
- Ad breaks

**Notifications**
- Mentions, your own keywords, and channels going live
- Separate tabs for stream alerts and other notifications
- Test previews are shown but never recorded in the list

**Other**
- Chat logging to a file, for the channels you pick
- Turkish and English interface
- Automatic updates

---

## Install

1. Download `Chatso Setup.exe` from the [latest release](../../releases/latest).
2. Run it. If Windows SmartScreen appears, choose **More info → Run anyway**.
3. Open the app and use **Account → Login** to sign in with Kick. The browser tab closes itself once you approve.
