

<p align="center">
    <img src="Logo.png" width="400" max-width="90%" alt="Logo" />
</p>

<p align="center">
<a href="https://mineconnect.ibb-games.de">
        <img src="https://img.shields.io/badge/website-mineconnect-3AAF28.svg?style=flat" alt="IBB-Games.de"/>
    </a>

   <a href="https://twitter.com/mineconnectapp">
        <img src="https://img.shields.io/badge/twitter-@MineConnectApp-blue.svg?style=flat" alt="Twitter: @MineConnectApp" />
    </a>
</p>
 
**MineConnect** is an app for ios and a plugin that allows you to monitor and interact with your Minecraft sever from everywhere using your smartphone.  
This is an early version. We plan to listen to your feedback, so we can build a nice and useful App together.  
On this site you can share your [feedback and report bugs](https://github.com/ichbinbenni/MineConnectAppPublic/issues). Just open an issue and tag your category. Like bug or feature request.

### Features

#### For users
- Push notifications for join-, leave-, die- and message- events. You can select each user you want to get a notification for.
- Chat with your server and friends from the MineConnect app. Even private conversations from Minecraft are as simple as using the ```/tell <Player> <Message>```-command.
- Dashboard that shows you what is interesting for you. How many persons are playing, who is online and other stats.

#### For admins
- Execute commands from the app. Also save your favorite commands for quick access.
- You can adjust everything easy from the app - no property file or commands you have to learn.
- White/Blacklist support: MineConnect can only be used by users that are on your whitelist (if enabled) or not on your blacklist.
- All operators are also admin for MineConnect.



### External links
[iOS-App](https://apps.apple.com/de/app/mineconnect/id1507676445)  
[Website](https://mineconnect.ibb-games.de)  
[Spigot](https://www.spigotmc.org/resources/mineconnect.77957/)  
Android - Coming later this summer

### Support
It costs $99 a year to publish an app to the AppStore. The app is free and without ads. It would be nice if you support this project and help me not to pay for making this app.

[![ko-fi](https://www.ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/O5O31JZNP)

## Setup

### Installation

#### 1. Plugin

Download the plugin from our [website](https://mineconnect.ibb-games.de/versions.html).

Just drag & drop the plugin file into your plugins folder. MineConnect needs Port 4711 - so make sure the port is open.

*Important: If you come from version 0.1 you have to delete the file ```mineconnect.db```. Because of the big structural change in this transition from 0.1 to 0.2 a migration wasn't useful. Of cause in future versions we try to migrate the database.*

#### 2. App
Download the app from the [Apple AppStore®]((https://apps.apple.com/de/app/mineconnect/id1507676445)).  
Android version will be available later this summer.

To add a new server you need to join your server in Minecraft. Execute the command ```/registerMe```. This will give you a four-digit one time password. So you don't need to remember it. Enter this password with the server address and your username into the MineConnect app.


### Made with ♥️ by Benedikt Spohr, Jonas Görgen and Roman Kramme
