# A Raspberry Pi Template for .NET Core 2 projects
An empty project template for .NET Core 2 IoT applications deployed to the RaspberryPi.

I started this project after reading this post:
https://www.thurrott.com/dev/106624/net-core-comes-quietly-raspberry-pi

## How to install the template

<b>TL;DR</b>  
<code>dotnet new -i RaspberryPi.Template::*</code>

I wrote about how to use this template and install it into your development environment in this post:  
https://jeremylindsayni.wordpress.com/2017/03/21/how-to-a-net-core-template-to-create-a-new-project-from-the-command-line-with-dotnet-new-i/

You need .NET Core 2 installed - you can get the most recent previews from here:  
https://github.com/dotnet/cli/tree/master

You can install from nuget using the command:  
<code>dotnet new -i RaspberryPi.Template::*</code>

Or if you want to install the source code and modify it, clone the repo to a directory (I put mine in the folder below but you can clone it anywhere):  
<code>C:\Users\Jeremy\Documents\Visual Studio 2017\Templates\ProjectTemplates\Raspberry Pi</code>

Then install the template using the command below:  
<code>dotnet new -i "C:\Users\Jeremy\Documents\Visual Studio 2017\Templates\ProjectTemplates\Raspberry Pi\RaspberryPiTemplate\RaspberryPiCore"</code>

Now you can see the list of templates you have installed with this command:  
<code>dotnet new --list</code>

And you can create a new project (called "MyNewProject") for your IoT device with the command:  
<code>dotnet new coreiot -n MyNewProject</code>

## More
See more examples of running .NET Core apps the RaspberryPi ARM device here.  
https://www.hackster.io/Ra5tko/running-native-net-core-apps-on-raspberry-pi-arm-0bb717
