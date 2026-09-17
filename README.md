# wildguess word list

Daily word source for the WildGuess (AnyWord) app.

`words.json` maps an Eastern-Time date (`yyyy-MM-dd`) to that day's word. The app
fetches this file on launch and looks up today's entry.

To add more days, just add more `"yyyy-MM-dd": "WORD"` entries (word must be
4-12 uppercase letters). Old entries can stay forever — they double as a log of
every word that's ever been used.
