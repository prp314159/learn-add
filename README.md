# Learn to Add

A one-page app that teaches a 5 year old what addition *is*: putting two groups together and finding out
how many there are now. A third game teaches what subtraction is: taking some away and finding out how
many are left. A fourth game is a gentle first meeting with multiplication: the same group, again and
again. The thinking behind every choice is in [PLAN.md](PLAN.md),
[PLAN-SUBTRACTION.md](PLAN-SUBTRACTION.md) and [PLAN-MULTIPLICATION.md](PLAN-MULTIPLICATION.md).

## The four games

- ✋ **Play:** no questions. Tap a box and one object hops onto the tray. Tap an object on the tray and it
  hops off again. The number sentence above the tray changes live. A full row of 5 sparkles, a full tray
  of 10 gets a fanfare, and 🌪️ tips everything off.
- ➕ **How many?:** the app deals two groups. He finds the total any way he likes and taps it. He may move
  the objects to the tray one tap at a time, count them by touching them, or just answer straight away.
  Five stars win a trophy, which is a good moment to stop for the day.
- ➖ **How many left?:** the whole slides onto the tray, then `− 2 = ?` arrives with two empty places
  under the `2`. He taps objects on the tray and they hop up into the places, faded; a tap on a gone one
  brings it back. Then he taps how many are left, or answers straight away and the app moves the group for
  him. `0` is on the row: 5 take away 5 leaves none. The stars and the trophy are shared with "How many?".
- ✖️ **How many altogether?:** `3 × 2 = ?` arrives with three empty plates. He taps a plate and a whole
  group of 2 drops onto it: one tap is one group. Then he taps how many there are altogether, or answers
  straight away and the app fills the plates for him. Totals up to 10, eight facts. The stars and the
  trophy are shared with the other two question games.

**He earns the ✖️ button.** It is hidden until he wins a trophy while playing ➖, at either level. Then it
pops in next to ➖. This is not remembered: when the app is opened again the button is hidden again, and
one trophy in ➖ brings it back. To see ✖️ straight away, open the page with `?unlock` at the end of the
address, for example `http://localhost:8137/?unlock`.

The small round letter in the corner is the parent dial. **Press and hold it** for a second to switch
between Level A (up to 5) and Level B (6 to 10). Each question game has its own level, and the dial shows
and changes the level of the game he is in (in Play, the addition level). ✖️ has one level for now, so
the dial is hidden there. The app remembers the levels and his place in the sums of each game.

## Parent card

The words of addition ("and", "altogether", "makes") are part of the idea, and the app cannot say them.
For the first sessions at least, sit with him:

- When the numbers pulse after a right answer, say it: **"3 and 2 make 5."**
- Ask **"how did you know?"** Any answer is good. Explaining is where the learning settles.
- Ask **"what if one more came?"**
- After a miss the objects bounce slowly, one at a time. Count along with him, out loud.
- Away from the iPad, tell tiny stories of both kinds. Some more come: "you have 3 cars, I give you 2
  more." Two groups together: "3 red cars and 2 blue cars, how many cars?"
- Short sessions on several days beat one long one.

For "How many left?":

- When the numbers pulse after a right answer, say it: **"5, take away 2, leaves 3."** Later, when he is
  fluent: "5 minus 2 is 3." Now and then say the pair: "3 and 2 make 5, so 5 take away 2 leaves 3."
- Ask **"how many are left?"** before he answers, and **"how did you know?"** after.
- Ask **"what if one more went away?"**
- If he answers with the number he took away, the word "left" is the whole lesson. Point at the tray and
  ask again.
- Do it on his fingers too: five fingers up, fold two down.
- Away from the iPad, tiny stories of leaving and eating: "you have 5 grapes and you eat 2", "5 birds on
  the wire, 2 fly away", and "you eat all 3, how many are left? None!"

For "How many altogether?" (the number of plates always comes first):

- When the numbers pulse after a right answer, say it on the three beats: **"3 plates. 2 on each. 6
  strawberries."** Now and then: "2 and 2 and 2 make 6."
- Before he answers, ask **"how many plates? how many on each?"** After a sum, ask **"what if one more
  plate came?"**
- When he answers those two questions without a slip: **"3 groups of 2 make 6."** Point at the `×`: "this
  sign says groups of".
- When he answers a shuffled sum before tapping a plate: "3 twos are 6." Weeks later, the school word:
  "you tapped 3 times. 3 times 2 is 6."
- Never "3 plus 2", "times makes it bigger" or "tables".
- If 2 × 3 comes right after 3 × 2 and he says "the same!", ask **"is it the same picture?"**
- Away from the iPad: socks in pairs, wheels on cars, legs on chairs, fingers on hands, each with "how
  many on each?".

Before the first session, and again after two or three weeks, do the five-minute check with real blocks
and cups (or plates) from "Step zero" in the plan of that game. What he does differently is the only real
evidence that the app taught him anything.

## What to watch for

The lists are in [PLAN.md](PLAN.md), [PLAN-SUBTRACTION.md](PLAN-SUBTRACTION.md) and
[PLAN-MULTIPLICATION.md](PLAN-MULTIPLICATION.md). The most useful ones at the start: does he count aloud
or tap and guess, does he answer before moving anything, and does he touch the objects on the tray to
count them? In "How many left?": does he answer with the number taken away, does he stop by himself or
only when the places are full, and does a car ever leave when he only meant to count it? In "How many
altogether?": does he answer 5 for `3 × 2` (he read the `×` as `+`), does he mix up the plates and how
many on each, and does he count by ones or say "2, 4, 6"?

## Number words in your own voice (optional)

The app uses notes, not a computer voice. If he often plays alone, record "one" to "ten" on a phone and
put the ten files in a `sounds/` folder next to `index.html`, named `1.m4a` to `10.m4a` (`.mp3` and `.wav`
work as well). The app then says the new total on every landing in Play, and counts aloud in the numbered
count after a second miss. It never counts his own hops in "How many?", because that would do the
thinking for him.

A version that spoke with the device's own voice was tried and switched off. The code is still there
behind `const VOICE = false;` in `index.html`, with no setting on the screen.

## Changing the objects

The objects are emoji pairs at the top of the script in `index.html` (`SETS`). Put what he loves first.
A new pair comes after every trophy. Keep the pairs red and blue or red and yellow, never red and green.

The food on the plates of ✖️ is the list right below it (`FOODS`): strawberries, oranges, apples, one
kind and one colour at a time. A new food comes after a trophy won in ✖️. Pick food with no parts he
could count: a cookie has chocolate chips, cherries come as a pair, grapes as a bunch.

## Running it

It is a single `index.html` with no build step. Any static web server works:

```bash
python3 -m http.server 8137
```

Then open `http://localhost:8137`. On the iPad, host the folder on any HTTPS site (GitHub Pages, for
example), open it in Safari, and use Share, then Add to Home Screen. It then opens full screen and works
without internet. On a phone it is played in landscape.
