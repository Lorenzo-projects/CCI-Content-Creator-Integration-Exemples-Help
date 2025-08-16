## 🎮 Minecraft CCI Stream Setup
This repo shares my Content Creator Integration (CCI) setup for Minecraft 1.20.1 (Forge 47.4.0), used on my Twitch channel (llorenzo_exe). It helps streamers connect StreamElements events to in-game actions like spawning sheep, cats, or zombie hordes with viewers' names! 🐑💥
My goal is to make it easy for you to set up CCI and bring your streams to life. Follow the guide below, copy my events, and start creating epic Minecraft moments!
be awere of one thing. ALL of the messages' displayed in the chat will be in ITALIAN. You can change them very easily


## 📜 My Stream Events
Follow: 1 sheep named after the follower.
Subscription (1 month): 1 cat named after the subscriber, tamed to llorenzo_exe.
Gifted Sub/Donation (100 bits = 1€):
5€/500 bits: 5 zombies + 3 skeletons.
10€/1000 bits: 7 zombies + 5 skeletons + 1 witch.
25€/2500 bits: 10 zombies + 7 skeletons + 2 witches + 1 blaze.
50€/5000 bits: 15 zombies + 10 skeletons + 3 witches + 3 blazes + 3 wither skeletons.
Raid or Host: 1 zombie per viewer (up to 50), named "RaidZombie".


## 🛠️ Setup Guide
Requirements

Minecraft 1.20.1 with Forge 47.4.0 (download).
CCI mod (CurseForge).
StreamElements account with a JWT token.
A world with cheats enabled.

Steps

Install CCI:
Download CCI for Minecraft 1.20.1 and place the .jar in .minecraft/mods/.

Create a World:
Start a singleplayer world with Allow Cheats: ON.

Connect StreamElements:
Use the simple guide listend on the official documentation of CCI: https://content-creator-integration.readthedocs.io/en/latest/gettingstarted/
OR
Get your JWT token from StreamElements Dashboard > Profile > Show secrets.
Edit .minecraft/config/contentcreatorintegration.toml:[socket]
streamElementsTokens = ["your_jwt_token_here"]
streamElementsWebsocketTokens = ["your_jwt_token_here"]


## 🐞 Troubleshooting

No mobs? Ensure cheats are enabled in your world.
No events? Verify the StreamElements token and WebSocket in /cci edit > Connections.
Errors? Check .minecraft/logs/latest.log.


## 🤝 Contribute
Have a cool CCI setup? Share it in GitHub Discussions or on my Twitch! Let’s make streaming better together! 🌟

## 😎 Support
If this helps, visit my Twitch channel and maybe spawn a sheep or two! 🐾 Star this repo ⭐ to share with others!

## 📜 License
MIT License

## Created by:
.lorenzo_. on discord, 
llorenzo_exe on Twitch and Instagram, 
Claude.ai (Sonnet 4.0)
