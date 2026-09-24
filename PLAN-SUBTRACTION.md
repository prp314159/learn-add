# How many left? A plan for subtraction

He is 5, comfortable with addition on the tray, and has asked for subtraction himself. This plan adds it.
It is written to be read on its own. The addition app and the reasoning behind it are in [PLAN.md](PLAN.md)
and [README.md](README.md); the little a reader needs from them is repeated below.

The recommendation in one line: **subtraction becomes a third game on the same screen, "How many left?",
not a new app.** One colour of objects, the whole on the tray, some of them hop off, he taps how many are
left.

## The app as it is

- One screen. A wooden tray of ten places in two rows of five (Level A shows one row). Two coloured groups
  at the top, a number sentence above them, a row of number buttons below the tray.
- ✋ **Play:** no questions. He taps objects out of two boxes onto the tray and off again. The sentence
  follows the tray live (`3 + 2 = 5`).
- 👀 **How many?:** the app deals two groups. He moves them onto the tray one tap at a time if he wants
  to, or answers straight away, and the groups slide onto the tray as the proof. After a miss, a slow
  bounce of the objects with notes only, after a second miss with numbers. A right answer reads the
  sentence back: each numeral pulses with its group. Five stars win a trophy.
- A parent dial (press and hold) picks Level A (totals up to 5) or Level B (6 to 10).
- Rules the app lives by: things first, symbols last. One tap, one thing, one count. The app never does
  the thinking for him (numbers on the objects are the last step of help, never the default). Notes, not a
  voice. Every group he can see is a true amount. No timer, no lives, no reading.

## Same app, a third game

Why not a new app:

- **Subtraction is addition undone, and he should see that** on the same tray with the same cars: 3 and 2
  make 5, so 5 take away 2 leaves 3. On a separate page it becomes a different world with a different
  picture, and the link is lost.
- **Almost everything carries over:** the tray, the hops, the tidy, the notes, the two-step help, the
  read-back, stars, trophy, the dial, the phone layout, the offline files. A copy would be 860 lines that
  then drift apart.
- **Simpler for him.** One icon on the iPad and one new button inside it, which he chooses himself.
- **Play needs no change.** Tapping objects off the tray is already there. Its sentence describes the tray,
  so it stays an addition sentence.

What it costs: a third icon. The addition plan allowed four; Quick look can still be the fourth, and Make 5
can wait or become a dial stage. And it needs care: the new game is its own block of code, and the two
existing games keep theirs.

The case for a separate app, for fairness: a new app is a small event for him, each app stays tiny, and
addition cannot be broken by accident. None of that outweighs seeing the two operations on one tray.

## Step zero: five minutes with real objects

Before any code. Blocks and a cup.

1. **Visible:** put out 5 blocks. Before he touches them, ask him to predict: "if you take 2 away, how many
   will be left?" Then "take 2 away", and ask both questions, in this order: "how many did you take away?"
   and "how many are left?" Then 8 blocks, take 3, the same way. Watch: does he predict without counting,
   and is the prediction right? Does he take exactly 2? Does he keep the two questions apart, or give the
   same number for both? Does he count the rest from 1, or just know? Predicting without counting is the
   clearest sign of a child who is past counting everything, and it separates the two starting levels
   more sharply than watching how he counts afterwards. Mixing up the two questions is the most common
   error at this age, and asking both shows in a minute whether he separates them.
2. **All gone:** 3 blocks. "Take all 3 away. How many are left?" Does he say "none" or "zero" happily, or is
   he puzzled? This decides where "all gone" sits in the first pass (see "Which sums").
3. **Covered:** 6 blocks go under the cup while he watches. 2 come out and lie beside it. "How many are
   still under the cup?" Can he count back ("6... 5, 4"), or does he know? Most 5 year olds cannot yet. A
   before-picture: this is what the lid (below) is for.
4. **Missing part:** 5 blocks, he watches. The cup covers some, 3 are showing. "How many are under the
   cup?" A before-picture for the missing part.
5. **How many more:** a row of 5 and a row of 3, side by side. "How many more are here?" A before-picture;
   comparing is a later stage.

What the first two checks decide:

- **Takes exactly 2, keeps the two questions apart, counts the rest from 1, and is sure:** build as
  written, start at Level A, expect him to move to Level B within a session or two. The waiting places
  (below) will not need to stop him, so "No places" (under "Next") comes early.
- **Gives the number he took away as the answer, answers with the whole, or loses track of how many to
  take:** Level A as written. The waiting places are the part that matters most for him.
- **Predicts "3" before touching anything, and "5" for 8 take away 3:** start at Level B, and the lid
  comes early. A right answer after he has counted the blocks that would be left is not the same thing:
  that is Level A, moving on quickly.
- **Happy with "none":** the first "all gone" (3−3) comes right after "take away one", so he meets the `0`
  button early. **Puzzled by it:** it moves to after "take away two", once the act itself is familiar.
  Either way zero is in the first version: the empty tray is the one place where zero is something he can
  see.

Repeat step zero after two or three weeks of play. What he does differently is the only real evidence.

## The one big idea

Subtraction is **taking some away from a group and finding out how many are left**. He should take them
away with his own finger, many times, before the sign matters.

Two things make this more than "count what is left":

- **The whole stays in sight, in two parts.** The taken-away cars do not vanish. They sit at the top, a
  little faded. He sees 5 as "3 on the tray and 2 gone": the same picture he already knows from
  `3 + 2 = 5`. That is what makes subtraction the undoing of addition, and it is the root of the missing
  part (`3 + ? = 5`) later.
- **The whole comes first.** The 5 is on the tray, a real amount, before anything leaves. The sentence is
  read in the order things happen: 5, take away 2, leaves 3.

## The scene, and one sum from start to finish

```
        5          −          2          =     ?
                          ◌   ◌                  two waiting places, under the 2

     ┌────┬────┬────┬────┬────┐
     │ 🚗 │ 🚗 │ 🚗 │ 🚗 │ 🚗 │       the whole, on the tray
     └────┴────┴────┴────┴────┘

   0    1    2    3    4    5                     tap how many are left
```

1. **Here are 5.** Five red cars appear under the `5` and slide onto the tray as one group, the way the
   proof moves in "How many?". The sentence shows just `5`, and the number row is faded and does nothing
   yet. Nothing is counted for him: no notes, no numbers. He can touch the cars to count them if he wants
   to (a wiggle and a note, as in "How many?").
2. **The question.** A second and a half after the whole has landed, `− 2 = ?` pops into the sentence and
   two empty dashed places pop in under the `2`, one after the other, with a tok each. Two places, two
   must go. The number row wakes up. The question waits for him: every touch on a car during the pause
   restarts it, so he can count the whole in peace and a car never leaves mid-count. The arrival is loud on
   purpose, because from this moment a touch on a car means something new. That is the one place where
   the same touch changes its meaning, from counting to taking away, and it is the biggest risk in the
   design: the first sessions are its test, and "What to watch for" has the sign that it is not working and
   the fallback. The second and a half is a guess, like the two seconds of Quick look in the addition plan,
   to be tuned by watching him.
3. **He takes them away.** He taps a car on the tray and it hops up into a place. Each hop plays the note
   of the new count in the places (1, then 2): the notes count what he is counting, the two he takes
   away, and they rise with the tok, tok that announced the places. The tray closes the gap behind it, so
   the rows of 5 stay true.
   Three taps, one rule: **a car only goes where there is a place for it, and a car with nowhere to go is
   counted.**
   - A car on the tray, places still empty: it hops up into the next place.
   - A car on the tray, places full: touching is counting, as in "How many?": a wiggle and the next note
     up, no number.
   - A car in a place: it hops back onto the tray, and plays the tray's new count (4). This is undo. He
     took one too many, or changed his mind, and it costs nothing. It is also the flip in miniature, under his own
     finger: the same car goes and comes back.
4. **He answers whenever he likes**, even before taking anything away. If places are still empty, the
   proof fills them: the cars that must go slide up into the places together, with one slide sound, the way
   the proof moves in addition. His taps move cars one at a time; the app moves groups.
5. **Right:** the `?` becomes `3`, and the read-back follows: `5` pulses with all five cars (the faded ones
   brighten for that beat), `2` with the gone ones, `3` with the tray. The parent says "5, take away 2,
   leaves 3."
   **The flip**, only when this sum was the second of an "other part" pair: the gone cars slide back onto
   the tray, the sentence turns round into `3 + 2 = 5`, and a quick read-back of the addition follows,
   `3` with the three, `2` with the two that came back, `5` with the full tray. Two seconds that show
   subtraction undoing addition, at the moment the two parts have just swapped roles. The parent says
   "and 3 and 2 make 5."
   Then a star.
6. **First miss:** a soft boop, no buzzer, no red cross. Any places still empty get filled, then the cars
   left on the tray bounce one at a time with notes only. He counts along and tries again.
   **Second miss:** the same bounce with numbers (1, 2, 3), ending in one big `3` over the tray. A sum
   that needed the numbers comes back two or three sums later, as in addition.
   **All gone** (5 take away 5): there is nothing left to bounce. After a first miss the empty places glow
   once; after a second, the big `0` sits over the empty tray. A right `0` reads back with the empty tray
   glowing for its beat.

Then the next sum. Five stars, the trophy, and the object changes as a treat, as now.

## Why this design

- **He does the taking away.** Taking away the right number is half of subtraction, and it is where young
  children most often go wrong: too many, too few, or the removed ones counted as the answer. The app could
  remove the cars itself and leave him only the counting, but then the act he is supposed to learn happens
  to him. The waiting places give him the number to take away as an amount he can see, with nothing to
  read.
- **The places are a scaffold, and the plan says so.** They stop him at two, so he never has to read the
  `2` and decide when to stop. That is right for a first version, and it is what catches the child who
  taps until something stops him. But he already reads numerals well (he reads a clock with minutes), so
  the scaffold may not be needed for long. "No places" (under "Next") takes it away, and it is an early
  stage to build.
- **One colour.** The whole is one group. Colouring the two that must go would pick them for him and show
  the answer before anything happens. That is crossing out, a fine method on paper later, but not the act.
  Place and brightness tell the parts apart, not colour, and the numerals follow the same rule: the `5`
  and the `3` are in the object's colour, the `2` is the same colour faded, like the cars it describes.
  The object still changes after every trophy.
- **Faded, not gone.** The taken-away cars are the same cars, a little faded and smaller. If they vanished
  (eaten, driven off), the `2` in the sentence would describe nothing on the screen, and the rule that every
  visible number has its group would break. A child who counts everything may count the faded ones too.
  Real take-away has the same risk, and children manage because they moved the things themselves. If it
  happens, the parent's "how many are left on the tray?" is the fix, not a change to the design. A hungry
  animal that eats them is a good treat for later, once the idea is solid, and only if the game starts to
  feel like a chore.
- **The tray pays off.** 7 take away 2: the two on the bottom row leave, the full row of 5 is what is
  left, and he can see it without counting. 10 take away 5: a whole row goes. These sums come early in
  Level B on purpose.
- **The sentence always starts with the whole.** `5 − 2`, never `2 − 5`. The whole is what is on the tray,
  so the order of the sentence is the order of what he sees. This is new: in addition the order did not
  matter, here it does. The "other part" pairs below make the point without a word.
- **Counting back is not taught here.** "5... 4, 3" is a later and fragile strategy (off-by-one errors are
  the norm at this age). Taking away and counting what is left, and seeing the two parts, is what this game
  builds. The lid (below) is where counting back and known facts get their turn. Nothing here counts down,
  not even the notes (see "Sound").
- **The proof moves a group.** When he answers without taking anything away, the cars that must go slide
  up together, never one by one. Single hops with a note each would be the act done for him, and the
  addition rule holds here too: his taps move one at a time, the app moves groups. It also keeps the quick
  answer quick.
- **The flip is in, and rare.** The whole reason for a third game on the same tray is that subtraction is
  addition undone, and the flip is the only moment that shows it: the gone cars come back, and
  `5 − 2 = 3` turns into `3 + 2 = 5`. It plays only after the second sum of an "other part" pair, when the
  two parts have just swapped roles, so it stays a small event, and it adds no tapping. The first draft
  left it for later because it lengthens a sum; it is in because it is what the shared tray is for.
- **Knowing the answer is never punished with waiting.** Answering at once, the proof and the read-back
  take three to four seconds in all.
- **Zero is in, as "all gone".** 5 take away 5 is the happiest subtraction fact, and the empty tray is
  where zero is something he can see, unlike `3 − 0` or `4 + 0`, which stay out. The `0` button sits at
  the left of the row, so the row reads like a number line. In Level A the addition row is 1 to 5 and
  this row is 0 to 5, so every button moves one place between the two games. He reads numerals, so that
  is fine, and it is on purpose: addition keeps its row without a zero.
- **Nothing else on the screen changes.** The same tray, the same number row, the same stars and dial. The
  new game is one more button, and inside it the only new things are the `−` sign, the waiting places, a
  `0` on the number row, and cars that hop up instead of down.

## The app must not do the thinking for him

| Moment | Notes | Numbers on the cars |
| --- | --- | --- |
| Here are 5 | no | no |
| The question arrives | a tok per place | no |
| He takes them away | yes: how many are now in the places (1, 2) | no |
| He puts one back | yes: how many are now on the tray | no |
| He counts the rest by touch | yes | no |
| First wrong answer | yes | no: a slow count of what is left |
| Second wrong answer | yes | **yes**: the count of what is left, then one big `3` |
| Right answer | the read-back chords | no: each numeral pulses with its group |

The help counts what is left, never the whole and never the gone ones, because "how many are left" is the
question. If he answered with the number taken away, the slow bounce of the three on the tray is exactly
the correction he needs, without a word. When nothing is left, the help is the empty tray itself: a glow,
then the big `0`.

## Sound, not voice

As in the addition app: small notes made in the browser, no audio files, no device voice. Two things are
new:

- **One rule for every hop, in both games: the note says how many are now in the place the car just
  joined.** In addition a car joins the tray and the note is the tray's count. Here a car joins the places
  and the note is their count, 1 then 2, which is what he is counting as he takes two away, and it rises
  with the tok, tok that announced the places. A car put back joins the tray again and plays the tray's
  count. The first draft played the tray's falling count (4, then 3) as the cars left, for the sound of
  fewer. It was changed for three reasons: he will say "one, two" as he takes them, and the addition app
  has taught him that the note rises with his count; the tok, tok already counts the gone amount going up;
  and "No places" (under "Next") needs him to count to 2 by himself, which rising notes support and
  falling ones fight. The falling count belongs to the lid, where counting back is the strategy.
- **The tok per place** when the question arrives. It says how many must go the way the notes say how
  many have landed: an amount in sound, without a number.

A parent's recorded number words, if the `sounds/` folder has them, play only in the numbered count after
a second miss, never on his own taps.

## The parent is part of the design

The words of subtraction ("take away", "left") are part of the idea, and the app cannot say them. For the
first sessions at least:

- During the read-back, say it: **"5, take away 2, leaves 3."** Later, when he is fluent: "5 minus 2 is 3."
- Ask **"how many are left?"** before he answers, and **"how did you know?"** after.
- Ask **"what if one more went away?"**
- Say the pair now and then: **"3 and 2 make 5, so 5 take away 2 leaves 3."**
- Do it on his fingers too: five fingers up, fold two down. The row of 5 on the tray is a hand, and finger
  subtraction is the bridge to doing it in his head.
- Away from the iPad, tell tiny stories of leaving and eating: "you have 5 grapes and you eat 2", "5 birds
  on the wire, 2 fly away", and "you eat all 3, how many are left? None!" "How many more" stories (you
  have 5, I have 3) are talk only for now.
- If he keeps answering with the number he took away, the word "left" is the whole lesson. Point at the
  tray and ask again.

## Which sums, in what order

Never random at first. One rule throughout: at least 1 is taken away. The whole may all go (that is
"all gone", and the answer is 0); nothing is ever taken away from nothing, and `3 − 0` stays out.

**Level A: the whole is 5 or fewer.** Fourteen facts in all. The first pass has twelve of them, in fifteen
sums, and the shuffle brings the other two:

1. **Take away one:** 2−1, 3−1, 4−1, 5−1. "One fewer is the number before": the link from counting to
   subtracting, as "plus one is the next number" was for addition.
2. **All gone, once:** 3−3. The whole leaves, the tray is empty, the answer is `0`. One is enough to meet
   the button: four in a row would teach only "empty tray, tap 0". Step zero's "all gone" check may move
   it after take away two.
3. **Take away two:** 3−2, 4−2, 5−2.
4. **The other part, back to back:** 5−2 then 5−3, 4−1 then 4−3, 5−1 then 5−4. The same whole on the
   tray, the other part leaves, and the two answers swap. This is subtraction's turn-around: it shows the
   two parts of a whole, and it quietly shows that the order matters (5−2 and 5−3 are not the same). The
   flip plays after the second of each pair.
5. **All gone, the full row:** 5−5, last of all. 2−2 and 4−4 come in the shuffle.

After the first pass: shuffled, never the same fact twice in a row, and an "other part" pair now and then.
The app remembers his place in the first pass, so a new session does not start again at 2−1.

**Level B: the whole is 6 to 10.** Forty facts; 27 in the first pass, each once, five or six short
sessions:

1. **Take away one and two, and one all gone, a sample only:** 7−1, 9−1, 8−2, 6−2, 6−6.
2. **Five and some more, undone:** 6−1 then 6−5, 7−2 then 7−5, 8−3 then 8−5, 9−4 then 9−5, and 10−5.
   First the extras leave and the full row stays, then the row leaves and the extras stay.
3. **Halves and near halves:** 6−3, 8−4, 7−3 then 7−4.
4. **From ten:** 10−1 then 10−9, 10−2 then 10−8, 10−3 then 10−7, 10−4 then 10−6. The full tray, the
   tens pairs undone. Last of all, 10−10: the full tray, all gone.

After the first pass, the shuffle draws from all 40 facts.

## Small steps

- **Level A:** one row on the tray, buttons 0 to 5. **Level B:** two rows, buttons 0 to 10.
- **The dial remembers a level per game.** Addition can be at B while take away starts at A, and nobody has
  to flip the dial when he switches games. Holding it changes the level of the game he is in, and its
  letter shows that level. Play has no level, so in Play the dial shows and changes the addition level,
  as it does now.
- The same five stars and the same trophy, shared across the two question games.

## Next

After watching him. In rough order of value. None of these is in the first version.

1. **No places.** The scaffold comes off. The outlines go, the `2` stands alone, and the gone cars still
   gather under it, but nothing stops him: he must read the `2` and stop himself. Too many or too few is a
   miss. First miss: the gone cars bounce with notes only, so he counts how many he took, and undo lets him
   put one back or take one more. Second miss: the numbers on the gone cars, ending in a big `2` over
   them. A dial stage, likely within weeks, since he reads numerals well. The sign that he is ready: he
   takes exactly the number every time and never needs the full places to stop him.
2. **The missing part.** `5 − ? = 3` on the tray: five places, three cars, how many gone? He can solve it
   by counting the empty places, so it is easier than the lid, and it is the bridge to `3 + ? = 5` in the
   other game. It comes before the lid because the link between the two games is the reason they share
   one tray.
3. **The lid.** The whole hops onto the tray and a lid marked `7` closes over it. Then 2 hop out from under
   it into the places. "How many are still under?" With what is left hidden, he must count back or know the
   fact. Take away 1 to 3 only. This is the one place where the notes go down: each car that comes out
   plays the count of what is still under the lid (6, then 5), because counting back is the strategy being
   learned here. First miss: the `7` pulses with its note, the gone ones bounce. Second miss: the lid lifts
   and the numbered count runs.
4. **How many more.** Two colours lined up in the two rows, red along the top, blue along the bottom, "how
   many more red?" The overhang is the answer. The second meaning of subtraction, with its own picture.
5. **Mixed.** A dial stage where the question game deals both kinds, so he has to look at the sign. The
   real test that both ideas are his.

## Tech

- A third mode, `take`, in the same `index.html`. Its own block of code next to the two games. Play and
  "How many?" keep their code, but the shared plumbing learns the new mode: the queue's idle check, the
  number row's gate, the pointing hand, the dial and what is saved all test for the mode today. The
  recount, the read-back and the sequencing chain (`nextSum`, `sumSolved`, `draw`, the pool) read the
  addition state directly today, so they take a game, a list or a set of beats as a parameter before
  take away can share them. The sequence state (his place in a pair, the comebacks, the shuffle bag) is
  per game, so nothing is lost when he switches games. Addition gets a re-test after the build.
- Reused as they are: the tray and its places, the hop, the queue (fast taps still hop one at a time), the
  tidy for one group, the touch-count, the two-step help, the read-back with different beats, stars, the
  trophy, the dial, the layout code.
- New: the deal of the whole onto the tray; the waiting places and their arrival (a short timer that every
  touch on a car restarts, and the number row inert until then); the take-away tap and its undo; the faded
  gone group and the faded `2` chip; the group slide as the proof; the sentence with a real minus sign
  (`−`, U+2212, never a hyphen: it must be as heavy as the `+`); the empty-tray help for all gone; the
  flip after the second sum of a pair.
- The number row: six buttons in Level A, eleven in Level B, `0` at the left. Level B's buttons are a
  twentieth smaller so that eleven fit across the scene. On a phone in landscape that is about 50 px,
  above the 44 pt minimum but tighter than the rest. The Level A styling keys on the level, not on a count
  of five buttons.
- The pointing hand: while places are empty it points at a car on the tray; when they are full it sweeps
  the number row, never one button.
- Remembered: his place in the first pass, per level, separate from addition, and the dial's level per game.
  The old single level becomes the addition level, and an old saved file is read as such.
- Sums: a first-pass table in the same shape as the addition one, each fact as whole and taken, and taken
  may equal the whole.
- Icon: ➖, the heavy minus sign (U+2796). It is drawn like the other two icons, it is the sign that heads
  the sentence inside, and it cannot be mistaken for the hand of Play (👋 and ✋ are the same hand at
  button size). It is a doorway, not a lesson: he taps it to choose the game, and the same sign is the
  first thing he sees inside, so the sign becomes the name of the act. A thin text `−` or `⊝` would look
  like a dash on the button; the emoji is as heavy as the other two.
- The name on the home screen stays "Learn to Add" for now.
- About 250 new lines, and edits in about eight existing functions.

## Build order

0. Step zero. Its result decides the starting level, where "all gone" sits, and how early the lid comes.
1. The scene and one sum: the deal, the question's arrival, the waiting places, the take-away taps and
   undo, the answer, the proof.
2. The help, the read-back, the flip, stars, the ordered facts including all gone, the comeback of a sum
   that needed numbers.
3. The dial per game, what is remembered, the parent card in the README, and a re-test of addition.
4. Watch him use it (list below), then adjust.
5. "Next", one item at a time, each after watching.
6. Step zero again, after two or three weeks.

## What to watch for

- Does he answer with the number taken away (2 for 5−2)? Or with the whole?
- Does he take away exactly the number, and stop? Or keep tapping until the places stop him? Stopping by
  himself is the sign for "No places".
- Does he use undo? A car that goes up and comes back is him thinking, not a mistake.
- Does he say "none" or "zero" for all gone, and find the `0` button?
- Does he count what is left from 1, or say it straight away? For which facts?
- Does he use the row of 5 (7−2 leaves the full row)? Or count from 1 every time?
- Does he count back ("5... 4, 3")? That is the sign for the lid.
- Does he say "because 3 and 2 make 5"? That is the sign that the flip has landed, and the sign for the
  missing part.
- Does a car ever leave when he only meant to count it? This is the biggest interaction risk in the
  design, and the first sessions are its test. The question waits while he touches, so it should be rare.
  If it keeps happening, the fallback is to tap a place instead of a car: a car then hops up from the
  tray, and a touch on a tray car means "count me" in both games.
- Does he still answer with the number taken away after a few sessions? Then the first-miss help gets one
  extra beat before the bounce: the `2` pulses with the gone cars, then the tray bounces. These are the 2;
  these are what is left. It is not in the first version because the help counts only what is left, on
  purpose, and the parent's "how many are left?" is the first fix.
- Does he count the faded cars at the top as well as the tray? If so, "how many are left on the tray?"
- Which cars does he take: from the right end, or anywhere? Neither is wrong; the tidy keeps the tray true.
- Does he switch between the two question games himself, or stay in one?
- After some weeks of both: does he add in the take-away game? That is the sign for the mixed stage.

## Decided

The open questions of the first draft, settled:

1. **Zero** is in from the first version, as "all gone", with a `0` button on the take-away row.
2. **He takes them away**, with the waiting places. To be revisited after watching him.
3. **The icon** is ➖.
4. **The name** stays "Learn to Add".
5. **The flip** is in the first version, only after the second sum of an "other part" pair.
6. **The notes** count the group a car joins: the places as he takes away, the tray as he puts one back.
   Nothing counts down until the lid.
7. **All gone** appears twice in the first pass of Level A (3−3 early, 5−5 last), not four times.
