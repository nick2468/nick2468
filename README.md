## Software by Nick Walker

I design and build software in Australia. Most of it is data tooling. The rest is
personal and educational projects: games, puzzles and tools for everyday jobs.

Every app below is shown with screenshots at **[nick2468.github.io](https://nick2468.github.io)**.
Each one is marked **open source** (MIT licence, fork and build it) or **copyright**
(you can use it, the source is mine).

### What is here

**[DataCrafter](https://www.datacrafter.net)** - copyright - a data engineering
platform: workflows, data models, classifiers and reports over many data sources at
once, with a desktop client, a web client and an Excel add-in. The
[releases](https://github.com/nick2468/DataCrafter-releases) are public; the source is not.

**[Conquest](https://github.com/nick2468/Conquest)** - open source - a turn-based territory
game for the iPad and the web. Three hand-drawn maps, eight computer
opponents, and it plays with the network off. The rules engine touches no
browser, no clock and no hidden random numbers, so the same code runs in the
game, in the tests, in a self-play tuner and on a server.
[Play it](https://conquest.datacrafter.net).

**[Tabiya](https://github.com/nick2468/Tabiya)** - open source - a desktop trainer for chess
opening repertoires. Ten courses: study a line and why each move is played,
drill it back from memory on a schedule, then play it against an engine
steered into the lines you have studied. Every line the notes name is played
on a board by a checker, which is how a note that recommends an illegal move
gets caught before a reader trusts it.
[Download it](https://github.com/nick2468/Tabiya/releases/latest).

**[Tabiya Player](https://github.com/nick2468/TabiyaPlayer)** - open source - Tabiya's
companion: a no-frills chess game against Stockfish, with a review afterwards
that names every slip and the move the engine preferred. The review is handed
the numbers the evaluation bar already worked out during the game, so you are
judged by exactly what you were watching, and a position the bar called level
cannot turn into a blunder afterwards because a later search happened to see
further.
[Download it](https://github.com/nick2468/TabiyaPlayer/releases/latest).

**[PDFluffer](https://github.com/nick2468/pdfluffer)** - open source - a PDF reader
and editor for Windows with no ads, no account, no nag screens and no network. Read in
tabs, fill forms, sign, tidy pages, flatten a signed form, and make a scanned PDF
searchable with the OCR built into Windows. The same PDF engine as Firefox, inside a
small Windows app.
[Download it](https://github.com/nick2468/pdfluffer/releases/latest).

**[Cuber](https://github.com/nick2468/Cuber)** - open source - a Rubik's Cube solver
for Windows that teaches as it solves, built from a screen my son drew on paper. Paint
your cube's colours on to the cube on the screen, press Solve, and follow the moves
while the cube on screen turns with you. Three methods: a quick twenty-move answer, the
fewest moves the solver can find, and the beginner method every guide teaches, in seven
named stages so you learn it rather than copy it.
[Download it](https://github.com/nick2468/Cuber/releases/latest).

**[jcc](https://github.com/nick2468/jcc)** - open source - a small C compiler written in
Java.

### About the downloads

The Tabiya, Tabiya Player and Cuber installers are signed with a code signing
certificate, so Windows names the publisher as **Open Source Developer Nicholas
Walker**. Windows SmartScreen may still warn about a new release for a while, until
it builds up a reputation.

The PDFluffer installer is not signed yet, so Windows will warn you that the
publisher is unknown and ask whether you want to continue. That prompt is expected and says nothing about the file beyond
the fact that it is not signed. Where the source is public you are welcome to
read it, or build it yourself, rather than take my word for it.

More on the way.
