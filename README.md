# Aion

A native macOS timer and personal workspace for Tasks, projects, Statistics,
Blocking and Settings. Plan in list, board, table, calendar and timeline views,
then start a focus session from a task. Calendar pairs a compact month with a
readable two-line agenda; Timeline keeps dates and task rows clear.

[Download Aion 1.3.21](https://github.com/AgarwalAarush/Flow-Personal-Releases/releases/tag/v1.3.21).

Time Tracker is optional and starts paused. Start or pause local tracking,
review app time and Idle intervals, and adjust an app’s category. Idle can include
aggregate inactivity or an inactive console session. Saved activity stays on
this Mac; tracking does not read keystrokes, window titles or browser history.

A compact date capsule moves between recorded days and returns to Today.
Grouped Work, Leisure, Watching, Other and Idle cards keep totals together
above the daily timeline. Past days show their recorded totals; the current
app or website appears only on Today. Days without recorded apps or websites
say so, including days with only Idle intervals.

Dia website classification is optional and remains Preview. Basic classification
uses native Accessibility and Automation access, enabled explicitly from Connect
Dia. It requires no browser extension. Accessibility reads only the focused
window identifier; Automation reads the selected tab only in the matching normal
window. Unknown windows skip website capture. Focused incognito time is Leisure
without reading its tabs. Only normalized hostnames are saved, never titles,
full URLs, queries or browsing history. App and Idle tracking work without these
optional permissions. The companion remains optional for video playback checks
on supported streaming sites. Continuous integration in the released app on a
compatible Dia Mac remains unverified; the identifier contract was owner-reported.

Google search, ChatGPT, Gemini and common development/research sites default to
Work. Reddit, games and gaming-related browsing use Leisure; this describes the
category of activity, not proof of gameplay. Personal website rules take priority
over browser/app defaults. Known work apps and public application categories also
supply defaults, without matching app display names. Existing Gaming history and
rules keep their stored identity under the new Leisure label.

Statistics has calendar Day, Week, Month and Year views in one compact chart.
Browse previous periods, then return to the current live range. A date-navigation
capsule, bold D/W/M/Y selector and compact metric cards keep the chart readable.
Hover a bar for details beside it; empty dates have a quiet baseline target.
Trend comparisons appear when the matching previous interval contains focus
time; their help states the exact comparison window. The graph has no separate detail row,
Daily Focus/average footer or session export. Primary pages fit without
scrolling; compact page controls keep longer collections reachable.

Aion stays out of the Dock and Command-Tab, including when Tasks, Statistics
or Settings is open. Open it from its menu bar item, Finder or Spotlight.

The Full timer is 400 × 275 pt. Hover to reveal its actions; Close hides the
window while the timer continues. The menu bar shows the countdown and toggles
the window. Use **⌘1** to show the timer, **⌘2** to switch Full ↔ Compact and
**⌘W** to hide it. Compact titles are read-only; edit names in Full.

View shortcuts follow the switcher order: ⌘3 Tasks, ⌘4 Today, ⌘5 Inbox,
⌘6 Completed, ⌘7 Time Tracker, ⌘8 Statistics and ⌘9 Blocking. Settings remains
⌘, and Keyboard Shortcuts is ⇧⌘/. Owned editors and sheets retain their save and
cancel behavior. Session Rhythm selectors and automatic-start settings have more
internal padding while keeping their compact layouts.

Light and dark appearances, reduced motion and native keyboard controls are
supported. The original completion chime is controlled by **Play a sound** in
Settings → General. Session notifications rotate through 75 sourced quotations
from 17 published authors. Existing sound, appearance and update choices remain
unchanged.

Automatic update checks and installation default off. Running intervals pause
just before an update restarts Aion, then resume with their remaining time
intact. Paused and idle timers stay paused; downloads keep the timer running.
Versions before 1.3.15 may show their previous manual-pause prompt once.

Aion was previously Flow Personal. Existing projects, tasks, history, settings,
storage and update identity carry forward. New downloads contain **Aion.app**.
This independent personal app by Aarush Agarwal coexists with Yugen GmbH's
Flow.app; do not replace that app. Requires macOS 14 or later; universal Intel
and Apple Silicon app.

This repository distributes installers and signed update feeds only. Application
source remains private. Downloads are ad hoc signed and **not Apple Developer
ID signed or notarized**. Sparkle Ed25519 signatures authenticate feeds and
archives. Respect macOS security warnings; do not disable Gatekeeper or remove
quarantine. The existing canonical updater feed remains `appcast.xml`.
