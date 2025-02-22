# Hydra

## For Webpages

`hydra -l <uname or wordlist> -P <wordlist> <loginpage url>:username=^USER^&password=^PASS^:<error text>`

- `hydra`: to run hydra
- `-l <uname or wordlist>`: option to specify username or path to usernames list
- `-P <wordlist>`: option to specify path to wordlist for password
- `loginpage url`: URL of target login page
- `username=^USER^&password=^PASS^`: hydra syntax of username and password placeholders
- `<error text>`: error text to help hydra determine when login attempt fails
