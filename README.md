<h2>How to install:</h2>

Open sublime text.

Click 'preferences'

Then 'browse packages' 

Go into 'User'

Download the file above, and put it in there.

When its put in there, you should be able to open any .nmap file and have syntax highlighting. 

Or if you're like me, open your namp file and manually select the syntax, either through 'Ctrl + P > Set Syntax: Nmap' or clicking the thing in the bottom right corner.

<h2>If you click browse packages and nothing happens</h2>
<h4>Linux:</h5>
The path is:
/home/`whoami`/.config/sublime-text/Packages/User/

```bash
#command to open path
xdg-open /home/`whoami`/.config/sublime-text/Packages/User/
```

Or root:
/root/.config/sublime-text/Packages/User

<h4>Windows:</h4>
C:\Users\<user>\AppData\Roaming\Sublime Text\Packages

```powershell
# powershell command to open path
$appdata = $env:APPDATA; $fullpath = $appdata + "\Sublime Text\Packages\User"; start $fullpath
```
