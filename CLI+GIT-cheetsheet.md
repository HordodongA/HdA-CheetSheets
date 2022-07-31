# PowerShell cheatsheet  
https://devblogs.microsoft.com/scripting/table-of-basic-powershell-commands/  

## Operational 
> ### Arrow up  
> * Last command  
> ### Arrow down  
> * Next command  
> ### TAB  
> * Directory/file name completion  
> ### clear  
> * Clear console  
> ### Ctrl + C  
> * Cancel process  
> ### pwd  
> * Print Working Directory  
> ### ls | ls -a (ls -force)  
> * List directory contents | List directory contents with hidden files  
> ### help [commandName]  
> * Print the help for the command  
> ### exit  
> * Close PoweShell  

## Whiteboard characters  
> ### ?  
> * One whiteboard character  
> ### *  
> *  whiteboard character  
> ### >  
> *  Print command answer to file (If file exists, rewrite content)  
> ### >>  
> *  Concat command answer to file  

## Navigation  
> ### cd [dirName] | cd [dirName/dir2Name]  
> * Change directory  
> ### cd .. |cd ../.. | cd ../../..  
> * Go up a directory | two | three  
> ### cd /  
> * Go to root directory  
> ### d:  
> * Go to drive D root directory  

## Directory and file operations  
> ### mkdir [dirName] (mk dirName)  
> * Make directory  
> ### rmdir [dirName]  (rd dirName)  
> * Remove directory  
> ### ni [fileName]  
> * Make file  
> ### rm [fileName]  
> * Remove file  
> ### del [dirName/fileName]  
> * Remove directory or file  
> ### type [fileName]  
> * Print file content to console  
> ### copy  
> * Copy file  
> ### move  
> * Move file  
> ### ren (rename)   
> * Rename file or folder  

## Node.js commands  
> ### node -v  
> * Print Node.js version  
> ### node [fileName.js]  
> * Run javascript file  

## Visual Studio Code commands  
> ### code  
> * Open VS Code  
> ### code [fileName]  
> * Open file is VS Code  
> ### code .  
> * Open VS Code in working directory with all files in it  

## Git commands  
> ### git --version  
> * Print Git version  
> ### Git init  
> * Start version control of working directory  
> ### Git add [fileName]  
> * Send file to staging area  
> ### Git add .  
> * Send file to staging area  
> ### Git commit [fileName] -m "message"  
> * Commit file with description of commit  
> ### Git commit . -m "message"  
> * Commit folder's all files with description of commit  
> ### Git status  
> * Pront working directory's files (working tree) status  
> ### Git log  
> * Show history of version controlled folder  
> ### Git switch  
> * Undo operations since last commit. Restore last commit  
> ### Git checkout [commitHash]  
> * Restore exact commit  

## Github operations  
> ### Git config --global user.name "[firstname lastname]"  
> * Configure user name for all local repositories  
> ### Git config --global user.email "[valid-email]"  
> * Configure user email for all local repositories  
> ### Git clone [URL]  
> * Clone remote repository to local  
> ### Git remote add [alias] [URL]  
> * Link local repository to remote repository with name "origin"  
> ### Git remote -v  
> * Print linked remote repository URL  
> ### Git fetch  
> * Compare files of remote repository with files of local repository  
> ### Git pull  
> * Pull remote repo to local and look for differences   
> ### Git push  
> * Upload commits to remote repository (full commit history)  
> ### Git push -set-upsream [alias] main  
> * Push to remote repository's main branch  
> ### Git branch  
> * Print branches, active branch marked with *  
