### How to configure it to work in Windows 10 once user log in.
- Create new task in task scheduler in windows 10 name it anything you want.
- Go to actions tab create new action.
- Select powershell as Program/script.
- Add argument `-ExecutionPolicy Bypass c:\scripts\wslbridge.ps1`


Now the script will run once the user is logged in.
