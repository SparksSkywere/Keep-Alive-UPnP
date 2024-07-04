# Keep-Alive-UPnP
For anyone who cannot access their router to port forward but the UPnP is left enabled and wants to host a server

# Usage
Before running this script please make sure you have edited the parameters inside the code, this is intended to run on a loop and I didn't add the parameters function as this is intended to run on server startup

# Example Powershell Command:
	.\UPnP.ps1
When you have finished press anykey on your keyboard to stop the port being held open, if you wish to keep this running forever on your system without a console being open remove the part past "# END SCRIPT BELOW"