

| TEST CASES \- VAMPIRE RUNNER |  |  |  |  |  |
| :---- | :---- | :---- | :---- | :---- | :---- |
| ID | Module | Test scenario | Step | Expected Result | Priority |
| TC-MENU-001 | Menu | Verify application launches successfully  | 1.Launch the application 2\. Observe the initial screen.  | The app opens correctly | high |
| TC-MENU-002 | Menu | Verify Play button starts gameplay  | 1.Launch application 2.Tap Play  | The gameplay scene loads and the game starts automatically.  | Critical |
| TC-MENU-003 | Menu | Verify Exit button closes the application  | 1.Launch application 2.Tap Exit | The app get closed | high |
| TC-MENU-004 | Menu | Verify Play button responds to touch input  | 1.Once on the menu check the Play button play sound and animation | Play button plays the sound and animation | high |
| TC-MENU-005 | Menu | Verify Exit button responds to touch input  | 1.Once on the menu check the Exit button play sound and animation | Exit button plays the sound and animation | high |
| TC-MENU-006 | Menu | Verify main menu UI is displayed correctly  | 1\. open the main menu | Get the correct display on screen | medium |
| TC-PLAYER- 001 | Player | Verify tapping makes the player jump | 1\. On game tap on the screen | Player jump on tap | critical |
| TC-PLAYER- 002 | Player | Verify player automatically runs  | 1.Open the gameplay 2.check the player animation start | The player animation start | medium |
| TC-PLAYER- 003 | Player | Verify holding screen increases jump duration  | 1\. In game hold the jump  | The player jumps higher | critical |
| TC-PLAYER- 004 | Player | Verify releasing screen stops extended jump  | 1.In game hold jump 2.Realise the jump mid-jumping | The player stops the jump | high |
| TC-PLAYER- 005 | Player | Verify repeated jumps work correctly  | 1.In game tap repeatedly | The player jump repeatedly | critical |
| TC-PLAYER- 006 | Player | Verify player lands correctly after jumping  | 1.check the player position after jumping | The player lands on the platform | high |
| TC-PLAYER- 007 | Player | Verify player can jump over an enemy  | 1.In game tap to jump over an enemy | The player jumps over the enemy | critical |
| TC-PLAYER- 008 | Player | Verify player collision cause the Game Over | 1\. In game collide with an enemy | Game Over menu pop up | critical |
| TC-COMBAT-001  | Combat | Verify shooting button fires projectile  | 1\. Shoot a projectile | The crossbow shoots a projectile | critical |
| TC-COMBAT-002  | Combat | Verify crossbow firing animation is triggered   | 1\. shoot a projectile and check the animation | The crossbow plays the animation | medium |
| TC-COMBAT-003  | Combat | Verify projectile travels in the intended direction  | 1.Shoot the projectile and check if it goes to the right  | The crossbow shoots to the right  | high |
| TC-COMBAT-004 | Combat | Verify projectile disappears after intended interaction  | 1.Shoot projectile 2.check if it disappear at collision with enemy  | The projectile disappears at the collision with an enemy | medium |
| TC-COMBAT-005  | Combat | Verify player can shoot while running  | 1.Shoot projectile 2.check if the player keeps playing the animation while shooting | The player keeps playing the animation while shooting | medium |
| TC-COMBAT-006  | Combat | Verify player can shoot while jumping  | 1.Tap to jump 2.shoot while jumping | The player shoots while jumping | high |
| TC-COMBAT-007 | Combat | Verify repeated shooting behaves correctly  | 1.Tap for shooting multiple times | The crossbow shoots multiple times | high |
| TC-INDESTRUCTIBLE\_ENEMY-001  | Enemy | Verify indestructible enemy spawns correctly  | 1.Play until the double barrel spawns | The double barrel spawns | critical |
| TC-INDESTRUCTIBLE\_ENEMY-002 | Enemy | Verify projectile does not destroy indestructible enemy  | 1.Shoots double barrel | The double barrel do not get destroyed | high |
| TC-INDESTRUCTIBLE\_ENEMY-003 | Enemy | Verify player can avoid indestructible enemy by jumping  | 1\. Jump over the obstacle | The player jump over the double barrel | critical |
| TC-INDESTRUCTIBLE\_ENEMY-004 | Enemy | Verify collision with indestructible enemy causes game over  | 1.Collide with the double barrel | The Game over menu is shown | critical |
| TC-GROUND\_ENEMY-001 | Enemy | Verify ground enemy spawns correctly  | 1\. Play until single barrel gets spawned | The single barrel spawns | critical |
| TC-GROUND\_ENEMY-002  | Enemy | Verify projectile destroys ground enemy  | 1.Shoot the single barrel | The single barrel gets destroyed | high |
| TC-GROUND\_ENEMY-003  | Enemy | Verify player can avoid ground enemy  | 1.Jump over the single barrel | The player jumps over the single barrel | critical |
| TC-GROUND\_ENEMY-004  | Enemy | Verify ground enemy awards bonus score when destroyed  | 1.shoot the single barrel 2\. check the score gets increased when the single barrel is destroyed | The score goes up by 100 points | high |
| TC-GROUND\_ENEMY-005 | Enemy | Verify collision with ground enemy causes game over | 1.Collide with the single barrel | The Game over menu is shown | critical |
| TC-AIR\_ENEMY-001 | Enemy | Verify air enemy spawns correctly  | 1\. Play until the bat gets spawned | The bat spawns | critical |
| TC-AIR\_ENEMY-002 | Enemy | Verify projectile destroys air enemy  | 1.Shoot the the bat | The bat gets destroyed | high |
| TC-AIR\_ENEMY-003 | Enemy | Verify player can avoid air enemy  | 1\. Stay still or jump the bat | The player avoid the bat | high |
| TC-AIR\_ENEMY-004 | Enemy | Verify air enemy awards bonus score when destroyed  | 1.shoot the bat 2\. check the score gets increased when the bat is destroyed | The score goes up by 500 points | high |
| TC-AIR\_ENEMY-005 | Enemy | Verify collision with air enemy causes game over | 1.Collide with the bat | The Game over menu is shown | critical |
| TC-SCORE-001  | Score | Verify score is displayed during gameplay  | 1.Play one run 2.check the score works | The score works as expected | high |
| TC-SCORE-002  | Score | Verify score increases during gameplay  | 1.play one run 2.check the score increase | The score increase as you play | high |
| TC-SCORE-003  | Score | Verify destroying ground enemy awards bonus score  | 1.shoot ground enemy 2.check if the score increase 100 points | The score increased 100 points | high |
| TC-SCORE-004  | Score | Verify destroying air enemy awards bonus score  | 1.shoot aerial enemy 2.check if the score increase 500 points | The score increased 500 points | high |
| TC-SCORE-005  | Score | Verify score is recorded after game over  | 1.play one run 2.check the score on the game over screen | The score of the run is shown in the screen | high |
| TC-SCORE-006  | Score | Verify first completed score becomes Best Score  | 1.play first run 2.hit one enemy 3.check if the score becomes the best score | The first score became the best score | critical |
| TC-SCORE-007  | Score | Verify higher score replaces Best Score  | 1.get higher score than the previous score | The best score gets replaced | critical |
| TC-SCORE-008  | Score | Verify lower score does not replace Best Score  | 1.play one run with low score | The score do not get replace | critical |
| TC-PAUSE-001  | Pause | Verify Pause button opens pause menu   | 1.start game 2.press pause button | The pause menu opens | high |
| TC-PAUSE-002  | Pause | Verify gameplay stops while paused  | 1.start game 2.open pause menu 3.check the game is paused | On the pause menu there is no movement while open | high |
| TC-PAUSE-003  | Pause | Verify player remains frozen while paused  | 1.start game 2.open pause menu 3.check the player does not move | While the pause menu is open the player is frozen | high |
| TC-PAUSE-004  | Pause | Verify enemies remains frozen while paused  | 1.start game 2.open pause menu 3.check the enemies does not move | While the pause menu is open the enemies are frozen | high |
| TC-PAUSE-005  | Pause | Verify Resume button returns to gameplay  | 1.start game 2.open pause menu 3.press the resume button | Once pressed the game continue  | critical |
| TC-PAUSE-006  | Pause | Verify gameplay continues correctly after Resume  | 1.start game 2.open pause menu 3.press the resume button | The game continues as normal | high |
| TC-PAUSE-007  | Pause | Verify Exit button from Pause returns to main menu  | 1.start game 2.open pause menu 3.press the exit button | The game goes back to the main menu | high |
| TC-PAUSE-008  | Pause | Verify pause functionality during active gameplay interactions  | 1.start game 2.open pause menu 3.try the jump button 4.try the shoot button | The tried actions didn’t work | high |
| TC-GAMEOVER-001  | Gameover | Verify Game Over screen appears after player death  | 1.start game 2.finish the run 3.check the Gameover screen appears | The gameover screen appears | critical |
| TC-GAMEOVER-002  | Gameover | Verify final score is displayed  | 1.start game 2.finish the run 3.check the score is on the screen updated | The score of the run is on the gameover screen | high |
| TC-GAMEOVER-003  | Gameover | Verify Best Score is displayed correctly  | 1.start game 2.finish the run 3.check the best score is still the same | The best score is still the one obtained previously | high |
| TC-GAMEOVER-004  | Gameover | Verify Restart button starts a new game  | 1.start game 2.finish the run 3.press the restart button 4.check another run starts | A new run starts | high |
| TC-GAMEOVER-005  | Gameover | Verify new game resets current score  | 1.start game 2.finish the run 3.press the restart button 4.check the score restart | The score start again from 0 | high |
| TC-GAMEOVER-006  | Gameover | Verify Exit button returns to main menu  | 1.start game 2.finish the run 3.press the exit button | The button send the player to the main menu | high |
| TC-ANIM-001  | Animation | Verify player running animation plays during gameplay  | 1.start game 2.check the player start the running animation | The player is playing the animation while playing | high |
| TC-ANIM-002  | Animation | Verify player running animation loops correctly  | 1.start game 2.check the player start the running animation correctly | The animation loop correctly | high |
| TC-ANIM-003  | Animation | Verify crossbow firing animation plays when shooting  | 1.start the game 2.shoot the crossbow 3.check if its playing the animation | The crossbow plays the animation correctly | high |
| TC-ANIM-004  | Animation | Verify bat wing animation plays continuously  | 1.start the game 2.wait until a bat appears 3.check the animation on the bat | The animation plays correctly | high |
| TC-ANIM-005  | Animation | Verify ground animation loops continuously  | 1.start the game 2\. play until the ground loop | The ground loops correctly | high |
| TC-ANIM-006  | Animation | Verify animations resume correctly after pause  | 1.start game 2.open pause menu 3\. check the player animation 4.shoot and check the crossbow animation 5.check there is a loop on the ground 6.the bat keeps playing the animation | Every animation keeps working after the pause | high |
| TC-FLOW-001  | Game Flow | Verify Main Menu → Gameplay transition  | 1.open the app 2.press the play button 3.check if it goes to gameplay | The gameplay starts correctly | critical |
| TC-FLOW-002  | Game Flow | Verify Gameplay → Pause transition  | 1.start the run 2.press pause button | The pause menu opens correctly | high |
| TC-FLOW-003  | Game Flow | Verify Pause → Gameplay transition  | 1.start the run 2.press pause button 3.press continue button | The gameplay continue correctly | high |
| TC-FLOW-004  | Game Flow | Verify Gameplay → Game Over transition  | 1.start the run 2.finish the run | The GameOver menu appears correctly | critical |
| TC-FLOW-005  | Game Flow | Verify Game Over → Gameplay transition  | 1.start the run 2.finish the run 3.press restart button | The game restart a new run correctly | high |
| TC-FLOW-006  | Game Flow | Verify Game Over → Main Menu transition  | 1.start the run 2.finish the run 3.press exit button | The main menu appears on the screen correctly | high |
| TC-UI-001  | UI | Verify gameplay buttons are visible  | 1.start the run 2.check if the UI is visible | All the UI is visible  | critical |
| TC-UI-002  | UI | Verify buttons respond correctly to touch  | 1.start the run 2.check if the UI works | All the UI works correctly | critical |
| TC-UI-003  | UI | Verify score remains readable during gameplay  | 1.start the run 2.check if the score is easily readable | The score is visible and clear to read | high |
| TC-UI-004  | UI | Verify Game Over UI is displayed correctly  | 1.start the run 2.finish the run 3.check the gameover UI | The game over UI is clear and readable  | high |
| TC-UI-005  | UI | Verify Pause UI is displayed correctly  | 1.start the run 2.press pause button 3.Check the UI | The pause UI is clear and readable | high |
| TC-STAB-001  | Stability | Verify application does not crash during normal gameplay  | 1.start the run 2.play until I hit an enemy | The game works with no problem | critical |
| TC-STAB-002  | Stability | Verify extended gameplay session remains stable  | 1.start the run 2.try to play for an extended period of time | The game does not get laggy nor does any functionality degrade.  | high |
| TC-STAB-003  | Stability | Verify repeated restart cycles do not cause crashes  | 1.start the run 2.open pause menu 3.press restart button 4.repeat at least 5 times | The game restart all the times restart with no problem and the gameplay works correctly after the restarts | high |
| TC-STAB-004  | Stability | Verify repeated pause/resume cycles do not cause crashes  | 1.start the run 2.open pause menu 3.press continue button 4.repeat for 7 times | the game does not suffer for the repeat pauses  | high |
| TC-STAB-005  | Stability | Verify repeated application launches do not cause crashes  | 1.Open the app multiple times from the home screen of the phone  | The app just open one instance of the game | critical |
| TC-STAB-006  | Stability | Verify no obvious progressive performance degradation during extended gameplay  | 1.start the run 2.play for a large period of time | The game works perfectly after a large game session | high |

