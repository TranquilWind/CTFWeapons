# Git

Examples: [GitHappens](https://github.com/TranquilWind/CTFWriteups/blob/main/TryHackMe/GitHappens.md)


- Usually found by nmap `<IP>/.git/`
- [GitTools](https://github.com/internetwache/GitTools)
- So far I have used only Git Dumper

### Git Dumper:
- ```
  ./gitdumper.sh -h

  [*] USAGE: http://target.tld/.git/ dest-dir [--git-dir=otherdir]
		--git-dir=otherdir		Change the git folder name. Default: .git
  ```
- Installs everything to the local machine
- now all git commands can be used to see the git's details like `git log` or `git log --patch`
