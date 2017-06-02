# Sublime Text Settings

## Initial
 1. Install [Sublime Text 3](https://www.sublimetext.com/3)
 2. Install [Package Control](https://packagecontrol.io/installation)
 3. Empty all files in **User** folder
	 - Windows: `~\AppData\Roaming\Sublime Text 3\Packages\User`
	 - Windows Portable: `INSTALLED-FOLDER\Data\Packages\User`
	 - Ubuntu: `~/.config/sublime-text-3/Packages/User`
 4. Clone settings into **User** folder
	 `git clone git@github.com:lynn9388/sublime-text-settings.git .`
	 
	 Change file permissions in Ubuntu
	 `sudo chmod 777 Package Control.sublime-settings Preferences.sublime-settings`

## Update
Execute commands in **User** folder
```
git fetch
git reset --hard origin/master
```