# Amazing-Maze
Project Amazing Maze Race 2014

───────────────────────────────────────
Amazing Maze Race V5
Created using Parallax Propeller Tool
V.1.3.2 - Update 105, 24.feb.2015
───────────────────────────────────────

  Build 105:
  Change of the timing before game start, reduced the waiting time from 9 to 2 sec. removed the sound file "game starts, please get ready".
  now the timing should be 1 secound, and there should be one "ding" before the game starts.
  Change of init-points from 1000 to 1100!
  Boot-routine is longer due to SD-card mounting procedure. Now the SD-card has 2 sec instead of 0,5 sec to mount before use...
  ERF 19, INT 300 Light keeps on after initial boot.

  Client :  Fagskolen Tinius Olsen

     PID :  Amazing Maze Race

 VERSION :  5

 RELEASE :  9

   BUILD :  105

   FINAL :  1

 Project :  "Maze_UPD_M_B105_24-2-15"

Archived :  Tuesday, February 24, 2015 at 1:45:43 PM

    Tool :  Propeller Tool version 1.3.2


            MAZE_005_TOP_update_24-2-15.spin
              │
              ├──tv_wtext.spin
              │    │
              │    └──TV.spin
              │
              ├──Keyboard.spin
              │
              ├──STRINGS.spin
              │
              ├──Output.spin
              │
              ├──V2-WAV_DACEngine.spin
              │    │
              │    └──SD-MMC_FATEngine.spin
              │
              └──SD-MMC_FATEngine.spin


