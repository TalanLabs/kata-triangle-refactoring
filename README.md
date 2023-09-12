# Tennis

Tennis has a rather quirky scoring system, and to newcomers it can be a little difficult to keep track of.
The tennis society has contracted you to build a scoreboard to display the current score during tennis games.

You can read more about Tennis scores on [wikipedia](https://fr.wikipedia.org/wiki/Tennis#:~:text=Pour%20gagner%20une%20manche%2C%20il,au%20bout%20de%20dix%20jeux).) which is summarized below:

A game is won by the first player to have won at least four points in total and at least two points more than the opponent.

1. The running score of each game is described in a manner peculiar to tennis: scores from zero to three points are described as `Love`, `Fifteen`, `Thirty`, and `Forty` respectively.

2. If at least three points have been scored by each player, and the scores are equal, the score is `Deuce`.

3. If at least three points have been scored by each side and a player has one more point than his opponent, the score of the game is `Advantage` for the player in the lead.

> You need only report the score for the current game. Sets and Matches are out of scope.

### Instruction

Your colleague has write several implementation of the `TennisGame`. He said the job his done, because all test pass.

Each implementation have two methods `wonPoint` and `getScore`. You cannot change the signature of this method.

Your job is to review the code of your colleague, and propose the refactoring you may judge neceessary.

There is a deliberate error in several of the implementations - the player names are hard-coded to `player1` and `player2`.
After you refactor, you may want to fix this problem and add suitable test cases to prove your fix works.
