----------------------------------------------------------------------------------------
TACO_II
----------------------------------------------------------------------------------------

	This program works by memory manipulation (memory hack)
	Reading / writing data values / op-codes in target proccess(game) memory
	All changes made by this program are not permanent !
	All changes will be lost / reset after target proccess(game) is closed.

----------------------------------------------------------------------------------------
	Player/Camera
----------------------------------------------------------------------------------------

		Player Position display:
			W-E
			Height
			S-N
			Angle (0->360)

		Camera Position display:
			W-E
			Height
			S-N

----------------------------------------------------------------------------------------
	Hotkeys to control Camera:
----------------------------------------------------------------------------------------
			SHIFT+F Disconnect camera from players position (enables free camera)
			SHIFT+R Restore camera to players position (Turns spectator mode OFF)
				
			SHIFT+W Move to North (North direction on Map)	
			SHIFT+S Move to South
			SHIFT+A Move to West	
			SHIFT+D Move to East
			SHIFT+E Move Up
			SHIFT+Q Move Down

			SHIFT+Z Turn automatic spectator mode(automatic fly mode) ON/OFF (Usable after SHIFT+F is pressed)
			SHIFT+X (Press once or HOLD): Move Camera one step/many steps.

			SHIFT+M		Camera Mouse input ON-OFF:	
			SHIFT+V		Camera Up/Down ON-OFF:		
			SHIFT+H		Camera Derection ON-OFF:	

			SHIFT+I 	In-Game Graphic Interface:  Turns gi on/off     In-Game Console command: 
								no_gi 0		Off
								no_gi 1		On

				
			***Spectator mode (automatic fly mode) is controlled by mouse movement, aimed to the desired direction.
				(Left-Right / Up-Down) @speed controlled by STEP SIZE.

			SHIFT+G   Turn camera floating ON/OFF

	UNLOCK Camera: Unlocks camera from player (indicated by RED square).


			Step Size - allows to change movement step for camera mode.
			+/- Step - allows to change STEP SIZE with (+/- Step) amount.

			Hotkey: SHIFT+ (+) = Increase STEP SIZE
					SHIFT+ (-) = Decrease STEP SIZE


	LOCK Camera:	   Locks camera to player.
			
			Camera position save/load Hotkey:
				Save: ALT+1,ALT+2,ALT+3,ALT+4,ALT+5,ALT+6,ALT+7,ALT+8,ALT+9
				Load: CTRL+1,CTRL+2,CTRL+3,CTRL+4,CTRL+5,CTRL+6,CTRL+7,CTRL+8,CTRL+9

			***All functions under Player/Camera require running of H&D Game.(Player must be in mission) 
				(Program detects if the game is active and program can be launched before Game is running)
			
			***All Camera functions work only if Player has no weapon in hand !!!
	
	Checkbox: Set Mouse Speed H
	Checkbox: Set Mouse Speed V
			User can select custom settings for mouse horisontal / vertical 
			speed for Unlocked camera mode (SHIFT+F)
				Sensitivity value 200 is mostly normal.
				Lower value means faster speed !

			***Mouse sensitivity settings will reset after (SHIFT+R) is pressed.
				TACO program reads game mouse setting only one time if game is present.
				If Mouse sensitivity settings are changed in game settings menu	then
				Mouse sensitivity will be reset to old value (SHIFT+R).



	Screenshot:	CTRL+S
			Image is saved as BMP format.
				


				

----------------------------------------------------------------------------------------
StatusBar:
---------------------------------------------------------------------------------------- 	
	Game Active/Game not Active
	Player profile name.



----------------------------------------------------------------------------------------
TACO_Settings.ini:
----------------------------------------------------------------------------------------
	[Application]

		Form_X=		Program window location from left (@ close, load at next start)
		Form_Y=		Program window location from Top (@ close, load at next start)
		MOUSE_SPEED_H=  Value for mouse horisontal sensitivity (speed)
		MOUSE_SPEED_V=  Value for mouse vertical sensitivity (speed)

	[Game]
		HD2GameExec=    HD2 (or any ohter application) full path (used for running game from menu: Game->Start HD2)
				Example: 
				C:\Program Files (x86)\Ilusion Softworks\Hidden & Dangerous 2\HD2_SabreSquadron.exe







DD.MM.YYYY
----------------------------------------------------------------------------------------
29.07.2022    TACO_II
	All mod functions are discontinued
----------------------------------------------------------------------------------------
2.Dec.2022
+Hotkey functions changed.
----------------------------------------------------------------------------------------
12.Dec.2022 (v2.0.5.7)
+floating camera (SHIFT+G)
+Step value automatic save/load
-Screenshot function removed
----------------------------------------------------------------------------------------
05.Jan.2023 (v2.0.5.9)
+ ??? Fixed something
----------------------------------------------------------------------------------------
15.Jan.2023 (v2.0.6.0)
+Mouse speed settings added
----------------------------------------------------------------------------------------
31.07.2023 (v2.0.6.2)
*some variables moved to global
+Memory documentation added (dev folder Memory.txt)
----------------------------------------------------------------------------------------
27.09.2023 (v2.0.6.5)
+Screenshot function returns...just like Batman.
----------------------------------------------------------------------------------------
04.06.2024 (v2.0.7.1)

Style selection removed.
----------------------------------------------------------------------------------------










----------------------------------------------------------------------------------------
Coded by LARK_1
----------------------------------------------------------------------------------------
Program created with: Embarcadero RAD Studio XE4 / Embarcadero RAD Studio 10.2
----------------------------------------------------------------------------------------




























































Loose lips sink shipt !