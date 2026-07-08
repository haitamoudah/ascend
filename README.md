<p align="center">
  <img src="resources/ascend-logo.png" alt="ascend logo" width="96" />
</p>

<h1 align="center">ascend</h1>

<p align="center">a local-first personal dashboard. the ascent starts here.</p>

<p align="center">
  <a href="https://github.com/haitamoudah/ascend/releases/latest"><img src="https://img.shields.io/github/v/release/haitamoudah/ascend" alt="latest release" /></a>
  <img src="https://img.shields.io/badge/platform-windows-1A2540" alt="platform" />
</p>

## screenshots

| home | progress |
|---|---|
| ![home screen with momentum, streaks, and a 14-day sparkline](docs/screenshots/home.png) | ![progress tracker with stat tiles and the cumulative ascent chart](docs/screenshots/progress.png) |

![settings with theme variants, behavior, and data tools](docs/screenshots/settings.png)

## features

- weighted habits with per-day schedules: binary, quantity, and duration types
- daily logging in under 30 seconds, with a backfill window for missed days
- a pure scoring engine: streak multipliers, penalties for logged misses, partial credit, and effective-dated parameter changes (history is never rescored)
- charts that draw your climb: cumulative ascent line, daily bars, completion heatmap
- a home screen with momentum vs last week, top streaks, and a 14-day sparkline
- three dark themes: midnight, graphite, and void
- integrated window chrome: a themed header with a drag region replaces the native title bar
- json export and import, daily startup backups with one-click restore
- an "erase everything" flow behind a type-to-confirm step, with an automatic backup first
- local reminders and launch-at-startup, no network anywhere

## installation

download the latest windows installer from [releases](https://github.com/haitamoudah/ascend/releases) and run it. windows may show a smartscreen prompt for an unsigned installer: choose "more info", then "run anyway".

macos and linux installers are on the roadmap.

## data and privacy

- 100% local: no cloud, no telemetry, no accounts, no network calls
- your data lives in a single sqlite database at `%APPDATA%/Ascend/ascend.db`
- a daily snapshot backup is written on launch (newest 7 kept), with extra snapshots before any import or restore
- full json export and import from settings > data
- habits are never hard-deleted: archiving keeps their history in your stats

## roadmap

- more modules: finance, journal, goals
- macos and linux installers

## support

found a bug or want a feature? [open an issue](https://github.com/haitamoudah/ascend/issues). see the [faq](FAQ.md) for common questions.
