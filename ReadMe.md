# Scripted Memtest

Scripts `memtest` to check a Mac's memory. Output is captured, cleaned up, and saved to plist for processing and reporting. 

Script is best run with a LaunchDaemon (as root in /Library/LaunchDaemons) when Mac is not in use and after a reboot to be able to capture as much memory as possible for testing. 

LaunchDaemon and Jamf/MunkiReport collection parts are not included. 

Tested with memtest 4.22.