Get the latest Cake build.ps1 by opening a powershell script, change the working directory to this one, and run:

Invoke-WebRequest http://cakebuild.net/download/bootstrapper/windows -OutFile build.ps1

Now open the build.cake file, and replace the placeholders with values for your Raspberry Pi's IP address, the destination directory, and the username you use to log into your Pi.