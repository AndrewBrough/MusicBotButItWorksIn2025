How to use MusicBot https://jmusicbot.com/commands/

**Common Commands**
`?play query`- add a song to the queue. Searches youtube and plays the first result. Can also pass a url or playlist.
`?search query`- add a song to the queue, but searches youtube and lets you chose one of the top results. Supports youtube by default but also supports soundcloud using `scsearch` instead
`?list` or `?queue` - show the current queue
`?skip` - skip the current song. If you played it -  otherwise a vote is started that needs > 50% to skip. Use ?skip to vote.
`?stop` - clears queue and bot leaves chat. PLEASE USE THIS once done playing music.
`?remove #`- remove the song in the queue at #. Eg `?remove 2` 
`?remove all`- remove all songs ONLY YOU have queued.

**Playlists (DJ/Admin only)**
`?playlists`- list all playlists
`?play playlist name`- play the named playlist
`?playlist setdefault name`- play this playlist when the queue is empty. WILL LOOP FOREVER so please STOP the bot when you're done listening.
`?playlist make name`- make a new empty playlist
`?playlist append url url url` or `?playlist append "ytsearch:query" "ytsearch:other query"`- add urls to a playlist. Must be urls or use the "ytsearch:query for song name" format instead of each url.


*Note that you can use either `@MusicBot` or `?` to start your commands eg. `@MusicBot play some kind of bread music`  or `?play idk what do bakers listen to?`