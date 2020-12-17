# Anarcho Gaming Minecraft Server

Welcome to Anarcho Gamings Minecraft Community!

Above you can find the current configurations of our Server. (Refer to the group to obtain the IP required for the Server)

Please feel free to submit a pull request if you have any optimization ideas! If you don't know how to do that please ping Rainer in the Group.

All current configs are included.

## Server Commands for everyone

You can find a shorter cheat sheet [here](CheatSheet.md).

### Important note

The server is currently restricted by whitelisting, therefore only known accounts are allowed to connect. To get whitelisted please either Ping @TheCoffeeCommander or @rainer_provokateur on Telegram.

If you are in the Trusted Group (@TheCoffeeCommander and @rainer_provokateur can set that up for you) you will be able to turn off whitelisting to invite new people. To do that do the following:

1. Type `/whitelist off`
1. Let the person you want to add to the server connect
1. When they are connected type `/whitelist add <user name>`
1. Enable the whitelist again with `/whitelist on`

The Server currently supports several convenience functions. Please refer to the following list:

_Note_ All commands are typed into the chat (Press the T key) and need the leading / (slash).

### Durability Ping
Will send a message to you if you tool has 10% of usage remaining.
Enter `/trigger duraPing` to change your personal settings.

### Coordinates HUD
You can enable showing your XYZ coordinates, looking direction and world time.
To enable or disable use `/trigger ch_toggle`

### The warehouse
There is a freeshop on the server where you can freely take all items and use them without asking for permission. The warehouse is also the spawnpoint for new players. To visit the warehouse at any given time type `/trigger warehouse` in the chat.

### Set Home, teleport there - and back!
We've enabled home zones on the server. You can use it at any location; it will set your home. You will still respawn at the last bed you used / at the original spawn point, but you can use commands to teleport yourself to your home with a cooldown of 10 Seconds. This won't work if you are currently attacked by a monster, or if you are drowning.

#### Setting your home
Stand on any solid block and type `/trigger sethome`
An message will tell you if you've been successful.

To add an additional home use `/trigger sethome set <NUMBER>`. You can currently set up to 3 homes.

#### Teleporting to your home
If you want to teleport to your home you may use `/trigger home`. See above for restrictions.

#### Teleporting "back"
To return to your previous position after teleporting home OR in the event of your death you may use `/trigger back`. 

#### Naming your home
While holding a name tag you can name your home with the command `/trigger namehome`

#### Deleting a home
You can delete your home with the command `/trigger delhome`

