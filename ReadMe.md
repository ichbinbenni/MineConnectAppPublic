### MineConnect
 
MineConnect is an app for ios and a plugin that allows you to monitor and interact with your sever from everywhere using your smartphone.

This is a first version with limited features. My plan is to listen to your feedback, so we can build a nice and useful App together.

On this side you can share your feedback und report bugs.

#### External links
[iOS-App](https://apps.apple.com/de/app/mineconnect/id1507676445)  
[Website](https://mineconnect.ibb-games.de)  
[Spigot](https://www.spigotmc.org/resources/mineconnect.77957/)


## Setup

### MineConnect is split into three parts:
1. iOS App
An app that everyone can download from the Apple-AppStore for free.
An Android app is under development and will be available later this year.

2. MineConnectServer
It is responsible for the client-communication, to manage the database and sending push notifications to the clients.
MineConnectServer stay awake even when the Minecraft server is offline. This allows users to check the status of the server and it allows the administrator to start the server remotely(future feature).

3. MineConnectPlugin
It is the connection to Minecraft. It monitors everything and stays in touch with the MineConnectServer and tells it when something happen. It also prints messages if someone from an app sends a message.

### Installation
#### Plugin

1. Drag & Drop MineConnectPlugin.jar into plugins folder like every other plugin.
2. Enjoy

#### Server
1. Open terminal(macOS/Linux) or CMD(Windows).
2. Navigate to server folder with cd My/Path/To/Server
3. Execute: java -jar MineConnectServer.jar

Make sure you start MineConnectServer from the server root folder.
(So don't write: java -jar Path/To/Folder/MineConnectServer.jar)