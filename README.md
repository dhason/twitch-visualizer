# Twitch Visualizer

A script to show a visualizer below the [Twitch Plays Pokemon stream](https://www.twitch.tv/twitchplayspokemon).

Below are four different ways to install it.

## Bookmark

You must click a bookmark whenever you open the stream.

1. Add and save a new bookmark with the following URL: `javascript:(function(){document.body.appendChild(document.createElement('script')).src='https://dhason.github.io/twitch-visualizer.user.js';})();`
Note: it may be easier to bookmark something like google.com, then edit the URL / "Location" to the above text, and rename the bookmark to whatever you like.


2. Open up the stream.  After it loads, click on your new bookmark, and the visualizer will appear.

## Greasemonkey (Firefox)

The visualizer will appear automatically whenever you open the stream.

1. [Install Greasemonkey.](https://addons.mozilla.org/en-US/firefox/addon/greasemonkey/)

2. Click here: https://dhason.github.io/twitch-visualizer.user.js

3. Click "Install".

4. Refresh the stream.


##Tampermonkey (Chrome)

The visualizer will appear automatically whenever you open the stream.

1. [Install Tampermonkey.](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo/related)

2. Click here: https://dhason.github.io/twitch-visualizer.user.js

3. Click "Install".

4. Refresh the stream.

## Run on dev console

You must run the script whenever you open the stream.

1. Open the stream.
2. On the stream page:
    * On Firefox, press `Ctrl` + `Shift` + `K`
    * On Chrome, press `Ctrl` + `Shift` + `J`
    * On Safari, press `Ctrl` + `Alt` + `I`
    * On IE9+, press `F12`
    * On Opera, press `Ctrl` + `Shift` + `I`

2. Paste this into the developer console, then hit Enter: `javascript:(function(){document.body.appendChild(document.createElement('script')).src='https://dhason.github.io/twitch-visualizer.user.js';})();`

## Other
Thanks to https://github.com/jpgohlke/twitch-chat-filter/blob/master/chat_filter.user.js, a good twitch extension reference.
