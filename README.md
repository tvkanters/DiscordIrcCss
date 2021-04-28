# Discord IRC CSS
Custom CSS for Discord that styles usernames of Discord messages and messages coming in through an IRC bridge seamlessly.

![Style example](https://user-images.githubusercontent.com/2603160/113452077-9628c880-9403-11eb-9961-38953337036e.png)


## Installation
**Note:** BetterDiscord removed a critical feature for custom CSS to work reliably in v1.1.0. This style is not compatible with that yet, and it's unclear how it can be made compatible without breaking every time Discord updates. Perhaps someone is kind enough to [create a BetterDiscord plugin that re-enables the feature](https://github.com/rauenzi/BetterDiscordAddons/issues/377), but in the meanwhile v1.0.0 has to be used.

* Install [BetterDiscord](https://github.com/betterdiscord/installer).
* Downgrade BetterDiscord to v1.0.0 by downloading the [`.asar`](https://github.com/rauenzi/BetterDiscordApp/releases/download/v1.0.0-beta/betterdiscord.asar) file and placing it in BetterDiscord's installation directory (e.g., `%AppData%\BetterDiscord\data`).
* Ensure 'Normalize Classes' is enabled under BetterDiscord's general settings.
* Copy-paste the CSS contents of `style.css` into the 'Custom CSS' settings added to the Discord settings.

![Installation example](https://i.imgur.com/6QanIo0.png)
