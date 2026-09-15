

| TRACEABILITY MATRIX  |  |  |  |  |
| :---- | :---- | :---- | :---- | :---- |
| Requirement ID | Requirement | Test Case ID | Result | Bug-ID |
| REQ-MENU-001  | The application shall launch successfully and display the main menu.  | TC-MENU-001, TC-STAB-005  | PASS | \- |
| REQ-MENU-002  | The main menu shall provide a Play button.  | TC-MENU-002, TC-UI-001  | PASS | \- |
| REQ-MENU-003  | The main menu shall provide an Exit button.  | TC-MENU-003, TC-UI-001  | PASS | \- |
| REQ-MENU-004  | Selecting the Play button shall start the gameplay.  | TC-MENU-004, TC-FLOW-001  | PASS | \- |
| REQ-MENU-005  | Selecting the Exit button from the main menu shall close the application.  | TC-MENU-005  | PASS | \- |
| REQ-PLAYER-001  | The player shall automatically run during gameplay.  | TC-PLAYER-001, TC-ANIM-001  | PASS | \- |
| REQ-PLAYER-002  | The player shall be able to jump when the screen is tapped.  | TC-PLAYER-002, TC-PLAYER-005  | PASS | \- |
| REQ-PLAYER-003  | Holding the screen shall allow the player to perform a longer jump.  | TC-PLAYER-003  | PASS | \- |
| REQ-PLAYER-004 | Releasing the screen shall end the extended jump input. | TC-PLAYER-004  | PASS | \- |
| REQ-PLAYER-005 | The player shall be able to perform consecutive jumps during gameplay.  | TC-PLAYER-005  | PASS | \- |
| REQ-PLAYER-006 | The player shall correctly land after completing a jump. | TC-PLAYER-006  | PASS | \- |
| REQ-PLAYER-007 | Collision between the player and an enemy that causes damage shall result in player death.  | TC-PLAYER-008, TC-INDESTRUCTIBLE\_ENEMY-004,TC-GROUND\_ENEMY-005,TC-AIR\_ENEMY-005 | PASS | \- |
| REQ-COMBAT-001  | The  player shall be able to fire a projectile using the Shoot button. | TC-COMBAT-001  | PASS | \- |
| REQ-COMBAT-002  | A projectile shall travel in the intended direction after being fired.  | TC-COMBAT-003  | PASS | \- |
| REQ-COMBAT-003 | The crossbow firing animation shall be triggered when the player shoots.  | TC-COMBAT-002  | PASS | \- |
| REQ-COMBAT-004 | The player shall be able to shoot while running.  | TC-COMBAT-005  | PASS | \- |
| REQ-COMBAT-005 | The player shall be able to shoot while jumping.  | TC-COMBAT-006  | PASS | \- |
| REQ-COMBAT-006 | Repeated shooting inputs shall behave according to the implemented shooting mechanics without causing application errors.  | TC-COMBAT-007, TC-STAB-001  | PASS | \- |
| REQ-ENEMY-001  | The indestructible enemy shall appear during gameplay.  | TC-INDESTRUCTIBLE\_ENEMY-001  | PASS | \- |
| REQ-ENEMY-002  | The indestructible enemy shall not be destroyed by projectiles.  | TC-INDESTRUCTIBLE\_ENEMY-002 | PASS | \- |
| REQ-ENEMY-003  | The player shall be able to avoid the indestructible enemy by jumping over it.  | TC-INDESTRUCTIBLE\_ENEMY-003 | PASS | \- |
| REQ-ENEMY-004  | Collision with the indestructible enemy shall result in player death.  | TC-INDESTRUCTIBLE\_ENEMY-004 | PASS | \- |
| REQ-ENEMY-005  | The ground enemy shall appear during gameplay.  | TC-GROUND\_ENEMY-001 | PASS | \- |
| REQ-ENEMY-006  | The player shall be able to destroy the ground enemy using a projectile.  | TC-GROUND\_ENEMY-002  | PASS | \- |
| REQ-ENEMY-007  | The player shall be able to avoid the ground enemy without destroying it.  | TC-GROUND\_ENEMY-003  | PASS | \- |
| REQ-ENEMY-008  | Destroying a ground enemy shall award the corresponding bonus score.  | TC-GROUND\_ENEMY-004 | PASS | \- |
| REQ-ENEMY-009  | The air enemy shall appear during gameplay.  | TC-AIR\_ENEMY-001 | PASS | \- |
| REQ-ENEMY-010  | The player shall be able to destroy the air enemy using a projectile.  | TC-AIR\_ENEMY-002 | PASS | \- |
| REQ-ENEMY-011  | The player shall be able to avoid the air enemy without destroying it.  | TC-AIR\_ENEMY-003 | PASS | \- |
| REQ-ENEMY-012  | Destroying an air enemy shall award the corresponding bonus score.  | TC-AIR\_ENEMY-004 | PASS | \- |
| REQ-SCORE-001  | The current score shall be displayed during gameplay.  | TC-SCORE-001  | PASS | \- |
| REQ-SCORE-002  | The score shall increase according to the implemented scoring system during gameplay.  | TC-SCORE-002  | PASS | \- |
| REQ-SCORE-003  | Destroying a ground enemy shall increase the score by the defined bonus amount.  | TC-SCORE-003  | PASS | \- |
| REQ-SCORE-004  | Destroying an air enemy shall increase the score by the defined bonus amount. | TC-SCORE-004  | PASS | \- |
| REQ-SCORE-005  | The final score shall be retained when the player loses.  | TC-SCORE-005  | PASS | \- |
| REQ-SCORE-006  | The game shall store the highest score achieved by the player as the Best Score.  | TC-SCORE-006, TC-SCORE-009  | PASS | \- |
| REQ-SCORE-007 | A score higher than the current Best Score shall replace the existing Best Score.  | TC-SCORE-007  | PASS | \- |
| REQ-SCORE-008 | A score lower than the current Best Score shall not replace the existing Best Score.  | TC-SCORE-008  | PASS | \- |
| REQ-PAUSE-001  | The player shall be able to open the Pause menu using the Pause button.  | TC-PAUSE-001, TC-FLOW-002  | PASS | \- |
| REQ-PAUSE-002  | Gameplay shall stop while the Pause menu is active.  | TC-PAUSE-002  | PASS | \- |
| REQ-PAUSE-003  | The player shall remain in the paused game state until selecting an available Pause menu action.  | TC-PAUSE-003, TC-PAUSE-004  | PASS | \- |
| REQ-PAUSE-004  | Selecting Continue shall close the Pause menu and resume gameplay.  | TC-PAUSE-005, TC-FLOW-003  | PASS | \- |
| REQ-PAUSE-005 | Gameplay shall continue correctly after selecting Continue.  | TC-PAUSE-006  | PASS | \- |
| REQ-PAUSE-006 | Selecting Exit from the Pause menu shall return the player to the main menu.  | TC-PAUSE-007, TC-FLOW-006  | PASS | \- |
| REQ-GAMEOVER-001  | The Game Over screen shall be displayed when the player loses.  | TC-GAMEOVER-001, TC-FLOW-004  | PASS | \- |
| REQ-GAMEOVER-002  | The Game Over screen shall display the final score.  | TC-GAMEOVER-002  | PASS | \- |
| REQ-GAMEOVER-003  | The Game Over screen shall display the current Best Score correctly.  | TC-GAMEOVER-003  | PASS | \- |
| REQ-GAMEOVER-004  | The Game Over screen shall provide a Play Again button.  | TC-GAMEOVER-004  | PASS | \- |
| REQ-GAMEOVER-005  | Selecting Play Again shall start a new gameplay session.  | TC-GAMEOVER-004, TC-GAMEOVER-005, TC-FLOW-005  | PASS | \- |
| REQ-GAMEOVER-006 | Starting a new gameplay session shall reset the current score appropriately.  | TC-GAMEOVER-005  | PASS | \- |
| REQ-GAMEOVER-007 | The Game Over screen shall provide an Exit button.  | TC-GAMEOVER-006  | PASS | \- |
| REQ-GAMEOVER-008 | Selecting Exit from the Game Over screen shall return the player to the main menu.  | TC-GAMEOVER-006, TC-FLOW-006  | PASS | \- |
| REQ-ANIM-001  | The player running animation shall play continuously during gameplay.  | TC-ANIM-001, TC-ANIM-002  | PASS | \- |
| REQ-ANIM-002  | The crossbow firing animation shall play when the player shoots.  | TC-ANIM-003  | PASS | \- |
| REQ-ANIM-003  | The air enemy shall play its flying animation during gameplay.  | TC-ANIM-004  | PASS | \- |
| REQ-ANIM-004  | The ground animation shall loop continuously during gameplay.  | TC-ANIM-005  | PASS | \- |
| REQ-ANIM-005 | Gameplay animations shall resume correctly after the game is resumed from the Pause menu.  | TC-ANIM-006  | PASS | \- |
| REQ-FLOW-001  | The application shall correctly transition from the Main Menu to Gameplay.  | TC-FLOW-001  | PASS | \- |
| REQ-FLOW-002  | The application shall correctly transition from Gameplay to Pause.  | TC-FLOW-002  | PASS | \- |
| REQ-FLOW-003  | The application shall correctly transition from Pause back to Gameplay.  | TC-FLOW-003  | PASS | \- |
| REQ-FLOW-004  | The application shall correctly transition from Gameplay to Game Over when the player loses.  | TC-FLOW-004  | PASS | \- |
| REQ-FLOW-005  | The application shall correctly transition from Game Over to a new Gameplay session.  | TC-FLOW-005  | PASS | \- |
| REQ-FLOW-006  | The application shall correctly transition from Pause or Game Over to the Main Menu when Exit is selected.  | TC-FLOW-006  | PASS | \- |
| REQ-UI-001  | Gameplay shall display the Pause button.  | TC-UI-001  | PASS | \- |
| REQ-UI-002  | Gameplay shall display the Shoot button.  | TC-UI-001  | PASS | \- |
| REQ-UI-003  | The gameplay UI buttons shall respond correctly to touch input.  | TC-UI-002  | PASS | \- |
| REQ-UI-004  | The current score shall remain visible and readable during gameplay.  | TC-UI-003  | PASS | \- |
| REQ-UI-005  | The Pause menu UI shall be displayed correctly when the game is paused.  | TC-UI-005  | PASS | \- |
| REQ-UI-006  | The Game Over UI shall be displayed correctly when the player loses.  | TC-UI-004  | PASS | \- |
| REQ-STAB-001  | The application shall not crash during normal gameplay.  | TC-STAB-001  | PASS | \- |
| REQ-STAB-002  | The application shall remain stable during an extended gameplay session.  | TC-STAB-002  | PASS | \- |
| REQ-STAB-003  | Repeated game restart cycles shall not cause application crashes or unexpected behaviour.  | TC-STAB-003  | PASS | \- |
| REQ-STAB-004  | Repeated Pause and Resume cycles shall not cause application crashes or unexpected behaviour.  | TC-STAB-004  | PASS | \- |
| REQ-STAB-005  | Repeated application launches shall not cause application crashes or unexpected behaviour.  | TC-STAB-005  | PASS | \- |
| REQ-STAB-006  | Extended gameplay shall not produce obvious progressive performance degradation.  | TC-STAB-006   | PASS | \- |

