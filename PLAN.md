# Learn to Add: plan

A one-page app that teaches a 5 year old what addition *is*. It is its own project: every choice below is
made for addition, not copied from the clock app. Addition only for now. Subtraction comes later on the
same screen.

## Step zero: five minutes with real objects

Before any code. He already reads a clock with minutes, so the risk is an app that is too easy, not too hard.

1. **Visible:** put out 3 blocks and 2 blocks: "how many altogether?" Then try 6 and 3.
2. **Covered:** let him watch 4 blocks go under a cup, put 2 beside it: "how many altogether?"
3. **Both covered:** he watches 2 blocks go under one cup and 6 under another: "how many altogether?" If
   he can do it at all, which number does he start from?
4. **Quick look:** lay 7 blocks under a cloth as a row of 5 and 2 more. Lift the cloth for two seconds:
   "how many?"

Watch *how* he finds out. The first two checks pick the starting point:

- **Counts everything from 1, and wants to lift the cup:** build the plan as written, starting at Level A.
- **Counts on when he can see the blocks, but is stuck with the cup:** start at Level B, and build
  "more arrive" and the lid straight after "How many?".
- **Says "4... 5, 6" with the cup, or just knows:** start at Level B, and the lid is the heart of the
  first version. "How many?" with both groups visible is only the warm-up.

The other two checks are mostly a "before" picture:

- **Both covered:** many 5 year olds cannot do this yet, or they start from the first number whatever
  its size. Starting from the 6 is what the baskets (below) are for.
- **Quick look:** unless he has met rows of 5 before, he will guess or want to count. That is what
  Quick look (below) is for, and it gets built early either way.

If the counting parts are easy for him, the first version still has three new things to teach: the `+` and
`=` signs, the rows of 5, and turn-arounds. Counting practice is then not the point.

**Repeat step zero after two or three weeks of play.** What he does differently with the cups and the
cloth is the only real evidence that the app taught him anything.

## The one big idea

Addition is **putting two groups together and finding out how many there are now**.
The child should do exactly that with their own finger, many times, before the symbols matter.
So the whole app is one scene (drawn here with counters; "apples" below means whatever he loves):

```
        3          +          2          =     ?
     🔴 🔴 🔴                🟡 🟡

     ┌────┬────┬────┬────┬────┐
     │    │    │    │    │    │      the tray: 10 places,
     ├────┼────┼────┼────┼────┤      two rows of 5 (like two hands)
     │    │    │    │    │    │
     └────┴────┴────┴────┴────┘

      1    2    3    4    5    6    7    8    9    10       tap the answer
```

1. Two small groups wait at the top: red apples and yellow apples.
2. The child taps an apple and it hops to the next free place on the tray. One tap, one apple, one count.
3. Each landing plays the next note up a scale.
4. The child taps "how many" on the number row. They may do this at any moment, even before moving
   a single apple.
5. The apples keep their colour on the tray, so the 3 and the 2 stay visible inside the 5.

## Why this design

- **Things first, symbols last.** At 5, `3 + 2 = 5` means nothing on its own. The number sentence is a
  *label* for what the child just did with the apples. It is never the starting point.
- **"Count them all" is the natural first strategy** at this age. The app makes it physical instead of
  skipping ahead to memorised facts.
- **The tray is a tool, not a ritual.** If he already sees that 2 + 1 is 3, he can answer straight away and
  the apples come to the tray by themselves as the proof. One app then fits a child who counts everything,
  one who counts on, and one who just knows, with no levelling logic. When he starts skipping the tray, he
  is ready for the next step.
- **The proof moves groups, not single apples.** Each group slides onto the tray in one piece, first
  group first. Nine single hops in a second would be a blur. A group that moves as one shows "a group
  and a group", and treats 4 as one amount. Only his own taps move apples one by one.
- **Knowing the answer is never punished with waiting.** When he answers without the tray, the slide and
  the read-back take 3 to 4 seconds in total.
- **One tap = one thing = one number.** This is the core counting skill, and the hop enforces it. Fast taps
  are queued, so apples always hop one at a time, in rhythm. Tapping is also easier than dragging.
- **Touching is counting.** Five year olds count by touching. In "How many?" a tap on an apple that is
  already on the tray never removes it: it wiggles and plays the next note up, with no number. After a
  short pause the run of notes starts again from the bottom. Only Play lets apples hop off the tray.
- **The tray is a ten-frame in disguise.** It fills left to right, top row first. A full row is 5, so 7
  always sits there as "5 and 2". The tray only makes that visible. He starts to use it when there is no
  time to count, which is what Quick look (below) is for. The rows match his two hands, so real fingers
  can follow along (finger use is good at this age, not a crutch). The groups at the top use the same
  shape (a row of 5, then the rest), so 7 looks the same everywhere.
- **The number row is not an answer key.** The buttons never sit directly under the tray cells (different
  size and spacing). Otherwise the last apple points at the right button. The row is always one line. It
  never wraps into two rows of five, because that would mirror the tray. Ten 60px buttons do not fit
  across a phone held upright, so on a phone the app is played in landscape.
- **Colours stay, and get tidied.** He may tap apples in any order. If the colours ended up mixed, one
  short "tidy" animation slides them into first group, then second group, once all have landed. If they
  are already in order, nothing moves. The parts stay visible inside the whole, and he sees that moving
  things around does not change how many there are. Each numeral in the sentence takes the colour of its
  group.
- **Red and yellow (or red and blue), never red and green.** The whole design depends on telling the two
  colours apart, and red-green colour blindness is common in boys and rarely known at 5.
- **Plain, same-kind objects.** Busy or mixed objects pull attention away from the quantity. One kind of
  thing per sum. The object can change between rounds as a treat, never inside one sum.
- **No timer, no lives, no reading needed.** Icons and a short demo animation (a pointing hand) explain
  what to do.

## The app must not do the thinking for him

If a big number pops on every landing, he can win by matching the last number he saw. No adding needed.
So numbers on the apples are the last step of the help, never the default:

| Moment | Notes | Numbers on the apples |
| --- | --- | --- |
| Play | yes | no: the total in the sentence pulses with every landing |
| How many?, while he moves apples | yes | no: he counts himself |
| First wrong answer | yes | no: a slow recount he counts along with |
| Second wrong answer | yes | **yes**: the full count |
| Right answer | yes | no: the read-back pulses each numeral with its group |

- **First miss: a nudge, not the answer.** No buzzer, no red cross, just a soft boop. Any apples still at
  the top slide onto the tray as groups, then all of them bounce slowly one at a time with notes only. He
  counts along and tries again.
- **Second miss: show how to find out.** The same bounce, now with the numbers (1, 2, 3, 4, 5). He tries again.
- **Guessing must stay slower than counting.** A wrong try costs nothing, so time is the only thing that
  makes counting the better deal. The recount is slow: about one apple per second up to 5, quicker for
  bigger totals, and never more than about 6 seconds in all. The number row does nothing while it runs,
  and wrong buttons are never greyed out: crossing numbers off rewards guessing.
- **A sum that needed the numbers comes back** two or three sums later, so he gets to solve it by himself.
- **The last number means all of them.** Numbers on single apples always fade. Every numbered count ends
  with one big `5` over the whole tray. Otherwise "5" can look like the name of the fifth apple. Play
  shows no numbers on apples at all: its tray keeps regrouping by colour, so a `5` that popped on a
  landing apple could end up sitting in place 3. The total in the sentence (`= 5`) pulses instead.
- **Right answer reads the sentence back.** About two seconds: the `3` pulses together with the red
  apples, then the `2` with the yellow ones, then the `5` with the whole tray. This is the one place where
  the symbols get tied to the things, so it happens every time.
- **A solved sum always earns its star**, even after a miss. A wrong try never costs him anything.

## Sound, not voice

- Small synthesised sounds made in the browser (no audio files): a note per count, a happy chord for a
  right answer, a soft "boop" for try again.
- The scale has five notes (C D E G A) and then repeats one octave higher. The bottom row of the tray
  sounds like the top row again, so "6 is 5 and 1" can be heard as well as seen.
- The child counts aloud themself. That beats any voice the app could play.
- Number words are the heart of counting, and notes do not carry them. If he often plays alone: a parent
  records "one" to "ten" on a phone and drops the ten files into a `sounds/` folder. If they exist, the
  app plays them where it would also show a number: in Play for the new total on every landing, and in
  the numbered count after a second miss. Never on his own hops in "How many?", because a spoken count
  does the thinking for him just as a popping number would. No recording feature inside the app.

## The parent is part of the design

The words of addition ("and", "altogether", "makes") are part of the idea, and the app cannot say them.
So the README carries a small parent card, for the first sessions at least:

- During the read-back, say it: "3 and 2 make 5."
- Ask "how did you know?" Any answer is good. Explaining is where the learning settles.
- Ask "what if one more came?"
- Away from the iPad, tell tiny stories of both kinds. Some more come: "you have 3 cars, I give you 2
  more." Two groups together: "3 red cars and 2 blue cars, how many cars?" The app keeps its objects
  plain on purpose, so the stories are where adding gets its meaning.

## Two games first

| Game | What happens |
| --- | --- |
| ✋ **Play** | No questions. Tap apples out of two boxes onto the tray, and tap them off again. The sentence changes live: `3 + 2 = 5`. A full row of 5 sparkles, a full tray of 10 gets a fanfare, and one button tumbles everything off. |
| 👀 **How many?** | The app deals two groups. He finds the total any way he likes and taps it. The `?` stays hidden until he is right. |

Play details: the tray always keeps itself tidy (no holes, colours together). A new apple lands in the
next free place and then slides into its colour group. When an apple is tapped off, the rest slide along
and the rows of 5 stay true. With only one colour on the tray the sentence shows
just `3`, never `3 + 0`. When the tray is full, a tapped box just wobbles.

**Every group he can see is a true amount.** Each colour comes out of a closed box with one apple peeking
out, and the boxes never run out, so any two groups up to a total of 10 can be built. A supply must never
look like a group he could count: the first build drew each supply as a heap of three, with the live
numeral right above it, so the screen showed a `2` over a picture of three. For the same reason the
sentence in Play sits right above the tray. Its numbers describe the tray, not the boxes.

Five stars win a trophy, with confetti. The trophy is also a natural end of a session: about five sums,
a few minutes. Short sessions on several days beat one long one.

**He never sees more than four icons.** Play and "How many?" first, Quick look and Make 5 later (see
"Next"). Everything else that comes later is a stage of "How many?", set with the parent dial.

## Which sums, in what order

Never random. Level A has only ten sums, so the first pass is ordered by hand:

1. **Plus one:** 1 + 1, 2 + 1, 3 + 1, 4 + 1. "Adding one is the next number" is the idea that links
   counting to adding.
2. **Turn-arounds, back to back:** 3 + 1 then 1 + 3, 2 + 1 then 1 + 2, 4 + 1 then 1 + 4.
3. **Plus two and the double:** 2 + 2, 3 + 2 then 2 + 3.

- **Inside a turn-around pair the colour stays with the quantity:** 3 red + 1 yellow, then 1 yellow + 3
  red. The tidied tray is then the mirror image of the one before, and he sees the same apples in swapped
  order. Outside a pair, the first group is red.
- After the first pass: shuffled, never the same sum twice in a row, and a turn-around pair now and then.
- The app remembers his place in the first pass, so a new session does not start again at 1 + 1.
- Level B is where he will probably spend most of his time, so its first pass is ordered by hand as
  well. About 30 sums, six short sessions:
  1. **Plus one and plus two, a sample only:** 6 + 1, 8 + 1 then 1 + 8, 7 + 2 then 2 + 7. All of them
     with every turn-around would be 30 sums, six sessions, before anything new appears.
  2. **Five and some more:** 5 + 1 to 5 + 5, where the full row pays off.
  3. **Doubles, each followed by its near double:** 3 + 3 then 3 + 4, 4 + 4 then 4 + 5.
  4. **Tens pairs:** 9 + 1, 8 + 2, 7 + 3, 6 + 4. Each one fills the tray, so a right answer gets the
     full-tray fanfare.
  5. That leaves only 3 + 6.

  From step 2 on, each sum is followed by its turn-around. After the first pass, the shuffle draws from
  the totals 6 to 10.

## Small steps

- **Level A:** totals up to 5. The tray shows only its top row, number row shows 1 to 5.
- **Level B:** totals up to 10.
- One dial for the parent, pressed and held so that he does not flip it by accident. The first version
  has two positions: A and B. The later stages of "How many?" (see "Next") become further positions on
  the same dial: A, B, more arrive, lid, baskets. They only make sense with totals up to 10, so there is
  no second switch. No automatic levelling in the first version.
- No zero at first. `4 + 0` is a strange idea at this age and can wait.

## Next: two strands

The two strands are built in turns, not one after the other. Step zero may pull the first step of either
into the first version.

**Counting strand: from counting everything to counting on.** These are not new games. They are stages
of "How many?", further positions on the parent dial, so he never gets a new icon for them.

1. **Open:** the first version. Both groups are loose.
2. **More arrive:** the first group is already on the tray and shows its number. Only the second group
   hops, and the notes carry on from the first group ("4... 5, 6"). This is also the "some more come"
   story, acted out. Same sums as the lid: the bigger group is on the tray, and 1 to 3 arrive.
3. **The lid** (below): the first group is hidden on the tray.
4. **The baskets** (below): both groups are hidden.

**Seeing strand: from counting by ones to knowing.** Counting on is still counting by ones, and many
children stay there for years. What leads to known facts is seeing 5 and 10 inside a number, and
splitting a whole into parts.

1. **Quick look, one colour** (below). The cheapest thing in the plan to build: no hops, no sentence.
2. **Quick look, two colours.**
3. **Make 5**, then **Make 10** (below).

**Later:** subtraction on the same tray (apples hop *off*: "5, take away 2"; this is why the tray is
designed now), then the missing part (`3 + ? = 5`).

### The closed box: a lid, then baskets

With every apple visible, he can always fall back on counting. Adding becomes its own skill when one part
is hidden and he has to hold "4" as a number and carry on from it.

**The lid** hides the first group on the tray:

- He watches the first group hop onto the tray, then a lid marked `4` closes over those places. He saw the
  four go in, so the `4` is a real amount, not just a symbol.
- The second group is loose. Its notes carry on from where the lid ends.
- **First miss:** the `4` pulses with its note, then the loose apples bounce one at a time with notes only.
- **Second miss:** the lid opens and the full numbered count runs. The sum comes back a little later.
- **Right answer:** the lid lifts as the proof, then the usual read-back.
- **Which sums:** bigger group under the lid and a loose group of 1 to 3 (4 + 1, 6 + 2, 5 + 3). No
  turn-arounds here. With 2 under the lid and 6 loose, counting on from the 2 is the sensible move, so
  there is nothing for him to discover.
- **The lid is the gentle version, in two ways.** It spans 4 places, so he can still point at the places
  and count them from 1. And the tray shows where the loose apples land: a lid of 4 with apples in places
  5 and 6 reads as "a full row and one more", with no counting on at all. Both are fair stepping stones,
  and the second is a good strategy in its own right. The baskets close both doors.

**The baskets** hide both groups, away from the tray:

- Two baskets stand beside an empty tray. He watches 6 apples go into one and 2 into the other, and each
  basket shows its number. There is nothing to count and nothing to read off the tray.
- He has to start from one number and carry on, with fingers or in his head.
- **Which sums:** the smaller group is always 1 to 3. With both groups hidden, 4 + 5 is a different and
  much harder task.
- **Small-first sums belong here, and they stand alone** (2 + 7, never straight after 7 + 2). Only now
  does starting from the bigger group save real work: two more counts instead of seven. By this stage he
  knows that a swap gives the same answer, so a turn-around straight after its partner would be answered
  from memory. He would never feel the extra work, and nobody could see which number he starts from.
- **First miss:** the smaller basket tips its apples out beside the tray, and the bigger one keeps its
  number. What he now sees is "6, and 2 more", which shows the easy way without saying it.
- **Second miss:** both baskets tip onto the tray and the full numbered count runs. The sum comes back a
  little later.
- **Right answer:** both baskets tip onto the tray as the proof, then the usual read-back.

### Quick look

The rows of 5 only start to work for him when there is no time to count. Quick look gets its own icon.

- A cloth lies over the tray. It lifts for about two seconds, then drops again. He taps how many.
- Nothing hops and no notes play, so there is nothing to count along with. 7 has to be seen as
  "5 and 2".
- First with one colour and no sentence: amounts up to 5, then 6 to 10. Then with two colours and the
  sentence (`5 + 2`, later `4 + 3`).
- **First miss:** one more two-second look.
- **Second miss:** the cloth stays off and the help shows the way of seeing, not a count by ones, because
  counting by ones is the habit this game is there to replace. From 6 up, the full row lights up as one
  block marked `5`, then the extra apples light up, then the big `7` over the whole tray. Up to 5, the
  numbered count runs. The amount comes back a little later.
- **Right answer:** the cloth lifts as the proof. With one colour there is no sentence to read back, so
  the big numeral over the tray is enough. With two colours, the usual read-back.
- Two seconds is a first guess. Tune it by watching him: long enough to see, too short to count.

### Make 5, then Make 10

- An empty row, two boxes (as in Play). Fill it any way you like, the sentence shows `5 = 2 + 3`, then "find another
  way". Many right answers, none wrong. Make 5 gets its own icon.
- It teaches that a whole splits into parts, which is the root of subtraction, missing numbers and
  making 10. Together with Quick look, this is what turns counting into knowing.
- Writing the total first also shows that `=` means "is the same as", not "the answer comes next".
- The ways he has found stay stacked on the screen, one row under the other. The staircase (one more red,
  one fewer yellow) is where the pattern shows, and a full staircase is a natural end of the round.
- This is the natural place to meet zero: "all red" is `5 = 5 + 0`. To be decided when the game is built.
- Later the same game becomes Make 10 on the full tray.

## Tech

- A single `index.html`, plain JavaScript, no build step, emoji for the art, PWA files so it installs on
  the iPad. It also works on a phone in landscape. Held upright, the phone shows a "turn me" picture.
- Two colours of one object: a ready emoji pair (🚗 🚙, ❤️ 💛, 📕 📘) or one emoji recoloured with a CSS
  filter (to be tested on the iPad).
- Pointer events, tap targets of at least 60px, no text selection or zoom on taps.
- `localStorage` for his place in the sums and the position of the parent dial. Nothing else is stored.
- Its own folder and its own git repo. The copied `clock/` folder still carries the clock's `.git`, which
  pushes to the `learn-clock` GitHub repo, so the new app must not be built inside that copy.

## Build order

0. The check with real objects (step zero). Its result decides the starting level and how early the lid
   is built.
1. The scene and **Play**: tray, queued hops, self-tidying tray, five-note scale, live number sentence
   with a pulsing total, sparkle at 5 and fanfare at 10.
2. **How many?**: answer at any time, groups that slide in as the proof, the ordered sums, the two-step
   help, the read-back, stars, trophy.
3. The parent dial (A and B), PWA files, landscape phone layout, the parent card in the README.
4. Watch him use it (list below), then adjust. What he actually does matters more than anything in this plan.
5. "Next", taking turns between the two strands: Quick look with one colour and "more arrive", then the
   lid, Quick look with two colours, Make 5, the baskets.
6. Step zero again, after two or three weeks of play.

## What to watch for

- Does he count aloud, or tap everything and guess?
- Does he tap any number just to make the app count for him?
- Does he answer before moving the apples? For which sums? That is the sign he is ready for "more arrive"
  and the lid.
- Does he use the row of 5 ("5 and 2"), or always count from 1? Always counting from 1 means more
  Quick look.
- Does he count along the number row ("3, then 2 more")? That is a good sign, not a trick.
- Are his misses often the button next door? That is a finger slip, not a counting error, and the
  recount should then get shorter.
- Does he touch the apples on the tray to count them? Does he lose track? If so, touched apples could
  dim until the notes start again.
- With the lid: does he count the places under it, or read the answer off the rows?
- With the baskets: on a small-first sum (2 + 7), does he start from the bigger number?
- Does he look at the number sentence during the read-back?
- How long does Play hold him, and what does he do there?
- Does "How many?" start to feel like a chore? Only then give the total a reason: a hungry animal that
  eats the apples after the read-back.

## Open questions

- What does he love right now (animals, cars, sweets)? That picks the objects.
- How often will he play alone? Often means even less text on screen, and the recorded number words
  move up.
