# Running Sheep

An endless runner controlled with the Enter key or touch input. Open `index.html` in a browser to play.

- The sheep runs automatically and gradually accelerates.
- Press Enter or touch the game screen to jump; press or touch again in midair for a double jump.
- Touching fences, crows, or rolled-up paper scraps reduces lives and points. The game ends when lives reach zero.
- Stomping a crow defeats it without reducing lives or points.
- Stomping a crow adds 5 points and plays a crow-call sound; jumping plays a spring sound.
- Hitting a fence, crow, or pit subtracts 5 points.
- Collecting hay restores a life up to the maximum and adds 10 points.
- Crows, fences, hay, paper scraps, and pits appear at random.
- Pits can be avoided by jumping and do not affect points or the passed-obstacle count.
- Reach the goal by passing 50 fences or crows; the sheep then sleeps on a futon.
- Reaching the goal with the 100-point target displays an aurora above the sleeping sheep.
- 100 points is the target score; scores can exceed it.
- Scores can exceed 100 and remain included in the ranking.
- After the 50th fence or crow, all remaining obstacles disappear and input is locked for two seconds during the goal transition.
- The goal screen saves the score locally and displays a top-five ranking.
- Mountains use varied widths and spacing for a more natural background.
- The background changes from morning to evening as the goal approaches, and cheerful ranch music plays during the game.
- The background transitions naturally from morning through midday to evening as the goal approaches.
- Background transitions are smoothed across obstacle counts so the sky does not jump when a new obstacle is passed.
- Once speed reaches 10.0, acceleration is reduced to two-thirds of the normal rate.
- The game fills the viewport and requests landscape orientation on supported mobile browsers.
- On desktop, the game canvas is displayed at up to 80% of the viewport height.
- On mobile, the ground area is slightly larger to provide more comfortable touch space; desktop layout is unchanged.
- After 50 fences or crows have been passed, no more obstacles appear, and the sleeping sheep sound plays at the goal.
