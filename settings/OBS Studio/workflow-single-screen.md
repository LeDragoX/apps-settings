# 🖥️ Workflow For a Single Screen

1. Use OBS Studio to Record/Live;
2. Download and Install [Transparent Twitch Chat Overlay](https://github.com/baffler/Transparent-Twitch-Chat-Overlay/releases);
   1. Open the settings, log in with your account if only streaming to _Twitch_;
   2. If you are _multi-streaming_ go to **Settings** > **Chat** and down below click **KapChat (Default)** and set **Custom URL**.
   3. Now resize and adjust the zoom accordingly (I recommend using next to the right-side of the screen).
3. Create an account on [BotRix](https://botrix.live/) and link all your accounts;
   1. Go to [this page](https://botrix.live/panel/widget/chat), customize the way you want to...
   2. Copy the link and paste on **OBS** as a browser source and **Transparent Twitch Chat Overlay** as a **Custom URL**, then **save**.
4. Create and link [StreamElements](https://streamelements.com/) account to your platforms, setup whatever you need (takes some time).
5. Download [Streamer.bot](https://streamer.bot/) to automate your stuff, you'll need to watch some tutorials, but trust me, this is OP for live-streaming production.
   1. Starter Pack from **Nutty**, import it and have fun (it's free): <https://nutty.gg/products/streamer-bot-starter-pack>
   2. Or the 🇧🇷 portuguese translation I made + some changes to it [here](./../Streamer.bot/ledragox-streamer-bot-essentials-nutty-traduzido-v1.0.4.nut).
      1. Import any file from the **Import** button, and throw the file at "**Import String**".
   3. A good automation idea is to set a hotkey to clip directly on Twitch, check this [page](https://thefyrewire.com/docs/api/twitch/clips/#required-parameters) on how to setup with the **Fyre API** (using StreamElements).
6. Profit!
