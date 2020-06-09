Snake 1.0

Credits:
  Nate Houk and David Reeve

Installation:
  -Unzip snake.zip
  -Run 'snake.exe'

Features:
  -Scoreboard
  -Multiple Levels
  -Level Editor

Object:
  Navigate the snake around the screen and try to eat the apples to gain points. Once you have eaten all of the apples on the level, you will advance to the next level. Try to get the highest points possible to make the scoreboard. You die by running into a wall, or running into yourself.

  Arrow Keys: Moves Snake
  +/-: Increase/Decrease Sound
  m: Mute Sound
  p: Pause
  q: Back to Menu

Edit Mode:
  To enter the edit mode, run 'level editor.bat'. You can also enter edit mode, by passing the following command options.

  'snake.exe edit' Brings you into the edit mode starting at level 1.

  'snake.exe edit level' Asks you what level you would like to edit, and bring you into the edit mode starting at your selected level.

  +/-: Edit Next/Previous Level
  0/9: Increase/Decrease Apples
  t: Toggle Place Wall/Place Head
  r: Reset Level
  s: Save
  w: Quit without Saving
  q: Save and then Quit

Troubleshooting FAQ:
  Q:When I start up the game, it says "Error loading datafile..." and then quits.
  A:Make sure the snake.dat file is in the same directory as snake.exe.

  Q:When I start up the game, it says "Scoreboard not loaded..."
  A:Make sure the scoreboard.dat file is in the same directory as snake.exe. Or you can ignore the error, and a new scoreboard.dat file will be created next time you make the scoreboard.

  Q:When I start up the game, it says "Levels not loaded..."
  A:Make sure the levels.dat file is in the same directory as snake.exe. Or you can ignore the error, and play the default empty levels. A new levels.dat file will be created next time you save from the level editor.

  Q:When I start up the game, I can see the mouse cursor, but the other graphics don't show up.
  A:The snake.dat file has been corrupted. Try downloading the game again.

  Q:The game plays normally, but I hear no sound.
  A:Make sure your speakers are turned on, and the volume is turned up. Try restarting the game, and if that doesn't work, then try restarting your computer.

  Q:The game plays normally, but doesn't respond to the keyboard.
  A:Try restarting the game, and if that doesn't work, then try restarting your computer.

  Q:The game plays normally, but the snake never gets faster when I eat the apples.
  A:Your computer is too slow and cannot process the game fast enough. I have not had the opportunity to test the game on many different computers, so I do not know the cutoff speed. I do know that it runs as intended on a PIII 500.

Bug Reports:
  Please send bug reports to nate@jumpthru.com with your computer specs, and a detailed description of the bug, and any other info you can provide.

Suggestions and Comments:
  Please send suggestions and comments to nate@jumpthru.com. Anything is appreciated!

Legal:
  License:
    Snake 1.0 is distributed as Freeware. You may use this software on any number of computers for as long as you like. The software is NOT Public Domain software. We allow the free distribution of the software, but Nate Houk and David Reeve retain ownership and copyright of the software and its source code in its entirety. You may use and/or distribute the software only subject to the following conditions:

      You may not modify the program or documentation files in any way.
      You must include all the files that were in the original distribution.
      You may not decomplie or otherwise reduce the Software to a human perceivable form.
      You may not sell the software or charge a distribution fee, except to recover the media costs.
      You understand and agree with this license and with the disclaimer of warranty and the limitation of liability printed below.
      The software may be bundled and distributed together with other software products but the same conditions apply.

  Disclaimer of Warranty:
    The software and related documentation are provided "as is", without warranty of any kind. Nate Houk and David Reeve disclaims all warranties, express or implied, including, but not limited to, the implied warranties of design, merchantability, fitness for a particular purpose. Nate Houk or David Reeve do not warrant that the functions contained in the software or documentation will meet your requirements, or that the operation of the software will be uninterrupted, error-free or complete, or that defects in the software or documentation will be corrected.

  Limitation of Liability:
    Under no circumstances, including negligence, shall Nate Houk or David Reeve be liable for any lost revenue or profits or any incidental, indirect, special, or consequential damages that result from the use or inability to use the or related products or documentation, even if Nate Houk or David Reeve has been advised of the possibility of such damages.

    Some states do not allow the limitation or exclusion of liability for incidental or consequential damages so the above limitation or exclusion may not apply to you. In no event shall Nate Houk or David Reeve's total liability to you for all damages, losses, and causes of action, whether in contract, tort (including negligence) or otherwise, exceed the amount paid by you for the software.

  Copyright:
    Program and Documentation are copyright (c) 2001, Nate Houk and David Reeve. All rights reserved.

Version History:
  1.0 August-27-2001 1:30 PM
  Updated license to make game freeware.

  0.9.8 June-4-2001 7:10 PM
  Updated quit graphic

  0.9.7.5 June-4-2001 6:50 PM
  Screenshots

  0.9.7 June-4-2001 6:00 PM
  Speed regulation
  Input regularly checked

  0.9.6 May-28-2001 9:40 PM
  Fixed random crashing

  0.9.5c May-28-2001 10:40 AM
  Fixed change level bug
  Fixed level editor

  0.9.5b May-27-2001 11:10 PM
  Fixed change level bug

  0.9.5a May-26-2001 5:50 PM
  Fixed level editor

  0.9.5 May-26-2001 1:00 PM
  Wrote pause
  Wrote level change
  Updated music

  0.9 May-22-2001 9:15 PM
  Added music
  Fixed level editor
  Wrote edit info

  0.8.5 May-20-2001 7:00 AM
  Fixed scoreboard
  Converted files to .dat

  0.8.2 May-19-2001 7:30 AM
  Wrote scoreboard

  0.8.1 May-18-2001 10:20 PM
  Updated level editor
  Fixed level editor
  Fixed clear snake bug

  0.8 May-17-2001 5:30 PM
  Wrote levels
  Wrote level editor

  0.7 May-12-2001 11:50 AM
  Fixed info
  Quick keys crashes program because of call back rest loop

  0.6.5 May-12-2001 10:20 AM
  Fixed delayed key reaction

  0.6b May-11-2001 11:45 PM
  Updated initial delay
  Updated scoring calculations

  0.6 May-10-2001 9:00 PM
  Updated background graphics
  Updated apple graphic
  Quit graphics
  Fixed crash detection

  0.5.1 May-10-2001 3:30 PM
  Fixed reset snake bug

  0.5d May-10-2001 10:00 AM
  Updated background graphics
  Scoring
  Fixed crash detection

  0.5c May-8-2001 10:00 AM
  Background graphics

  0.5b May-7-2001 7:30 PM
  Updated menu graphics and fixed pointer problem
  Fadeout not working

  0.5 May-6-2001 9:20 AM
  Menu graphics and code cleaned up

  0.4 May-2-2001 6:40 PM
  Apple and crash checking

  0.3 May-2-2001 8:00 AM
  Movable snake

  0.2 May-1-2001 6:30 PM
  Initial graphics

  0.1 April-25-2001 9:30 PM
  Initial program design

Suggestions:
  Enemy Snakes (computer, trying to kill you)
  Multiple Apples (all or some of total apples for level on screen)
  Poison Apples (eat and die)
  Multiple Players (human or computer, trying to win)
  More Obstacles (mud, water, etc.)
  BeOS Port (email interested person)
  Classic Snake (only one level, no obstacles)
  Reset Snake at each Level (instead of keeping your snake length when you change levels)
  Timed Apples (apple relocated if you don't eat in time)
  Timed Game (die if run out of time on level)
  Timer (how long your game lasts)
  Setup Program (ease installation of program)
  Snake corner pieces (would allow for a much better looking snake graphic)