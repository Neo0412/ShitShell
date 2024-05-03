# ShitShell
The worst reverse shell out there!

ShitShell is a reverse shell which uses a text file hostet on pastebin.com to receive commands and a discord webhook to grand output.
It dosen't get any worse than that!

# Quick Setup Guid
1. Create a new paste on pastebin and insert the raw URL into the script.
2. Edit the paste and write any of the given commands.
3. Now save the paste and run the script.
4. The command written in the paste will be executed.
5. Edit the paste for executing your next command.


# Command List:

- Close: Closes the current ShitShell session.
- FolderTree: Gets folder trees and sends it to your Webhook.
- CheckForAdmin: Checks if the script is being run as admin.
- AddPersistance: Runs script on startup.
- RemovePersistance: Removes persistance.
- GetClipboard: Sends clipboard content to your webhook.
- TakeScreenshot: Sends a screenshot to your webhook.
- Exfil: Given a path, this function will exfiltrate data to your webhook.
- SysInfo: Gives back basic information abt the system.

You can also execute any other Powershell command but won't get any output from it tho.
More are to be added in the future!

# !! ONLY FOR USE ON YOUR DEVICES !!

Thanks to beigeworm for the idea with the pastebin!
Please note that I have only created this script for practice purposes :)
