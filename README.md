#  README Instructions
## Stoneblock Server
Contains all stoneblock files to be pushed and pulled to share stoneblock hosting computer

## Instructions
* Initial clone...
  * When you are initally getting the repo: `git clone https://github.com/kboehmer002/stoneblock.git`
  * You only need to do this once... unless you delete the whole thing on your local computer
* After you have cloned the repo...
  * Pull the current code from the repo: 'git pull'
  * You must be inside the repo folder on your local divice (in this case the folder  `stoneblock`) to use this command
    *  `cd stoneblock` 
* Running the server...
  * First things first, handle your [port forwarding](https://github.com/kboehmer002/stoneblock/blob/main/Port_Forwarding.md)! 
  * Start: Click the  `start.bat` file so it will run
    * otherwise while you are in the folder you can run it with `./start.bat`
  * Stop: Type `stop` in either the GUI or the CMD line
  * Admin Privilages: `/op USERNAME_TO_ADD`
  * Teleport: `/tp USER_TO_TP USER_AT_LOC` ; this can be done from the CMD line, the GUI, or (if the user has admin privilages) the chat log


## Easiest way to run after initial cloning
*Note: the cd command is assuming you are in the directory the `stoneblock` folder is in*
```
cd stoneblock
git pull
./start.bat
```
when you are finished...
*Note: You might want to copy+paste the `world` folder into the `backups` folder so you have a copy you can revert to if the current file becomes corrupted*
```
stop
git
git push
```
* Next time you go to start it repeat the process. This keeps the current running world up to date for whoever wants to host next.
* Find the server at your `GLOBAL_IP:PORT_FORWARDED` 
  * eg. `201.131.137.100:2955`

# 12345