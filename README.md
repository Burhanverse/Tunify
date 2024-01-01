<p align="center">
  <img src="src/docs/assets/icon files/IMG_6573.PNG" height="256">
  </a>
  <a href="t.me/tunifyy/6">
    <h1 align="center">Tunify</h1>
  </a>
</p>

Creates an auto-updating Telegram post that shows what you are currently listening to on Spotify.  
You can see how it looks [here](t.me/tunifyy/6)

## Difficulty level

-   If you had programming experience: 🟢 easy.
-   If you have no programming experience: 🟡 medium.

Before you start, I recommend that you read the instructions in full and proceed with an understanding of the complexity and your capabilities.

## Installation and local launch

1. Download and install [Node.js](https://nodejs.org/en/download/).
2. [Download project files](https://github.com/runixe786/Tunify/archive/main.zip) and unzip it (prefer doing it on desktop). It is better that the path contains only Latin characters without spaces.
3. Launch the terminal from the root directory of the unzipped folder and run `npm i`. Wait for the installation of dependencies to complete (3-10 minutes depending on the speed of the Internet).
4. After its done, close the terminal, re-launch it in same directory and run `node src/init`. The script will ask you to insert a channel or chat ID. Without closing the console, go to the next step.
5. There are many different ways to find out the channel or chat ID. I will describe the simplest one: Add the bot [@myidbot](https://t.me/myidbot) to your chat or channel → send the command `/getgroupid@myidbot` → copy your Id (along with a minus, if any) → paste it to the open console and press Enter.
6. The script will ask you to insert the bot token. To get a token, go to chat with [@BotFather](https://t.me/BotFather) and send the command `/newbot`. Following the instructions. Upon completion, [@BotFather](https://t.me/BotFather) will send you your bot token. Copy the token → paste it into the console and press Enter. After that, the script will ask you to insert the Client ID.
7. Add your bot from step 6 to your chat or channel.
8. Go to [this link](https://developer.spotify.com/dashboard/applications) (login if required).
9. In your "Dashboard" click on "CREATE AN APP".
10. Enter any name and description of the application.
11. Now ,in the Redirect URIs field enter `https://example.com/` , check all the boxes down below and → click "CREATE AN APP".
12. Now you will be on dashboard page after creating thr app. Click on that app name displayed in dashboard. go to settings on top right corner and Find your Client ID on the page and copy it → paste it into the console and press Enter
13. The script will ask for your Client Secret. Return to the browser → click "Show Client Secret" → copy your Client Secret → paste it into the console and press Enter.
14. The script will warn you that a browser will now open. Press Enter, sign in to your account and grant access. After that, the browser will automatically close and the console will display a message about successful initialization. Immediately after initialization, the script will automatically run the main script. Don't close the console.
15. Play some song in Spotify. Your device must be connected to the internet. If you did everything right, that very cherished message from the bot should appear in your channel or chat. Congratulations if you succeeded 🎉 It was not easy 😁

If you close the console, the bot will stop updating your channel post. If you closed the console, you can start the bot again by simply running `node src/index`. The bot won't send a new message, but will update the old one, so it is advisable to pin it. Sometimes errors can appear in the console. If they do not repeat, then everything is fine.

## Feedback

If you find any errors in the script or inaccuracies in the instructions or want to add suggestions, [open new issue](https://github.com/runixe786/tunify/issues/new) or text me in Telegram [@MaybeSahil](https://t.me/MaybeSahil).  
Subscribe to my Telegram channel [@DroidDenn](https://t.me/DroidDenn).
