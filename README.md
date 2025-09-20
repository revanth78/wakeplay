# WakePlay

WakePlay is a mobile alarm app that wakes users with their YouTube Music playlists.  
At the scheduled alarm time, the app automatically opens the YouTube Music app with the chosen playlist.

## MVP
- Connect a YouTube Music playlist URL.
- Create an alarm with a time + playlist.
- At alarm time, WakePlay opens YouTube Music with that playlist.
- No snooze option — only Stop via YouTube Music app.

## Tech Stack
- React Native (bare, version 0.74)
- Android: AlarmManager + Intent to open YouTube Music
- iOS: Local notification + deep link (requires tap to start)
- SQLite for alarms
- Trello for PM, GitHub for repo/CI

## Why?
Most alarm apps use harsh tones. WakePlay lets you wake up to your own playlists with minimal complexity.


