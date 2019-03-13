# Git Gud at setting GIT repos!

GitGud helps you to set up a working local and remote repository on GitHub.
The repo manager sets up a local repository with your name of choice and sets a remote repo on GitHub with the same name. Later a connection between the two is established.

Note: For best results put the script in any folder listed in PATH or add the repo folder to PATH itself.

How to use:
Running gitgud without parameters yields the same result as with -h or --help.

gitgud [-h | --help] OR [-q | --quiet] [REPO]

-h/--help: Shows this help message
-q/--quiet: Omits error output to screen, instead redirecting it to the log file.
REPO: Repository name. If no path is specified - creates in current working directory. Otherwise uses mkdir -p for path creation.
Once the local repo is created, it is initialized with git init.
A local directory ~/.gitgud is created for log files. These are sorted by date.

You will be asked for GitHub username and password - it will not be saved or logged so you'll use it every time you18 create a remote repository on GitHub with the same name as the local one, linking them aft18directed to log file.
If18king is successful - a success message will be shown. Otherwise a failure message is print18 is deleted from the machine - but the path to it is left untouched.

ROADMAP:
1. Get the directory creation more precise.
2. Make initial README addition dynamic (Right now it's got a placeholder text)
3. Refine the quiet feature.
4. Debug. A lot.
