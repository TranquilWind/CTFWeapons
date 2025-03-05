# Wordpress

Examples: [MrRobotCTF](https://github.com/TranquilWind/CTFWriteups/blob/main/TryHackMe/MrRobotCTF.md)

- Doesn't appear on nmap scanning (most cases)
- From what I have tried/know dirbuster/gobuster can help in figuring out the login page `wp-login` or related pages or just menddling with the URL will lead to some page which shows the wordpress backend.
- Login using clues or brute force
- There will be some editable .php file which can also be executable (like when you visit the link related to the editor)
- Use pentestmonkey to get shell access
