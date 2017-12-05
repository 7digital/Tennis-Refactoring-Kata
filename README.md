# Tennis Refactoring Kata

## Goal

The aim of this Kata is to refactor the code into a state that you would be happy leaving for your peers (or your future self!) to work on.

## Considerations

* We're looking for incremental improvements, so commit as often as you can. 
* Use the tests to provide feedback on your changes.
* Ask yourself:
  * Is the code readable?
  * Does the code express intent well?
  * Is there any obscure logic that could be simplified?

## Scope

We're only looking for refactorings here. The overall behaviour of the code should not change. However, you are permitted to change the public interface if you deem it necessary.

## Tennis Scoring

To help you understand the domain context of the code, here are the general rules of Tennis:

1. A game is won by the first player to have won at least four points in total and at least two points more than the opponent.
2. The running score of each game is described in a manner peculiar to tennis: scores from zero to three points are described as "Love", "Fifteen", "Thirty", and "Forty" respectively.
3. If at least three points have been scored by each player, and the scores are equal, the score is "Deuce".
4. If at least three points have been scored by each side and a player has one more point than his opponent, the score of the game is "Advantage" for the player in the lead.
