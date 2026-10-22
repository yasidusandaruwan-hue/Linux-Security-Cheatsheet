# Linux-Security-Cheatsheet
Essential Linux commands for beginners in Cybersecurity.

Linux Essentials & Cyber Security Cheat Sheet.

1.) System Navigation 
* pwd                - Displays the current directory.
* ls                 - Lists the files in the folder.
* ls -la             - Displays all details, including hidden files.
* cd [directory]     - Switch to another folder.
* cd ..              - Returns to the previous folder.

2.) File & Directory Management 
* mkdir [folder_name]- Creates a new folder.
* touch [file_name]  - Creates a new empty file.
* cat   [file_name]  - Checks the content of the file.
* rm    [file_name]  - Deletes a file.
* rm -rf   [folder]  - Deletes a folder completely.
* cp [src] [dest]    - Copies a file.
* mv [src] [dest]    - Moves or renames a file.

3.) Text Manipulation & Search 
* grep "text" [file] - Searches for specific words within a file.
* nano [file_name]   - Edits a file within the terminal
* subl [file_name]   - Sublime Text opens the file.

4.) Permissions & Superuser 
* sudo [command]     - Runs with Admin / Root privileges.
* chmod +x [file]    - Allows a file to be executed (run).
* chmod 755 [file]   - Changes file permissions.
* chown [user]:[group] [file] - Changes the file owner.

5.) Network & Troubleshooting 
* ifconfig / ip a    - Checks IP addresses and network interfaces.
* ping [ip/domain]   - Checks the network connection.
* netstat -tuln      - Checks for open network ports.
