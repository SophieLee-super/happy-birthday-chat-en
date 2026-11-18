# Happy Birthday, in a Chat 🎂

A tiny interactive birthday website — a programmer's-romance gift for a friend.
One single `index.html`, no build step, no dependencies. Open it and it plays.

## What it does

1. **A simulated chat** — messages arrive one by one in a phone-style chat box, with typing dots and tap-to-reply choices (a small branching script, including a "Crazy Thursday" joke that follows the real weekday of the birthday).
2. **What's special about your birthday** — one plain sentence per screen, tap to see the next: the weekday you were born, who shares your birthday, what happened on this day in history, your birth flowers, how many days you've been in the world, and the age you're turning.
3. **Balloons, lights and a cake** — balloons rise from the bottom of the screen, and there's one candle to tap out and make a wish.
4. **A letter** — typed out character by character at the end.

## Make it yours in one minute

Everything personal lives in one `CONFIG` block at the top of the script inside `index.html`:

- Change `birthDate` to your friend's birthday (`YYYY-MM-DD`) — the weekday joke and the whole "special birthday" section regenerate automatically.
- Or just share a link with the date in it: `index.html?date=2000-01-01` — the date in the link wins, no code editing needed.
- Edit the chat lines, the choice replies, and the letter text in the same `CONFIG` block, word for word however you like.
- Same-day celebrities / history lines live in a small lookup table keyed by `MM-DD` — add your friend's date if it's not there yet (dates not in the table simply skip those two lines).

## Run it / publish it free

- Locally: just open `index.html` in any browser.
- Online: enable **GitHub Pages** (Settings → Pages → Deploy from branch `main`, folder `/ (root)`) and share the link it gives you. Add `?date=YYYY-MM-DD` to the link to generate the site for that birthday.

## License

MIT — fork it, change the words, and give it to your own person.
