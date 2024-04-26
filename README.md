# DiscordBotApp v13.0 Release!
## Download here! https://kodiakcoco.com/downloadbot
### In this new and improved release we can now host two different bots using different coding languages at the same exact time!
- It has an integrated Console that hosts a javascript bot right after the C# bot has started! By first registering the slash commands and then by actually starting the bot!
- After both bots have been started you can use the console (the textBox that says "node register-commands.js") to enter anything into and it will apply it to the javascript bot!
- You can add commands, and your bot token into the .env file and the register-commands.js file and for editing the logic edit the index.js file
**Meanwhile most of the features for the C# bot code remain the same.**
## Upgrades to the C#
- improved image saving by adding the time, and date to the file name
- updated xaml for handling the js bot commands
- updated c# for sending a message after pressing the return key
- updated graphics for the buttons
- updated link for the website button
- better handling for the message logging
- updated graphics for moving the application
- bigger design for the search window
- new closing animations for the search window
## Steps for setting up the bot to work using JavaScript (best to have knowledge in this language specifically)
- First find the .env file because this where you need to input you bot token and server/channel ids
- input all necessary ids and then save the file, then find the "src" folder
- open the "register-commands.js" file and edit anything you want (remember the names for each slash command, you'll need them later)
- save that file and open "index.js" this is where you'll edit any commands and logic for your bot (there's already some code in there so just get rid of what you don't want, and add in whatever you like.)
- save that file and then open the "DiscordBotApp.exe" file (this is the application that will be hosting your bot)
- make a new discord bot in the developer portal and name it "C# Bot hosting" (If you don't have one that you want to host using C#) otherwise place that bot token in the bot token password box. it will be hidden and only show dots (Keeping your bot token hidden can increase the safety of your Discord Bot)
- After you press the "Start Bot" button, in 5 seconds your JavaScript Bot will start, and after it's hosted (Unless you changed the code) you can send a message to the Channel in the Server you specified in the ".env" file.
### Congratulations! You're now hosting a Discord bot from your pc!

Share with more programmers!
### For the source code and VS project, message me on discord.
- username: **calybdev**

## Enjoy coding with C# or JavaScript!
