# Aion

A native macOS app for focused work and personal planning. A quiet timer, an
explicit compact view and one workspace for Tasks, projects, Statistics,
Blocking and Settings. Plan in list, board, table, calendar and timeline views;
start focus directly from a task and keep its recorded time through renames.

Charcoal surfaces, ice-blue selections, useful action icons and restrained
transitions keep the interface simple. Light and dark appearances, reduced
motion and native keyboard controls are supported. The charcoal-and-mint
app icon accompanies an original soft completion chime. Enable **Play a sound**
in Settings → General; the speaker button previews it independently of alerts.
Existing sound and appearance choices are preserved. Completion chimes also
handle delayed background callbacks. Session notifications include a rotating
quote and author credit from a 120-entry collection of classic excerpts and
original lines credited to Aion.

The timer stays visible when another app takes focus. Hover over the full timer
to reveal Close, Skip, Restart, Statistics and session actions. Close hides the
window while the session keeps running. The menu bar shows a ticking countdown
without a second icon; click it to show or hide the timer, or right-click for
actions. Reopening Aion restores your chosen timer size.

Use **⌘1** to show the timer, **⌘2** to switch Full ↔ Compact, and **⌘W** to
hide it. Drag the empty top bar or clock to move the full timer; drag the compact
clock to move the compact timer. Keyboard controls remain available, with quiet
hover feedback and no extra focus outlines.

[Download Aion 1.3.13](https://github.com/AgarwalAarush/Flow-Personal-Releases/releases/tag/v1.3.13).

Workspace uses a compact titlebar and a top-right view switcher that opens on
hover or click. Compact timer titles are read-only; edit names in the Full timer
without an input border or text-position jump. Settings uses tighter rows and
consistent pill states. Statistics is one fixed chart with range controls inside
the card, without search, filters or a session list. All primary pages fit without
scrolling; compact page controls keep longer collections reachable.
The Full timer is 400 × 275 pt, and interval labels are Focus, Break and Long Break.
Tasks is the single personal task destination. Page content updates independently
of the countdown.

Aion was previously called Flow Personal. Existing projects, tasks, session
history, settings and update identity carry forward. New downloads contain
**Aion.app**. Existing automatic updates preserve their installation path while
using Aion's new name and icon. It coexists with Yugen GmbH's Flow.app and is an
independent personal app by Aarush Agarwal, without vendor affiliation.

This repository distributes installers and signed update feeds only.
Application source remains private. Requires macOS 14 or later; universal Intel
and Apple Silicon app.

Downloads are ad hoc signed and **not Apple Developer ID signed or notarized**.
Sparkle Ed25519 signatures authenticate update feeds and archives. Respect macOS
security warnings; do not disable Gatekeeper or remove quarantine.

Automatic update checks and installation default off. Active focus postpones
update relaunch until paused or finished. The existing canonical feed remains
`appcast.xml`.
