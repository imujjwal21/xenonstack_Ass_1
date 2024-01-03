How to Install:

Get internsctl:
Copy the code: git clone https://github.com/imujjwal21/xenonstack_Ass_1.git


Go into the folder: cd xenonstack_Ass_1
Install stuff: npm install
Make it easy to use everywhere: npm link
How to Use:

Learn More: man internsctl shows a manual.
Need Help?: Use internsctl --help.
Check Version: internsctl --version.
Commands:

Easy Stuff:

Check CPU: internsctl cpu getinfo
It'll show CPU details.
See Memory: internsctl memory getinfo
Shows memory details.
Medium Stuff:

Add a User: internsctl user create <username>
Makes a new user.
List Users: internsctl user list
Lists all users.
List Powerful Users: internsctl user list --sudo-only
Lists users with special powers.
Advanced Stuff:

Check a File: internsctl file getinfo <file-name>
Gives details about a file.
Specific File Details:
Size: internsctl file getinfo --size <file-name>
Permissions: internsctl file getinfo --permissions <file-name>
Owner: internsctl file getinfo --owner <file-name>
Last Changed: internsctl file getinfo --last-modified <file-name>
Examples:

To see CPU: internsctl cpu getinfo
To make a user: internsctl user create john_doe
To get file details: internsctl file getinfo hello.txt
