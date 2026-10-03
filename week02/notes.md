pwd printed the absolute path of the present working directory (e.g., /home/advit).  


ls -a revealed hidden files and directories, specifically those whose names start with a dot, such as .venv.  


The first column in the ls -l output indicates the file type (like d for directory) and its read, write, and execute permissions.  

This works because coding-cafe/week02 is a relative path, meaning it maps the route starting from your current standing location rather than the root directory.   

The mv command performed two different actions: it first moved README-backup.md into the week01/ directory, and then it renamed that file to old-readme.md.  

The PATH contains multiple directories separated by colons.There are 25 folders listed in PATH

My global python3 executable lives at /usr/bin/python3.  

The paths are usually identical unless the peers are using completely different operating systems or customized environment setups.  

The shell returned a command not found error. This occurs because the misspelled program pyton3 does not exist in any of the directories listed in my PATH variable.  

The directory did not appear with a plain ls because its name starts with a dot, which designates it as a hidden folder that requires the -a flag to become visible.  


The prompt changed to display (.venv) at the very beginning of the line, indicating the virtual environment is currently active.  


The path changed to point inside the .venv/bin directory. This tells me that the activate script temporarily placed the virtual environment's path at the very front of my PATH list.  


The second list contains the requests library along with its dependencies (such as certifi, idna, charset-normalizer, and urllib3), which were not present initially.