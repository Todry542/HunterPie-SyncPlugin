Description:
--------------
This is a plugin for [HunterPie](https://github.com/Haato3o/HunterPie) that synchronizes Part and Ailment data between clients.

The server is open source and available [here](https://hub.docker.com/r/todry542/mhwsync).<br>
It is currently deployed on my own server. Please by nice with ;)

Please note that this plugin has not undergone extensive testing yet as I can't test it properly without the help of other players.

Installation:
---------------
Download [module.json](https://raw.githubusercontent.com/Todry542/HunterPie-SyncPlugin/master/module.json) and drag the file into you HunterPie application window.


Compile:
---------------

<b>CAUTION</b><br>
If you want to create your own server, you need to compile again the SyncPlugin.dll with HunterPie:<br>
<ol>
<li>Go to your HunterPie folder</li>
<li>Navigue to Modules folder</li>
<li>Create a new folder and name "SyncPlugin"</li>
<li>Put the "main.cs" with your server url change (line 85 : variable : "ServerUrl")</li>
<li>Copy lib folder with System.Web.dll</li>
<li>Copy module.json</li>
<li>In module.json delete amm after "update"</li>
<li>Save and launch HunterPie!</li>
</ol>
