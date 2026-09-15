# CCAR-F Drill

Self-contained practice drill for the Claude Certified Architect Foundations exam.
Original questions written against the official exam guide task statements.
Not affiliated with Anthropic.

## Running it

Open `index.html`. That is the whole application. There is no build step, no
server, no API key and no account. It works from a local double-click, from a
USB stick, or from the hosted URL below.

Live: https://aqeelkhokhar.github.io/ccarf-drill/

## Progress

Scores and missed questions are stored in the browser the drill is opened in,
which is what the Weak spots preset reads from. To carry progress to another
computer, use **Export progress** on the first machine and **Import progress**
on the second. Import merges rather than overwrites, so running it on a machine
that already has history keeps the higher of the two counts per question.

## Notes

The floating Ask button only appears when the page is opened inside the Claude
artifact runtime, which is the only place its backing call exists. Everywhere
else it stays hidden and the drill behaves normally.
