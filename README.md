# TrailerHero

TrailerHero is a Decky Loader plugin that makes Steam Big Picture feel a little more like a console dashboard.

When you open a game page, the plugin keeps the original Steam hero artwork in place, waits a moment, then fades in a muted trailer inside the same hero area. It can use Steam trailers first, and YouTube as a fallback when Steam has nothing useful.

It also supports the Steam Big Picture home page, per-game video choices, custom Steam AppID mapping for non-Steam games, intro/outro trimming, optional CRT styling for low-resolution videos, and a small logo assist for game pages that use tiny SteamGridDB logos.

## Languages

TrailerHero follows the current Steam or browser language automatically.

Included languages:

- English
- Italian
- French
- Spanish
- Portuguese
- Brazilian Portuguese
- German
- Dutch
- Ukrainian
- Chinese
- Japanese

## Main Controls

- **Enabled** turns the effect on or off.
- **Delay** chooses how long the hero stays still before the trailer appears.
- **Steam quality** chooses the preferred Steam trailer quality.
- **Enable on home** also plays trailers on the Steam Big Picture library home.
- **Game page logo** moves the game logo to the bottom-left while the trailer is visible, then restores it when you leave.
- **Automatic CRT** applies a subtle CRT look to low-resolution trailers.
- **Source** lets each game use automatic mode, Steam, or YouTube.
- **Steam AppID source** lets a non-Steam game borrow trailers from a Steam app.
- **Steam video** lets you choose any Steam video returned for that game, not just the highlighted trailer.
- **Trim start / Trim end** saves per-game video trimming.
- **YouTube fallback** lets you save or auto-search a YouTube trailer when Steam does not have one.

## Notes

The plugin should work well on Linux, but it was built on and for Windows. Please keep this in mind.

This plugin works by carefully reading and adapting Steam Big Picture UI elements. Steam changes its interface often, so some selectors may need updates over time.

YouTube is handled through the embedded player. TrailerHero hides as much player chrome as possible, but YouTube can still briefly show its own internal overlay in some cases.
