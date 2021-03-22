# DO NOT USE V2! IT'S NOT DONE YET, [USE V1](https://github.com/colinhartigan/valorant-rpc/releases/)

```
 _    _____    __    ____  ____  ___    _   ________            ____  ____  ______
| |  / /   |  / /   / __ \/ __ \/   |  / | / /_  __/           / __ \/ __ \/ ____/
| | / / /| | / /   / / / / /_/ / /| | /  |/ / / /    ______   / /_/ / /_/ / /     
| |/ / ___ |/ /___/ /_/ / _, _/ ___ |/ /|  / / /    /_____/  / _, _/ ____/ /___   
|___/_/  |_/_____/\____/_/ |_/_/  |_/_/ |_/ /_/             /_/ |_/_/    \____/   
```

# valorant-rich-presence-client
 
A feature-rich Discord rich-presence extension for VALORANT


## Images
![image](https://user-images.githubusercontent.com/42125428/112060312-64764e80-8b33-11eb-843b-2bb457b39a31.png)
![image](https://user-images.githubusercontent.com/42125428/112060125-22e5a380-8b33-11eb-9bbe-5cc9fa5605df.png)
![image](https://user-images.githubusercontent.com/42125428/112060228-4c063400-8b33-11eb-9701-1ff403d7b916.png)
![image](https://user-images.githubusercontent.com/42125428/112060347-73f59780-8b33-11eb-8881-27d291ff9eac.png)


## Installation
> Antivirus might mark the installer executable as malicious, you can run it anyway

For most of you, select **Install for all users**; you'll know if you want to select the other option.

![image](https://user-images.githubusercontent.com/42125428/112061391-d13e1880-8b34-11eb-9b69-c81d43f080b8.png)

If you get a Windows notification from User Account Control, choose yes

![image](https://user-images.githubusercontent.com/42125428/112061494-f16dd780-8b34-11eb-9ffd-c8910cb7c254.png)

Take note or copy of the path to your installation, you'll need it later!

![image](https://user-images.githubusercontent.com/42125428/112061608-1f531c00-8b35-11eb-8a1b-4ae1931bf9eb.png)

During installation, you have a decision to make: *"do I want the program to automatically launch with VALORANT (recommended), or do I want to manually launch it every time I play?"*. 
**If you chose the second option**, it is recommended you create a desktop shortcut, otherwise, ignore that option.

![image](https://user-images.githubusercontent.com/42125428/112061652-309c2880-8b35-11eb-9144-b90a0d73be44.png)

It is recommended you run the program after installing; it runs a few first-time setup tasks.


## Editing the configuration
Navigate to %APPDATA%\valorant-rpc and open config.json with your favorite text editor
> press CTRL+R, type *%APPDATA%\valorant-rpc* then press enter

### settings

- `launch_timeout`: time, in seconds, the program should wait for VALORANT to launch. if the time passes before the game fully loads, the program will exit
- `menu_refresh_interval`: how often, in seconds, the program should update your Discord presence while in the menus
- `ingame_refresh_interval`: how often, in seconds, the program should update your Discord presence while in a game 

### riot account

inputting your account credentials is OPTIONAL; however, features including Discord party invites and agent details in presence require login
- `username`: Riot account username
- `password`: Riot account password

### rpc-oauth
- leave this section blank; it stores the application's Discord authentication data

### rpc-client-override
- leave this section unchanged UNLESS you are setting up your own Discord application to share with friends so you can use the party invites feature. [Read more about it here](https://github.com/colinhartigan/valorant-rpc/wiki)


## Restarting the application
> this **DOES NOT** close/restart VALORANT, you can restart the app while VALORANT is open
After editing the configuration, locate the tray icon, right click it, and select **restart**
![image](https://user-images.githubusercontent.com/42125428/112065554-3268ea80-8b3b-11eb-928a-9cdb92b9dbb1.png)

The console window will reappear for a few seconds and the program will restart
