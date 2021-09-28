# yt-karaoke
Terminal-based karaoke song manager.<br />
Uses youtube-dl and mpv so install them first.

# Install
Create the directory "$HOME/.karaoke". (default)<br />
Add youtube channel urls to "$HOME/.karaoke/channel_list" file. (default)

# How to use
Go to youtube and look for some channels that upload karaoke songs and add the channels to the channel_list file.<br />
When channels are added, run "karaoke update" and it will index all videos into a database. This is very slow.<br />
You can then search and play songs by either entering the number or the song name.

# Settings
You can edit the karaoke script and change the MPV variable if you want other MPV settings.<br />

# Todo
Make a setting that download songs as they are played so then don't have to be streamed multiple times in case they are played often.<br />
Automatically remove broken links.
