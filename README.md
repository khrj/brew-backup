# BrewBackup
Automated Backup of brew programs, casks and Mac app store apps (using brew bundle dump).

## Backup
1. [Duplicate this repository](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/duplicating-a-repository)
2. Clone repository to documents (You have to, it's hardcoded), and make sure you use SSH, NOT HTTPS.
3. Remove the Brewfile (That's my brewfile)
4. Copy Brew Backup to /Applications/
5. Use apple's built in calendar to schedule running brew backup. [Guide](http://www.macosxautomation.com/automator/calendar/index.html)

## Restore
1. Clone your duplicate of this repository
2. Run brew bundle
