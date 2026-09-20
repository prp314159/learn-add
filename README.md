# Learn to Add

A one-page app that teaches a 5 year old what addition *is*: putting two groups together and finding out
how many there are now. The thinking behind every choice is in [PLAN.md](PLAN.md).

## The two games

- ✋ **Play:** no questions. Tap a box and one object hops onto the tray. Tap an object on the tray and it
  hops off again. The number sentence above the tray changes live. A full row of 5 sparkles, a full tray
  of 10 gets a fanfare, and 🌪️ tips everything off.
- 👀 **How many?:** the app deals two groups. He finds the total any way he likes and taps it. He may move
  the objects to the tray one tap at a time, count them by touching them, or just answer straight away.
  Five stars win a trophy, which is a good moment to stop for the day.

The small round letter in the corner is the parent dial. **Press and hold it** for a second to switch
between Level A (totals up to 5) and Level B (totals up to 10). The app remembers the level and his place
in the sums.

## Parent card

The words of addition ("and", "altogether", "makes") are part of the idea. After a right answer the app
says the bare sentence in the device's own voice ("three, and two, make five"), but it cannot tell a
story or ask a question. For the first sessions at least, sit with him:

- When the numbers pulse after a right answer, say it along with the app: **"3 and 2 make 5."**
- Ask **"how did you know?"** Any answer is good. Explaining is where the learning settles.
- Ask **"what if one more came?"**
- After a miss the objects bounce slowly, one at a time. Count along with him, out loud. After a second
  miss the app counts aloud as well.
- Away from the iPad, tell tiny stories of both kinds. Some more come: "you have 3 cars, I give you 2
  more." Two groups together: "3 red cars and 2 blue cars, how many cars?"
- Short sessions on several days beat one long one.

Before the first session, and again after two or three weeks, do the five-minute check with real blocks
and cups from "Step zero" in the plan. What he does differently is the only real evidence that the app
taught him anything.

## What to watch for

The list is at the end of [PLAN.md](PLAN.md). The most useful ones at the start: does he count aloud or
tap and guess, does he answer before moving anything, and does he touch the objects on the tray to count
them?

## The voice, and your own voice (optional)

The app speaks with the device's own voice in two places only: the sentence after a right answer, and the
numbered count after a second miss. It needs no files and no internet. To hear "plus" and "equals"
instead of "and" and "make", change the one `SAYING` line in `index.html`.

Your own voice is nicer than the device's. If he often plays alone, record "one" to "ten" on a phone and
put the ten files in a `sounds/` folder next to `index.html`, named `1.m4a` to `10.m4a` (`.mp3` and `.wav`
work as well). The app then uses your number words in the numbered count, and also says the new total on
every landing in Play. It never counts his own hops in "How many?", because that would do the thinking
for him.

## Changing the objects

The objects are emoji pairs at the top of the script in `index.html` (`SETS`). Put what he loves first.
A new pair comes after every trophy. Keep the pairs red and blue or red and yellow, never red and green.

## Running it

It is a single `index.html` with no build step. Any static web server works:

```bash
python3 -m http.server 8137
```

Then open `http://localhost:8137`. On the iPad, host the folder on any HTTPS site (GitHub Pages, for
example), open it in Safari, and use Share, then Add to Home Screen. It then opens full screen and works
without internet. On a phone it is played in landscape.
