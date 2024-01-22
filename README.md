# group4_project4_cs3750
Grid word finder (boggle)
Made a change in README.md from within branch 'Ryan'
Made a 2nd change in README.md from within branch 'Ryan'

a multiplayer player asynchronous game. 

The game itself organizes random letters on a grid like, similar to this:


R	A	M	F
C	E	K	O
T	H	V	U
S	B	A	D
All players see the same grid.  When the game starts, both players can find words within the grid.  A word can be formed by using a sequence of adjacent/diagonal letters, no one square being used more than once in a word.  For example, "THEM" is a valid word in this grid, but "HAH" is not. 

The grid should be selected so that vowels make up 6 or 7 squares, and consonants make up the remaining.  If you want to tweak your letters so that more common letters show up more than others (such as T showing up more than Q), feel free to do so, but it is not required. 

Words should be compared server side against an already existing list of valid dictionary words before accepted.

As the user types a word, the UI should signify if the current word is valid or not valid (such as gray = not valid, black = valid). The validity of the word is determined if it is both on the board and in a dictionary file.

When a user submits a word, that player's points are increased. That user should also see a list of all words he or she has correctly chosen.

During game play, all players should see all other player current score totals. They do not see what other words players have found.

No word can be used twice (even if it shows up twice in different areas on the grid)

Words must be at least 3 letters long

How words are scored :
3 letters - 1 point
4 letters - 2 points
5 letters - 4 points
6 letters - 7 points
7 letters - 11 points
8 letters - 16 points
9+ letters - 22 points

Game Completion:

The game ends after 60 seconds.

At the end of the game, each player should see a results screen.  The screen lists for each player all words correctly found, as well as that player's total score.  The winner is displayed.  Players can choose to start a new game if desired.

Prior to Game Start:

Players gather into a virtual room. Players choose their name and submit a button when finished. When all players in a room select they are ready to start, the game counts down three seconds, then starts.

Optional: Multiple rooms can be implemented in case different gaming groups are requested.

Optional: The game should be functional on a desktop web browser or a mobile web browser.  If you can't publish it to test on a web browser, you can use use tools which resize a PC browser's resolution common to mobile devices.

More details will be forthcoming as students require more requirements. Login functionality and user accounts *may* be required as I see how the project progresses.