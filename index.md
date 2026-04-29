---
title: Moor
---

# Moor

An ADHD task companion that reads your connected Google accounts to surface
the single most useful task to do today.

## What Moor does

Each morning at 06:00 (Australia/Sydney), Moor reads recent emails and
upcoming calendar events from your connected Google accounts and produces a
brief: one primary recommendation, up to two alternatives, and any external
commitments in the next seven days. Throughout the day, Moor reconciles
email-derived task items with completion signals (payment receipts, reply
confirmations) and auto-closes the ones that are clearly done.

The app is built around the working assumption that the most useful thing an
ADHD-medicated user wakes up to is *one clear next thing to do*, not a list.
Moor never produces a list of more than three actionable items at a time,
never schedules user-internal work to a specific clock time, and never
overrides a "done" signal from the user.

## What data Moor reads

Two read-only Google scopes per connected account:

- **Gmail** (`gmail.readonly`) — recent message metadata (sender, subject,
  snippet, date, message ID) for actionable email and completion-signal
  matching. Email bodies are never read.
- **Google Calendar** (`calendar.readonly`) — upcoming events (title, start,
  end, attendees) for the next seven days, surfaced as external commitments
  in the daily brief.

Full details are in the [privacy policy](privacy-policy).

## Who runs Moor

Moor is a personal project run by Christopher Banham. As of April 2026 it is
used only by the author; there is no public signup. Contact:
**drink@fountainheadwinehouse.com**.

## Legal

- [Privacy policy](privacy-policy)
- [Terms of service](terms-of-service)
