
* ## The .bat File

* Toggle viewing input commands (Optional):
  * *on/off*.
	
	>@echo off	

* Change directory to rclone folder: 
  * *Coordinates to the folder containing "rclone.exe"*
	
	>cd C:\your\directory\here\

* Mount the remote to the designated drive letter: 
  * *Remotes are created through running "[rclone config](https://rclone.org/commands/rclone_config/)"*.
  
  * Replace ***"X X X"*** with your created remote name *(eg. Drive or "Google Drive")*, then Replace ***X:*** with your desired Drive letter *(eg. D:)*.
  
  * *Do **NOT** Remove Quotation Marks if your created remote drive contains spaces*.
	
	>rclone mount --vfs-cache-mode full "X X X": X:

* Enable the "Press any key to continue..." prompt: 
  * *Should only really show up when an error is given*.
	
	>pause

⚠ Don't forget to place the .bat File in the same location as the rclone.exe

---

>Should look something like this:
 * <img src=assets/asset12.png>

---
