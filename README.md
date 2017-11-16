# Synchtube Premium
<p align="center">
  <img src="https://dl.dropboxusercontent.com/s/1plmshru4ocjrg2/synchtube_2.png" alt="Synchtube" title="Synchtube" />
</p>

---
## About
**Synchtube Premium** is a powerful JavaScript application for [Synchtube](https://synchtu.be/) (or any other server based on CyTube) channels. It adds to your channel many missing features, functions, and enhancements.
## Installation
1. Log as an admin to your Synchtube / CyTube / etc. room, and go to: Channel Settings > Admin Settings
2. Paste following URL to "External Javascript": `https://dl.dropboxusercontent.com/s/1dyazoq6t7wh808/Premium.js`<br />
3. *Installation finished! No configuration is required.*

---
## Features
### General overwiew
* User-oriented - gives single user almost infinite possibilities to set layout and look of the channel.
* Minimal layout interference - maximum channel boost by adding only few buttons and menus.
* All-in-one file - includes both JavaScript and CSS, no additional files needed.
* Ready-to-use - doesn't require any configuration to work.
* Relatively small filesize - only 275 kB of code.
#### General features
* User settings stored in cookies/localStorage, applied for all rooms powered by Synchtube Premium (you don't have to configure each channel separately)
* Synchtube logo in the navigation bar (only for Synchtube server)
* Channel ID instead of default server name
* Extended "Layout" menu in the navigation bar
* Media progress bar (can be disabled by a user)
* Synchtube Premium credits added to footer
* Additional chat notifications
* List of all new elements added to default layout:
  * 2 navigation bar icons
  * 3 chat header and 4 playlist footer labels
  * "Colors" menu button next to "Emote List"
  * Chat controls - group of 4/5 buttons
  * Menu button added to playlist controls
  * 2 menu buttons and "favourites list" button added to player controls
### List of user options and functions
#### General layout
* Modal windows without fading background
* Glue layout elements to the edge of the screen
* Browser's tab title: page title/ current media title/ channel ID/ number of chat messages
* Displaying/hiding various layout elements
* Compact layout
* Single column layout
* Old Synchtube layout (player on left, chat on right)
* Channel MOTD on bottom
* Large chat, no player
* Large player, no chat
* Theatre mode (only large media player plus chat on the side)
* Radio mode (radio-like layout with hidden video player)
#### Theme customization
* Theme/skin selector, 5 default plus 9 additional themes
* Ignore channels' CSS
* Ignore only this channel CSS (separated option for each channel)
* User CSS code (up to 100k characters)
* 9 optional background patterns
* 14 optional Google fonts
#### Navigation bar
* Make navigation bar scrollable
* Collapse navigation bar
* Transparent navigation bar (opaque on mouseover)
#### MOTD
* Collapse MOTD on load
#### Userlist
* Collapse userlist on load
* Separate userlist items
* Userlist on right
* Big user profiles
#### Chat
* Autohide scrollbars (chat & userlist)
* Don't display "New Messages Below" alert
* Display all user profile images below chat
* Disable chat soundfilters (if available)
* Load emotes to cache on start
* Scroll chat panel to top on load
* Custom character(s) after username in chat messages
* Maximum number of visible chat messages: 50/ 100/ 200/ 500
* Handy emotes panel (expanded on mouseover) with selectable number of emotes per page: 25/ 50/ 100/ 200/ 500
* Emotes tab completion preview with selectable position: don't show preview/ bottom left/ bottom right/ top left/ top right
* Premium Notifiactions with selectable mode: don't show neither/ show only "user joined/disconnected"/ show only "now playing"/ show both
* Ignore chat colors and/or text effects with selectable mode: ignore only colors/ ignore only effects/ ignore both colors and effects
* Custom chat filters (simplified regular expressions)
* "Toggle chat expanding" (to screen height) clickable label
* "Scroll to playlist" clickable label
* "Scroll chat panel to top" clickable label
* Colors button with selectable 30 chat text colors, in addition, any HTML color is possible (typing proper code in the chatline)
* Oeakaki - simple drawing board, uses modified external application, lets user draw a simple picture and returns link to uploaded file (to imgur.com)
* Pseudo-random, info, fun and playlist handling commands - 17 commands started with "!" (including searching for gifs on giphy.com)
* Layout and channel handling commands - 24 commands started with "/"
* 12 chatline codes for text effects
* Up to 10 available shorthands (form "//0" to "//9") for long texts or code sequences defined by user
* List of user chat messages in current session
* List of chat messages in current session that mentioned user's name, with possibility to save up to 200 mentions
* Unicode characters panel (expanded on mouseover) with single symbols, diacritic letters and text emojis
* Custom ping (notification) sound file with adjustable ping volume
* Clear user's chat window
* Upload to imgur - lets user select an image from disk and returns link to uploaded file
* Convert links to images (image is displayed directly on chat, instead of link)
* Convert media to images (player with video or music file is displayed directly on chat, instead of link)
* NicoNico mode (chat messages displayed on the player)
* White background chat
* Separate chat messages (messages separated with horizontal lines)
* Ignore avatars and name colors
* Ignore emotes (displaying only emote text codes instead of images)
* Adjustable chat font size (in percents)
* Leader status menu item (quick toggling of self-leader status)
* Hide AFK users (AFKers will be hidden on the userlist)
* Hide timestamps
* Disable autoscroll
* Always show usernames (username displaying after every consecutive message)
* Matrix style chat
* Bubbled chat messages
* Autoclear button - non-stop clearing the chat (if raid or spam attack)
* AntiAFK button - prevents user from AFK status
* Buttons for "/clear" and "/afk" commands
#### Player
* Hide player until next, possible player covering custom image
* Full-width title bar
* Hide progress bar
* Show time left
* Adjustable player brightness
* Adjustable sound volume
* Disable player (hide both video and sound)
* Remove player
* Mirror player horizontally
* Mirror player vertically
* Show player mascot (12 selectable animated mascots plus option for custom image) with selectable position: bottom left/ bottom center/ bottom right/ top left/ top right/ center
#### Playlist
* List of last played (items played in current session with history of user's plays - up to 100 items)
* Contributors ranking
* Numbered playlist items
* Show contributors usernames (usernames displayed directly on the playlist)
* Filter playlist by username
* Hide playlist scrollbar
* Show miniatures (for YouTube and Dailymotion)
* Hide buttons
* Video quality selector
* Improved retrieve playlist links button - 5 options: raw links/ plain text/ HTML code/ ordered list/ array format
* "Scroll playlist to current item" clickable label
* "Expand playlist" (playlist displayed without scrollbar) clickable label
* "Hide playlist" clickable label
* "Scroll to chat" clickable label
#### Other
* Personal notepad (up to 1M characters)
* Personal media database (requires external .js file)
* Custom HTML in empty space under the chat
* 17 keyboard shortcuts (using "left alt" button)
* Premium admin tools - chat effects, CSS tips, MOTD tabs, soundfilters, media database, customization
* Jukebox mode button
* Channels button - displays list of public channels
* UTC time shown in advanced options panel
* Favourites links panel - up to 200 links to save, with YouTube preview and 3 modes of sorting (oldest firest/ newest first/ alphabetically)
---
## Hosting
Default Synchtube Premium file, together with other separated files (that cannot be included into main code - additional themes, animated mascots, external Oekaki API), is hosted on Dropbox. Some features use external APIs (imgur.com, giphy.com) and obviously are dependent on behaviour of those servers.
## Changelog
### v2.10 - *[2017-??-??]*
* First release on GitHub.
### v2.0 - *[2017-01-15]*
* Heavily modified, reviewed and largely extended new version.
### v1.5 - *[2016-11-04]*
* First public version available for other users.
### v1.0 - *[2016-04-02]*
* First version used only on my channels.
## Feedback
Please open a GitHub Issue.
## License
Premium is free and licensed under Creative Commons CC-BY-NC-SA 4.0 (see [Creative Commons](http://creativecommons.org/licenses/by-nc-sa/4.0/) for the full text).
