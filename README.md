# Youtube Music Playlist Index Ordering
A userscript to add the ability order song based on index, like how Steam does on user's wishlist page.

# Why?
Why not? It's easier when you have many songs in one playlist

# How it works?
It gets the playlist ID and check if the playlist mode on the page is in manual ordering. It will assign input boxes to every song in the list for, ofc the input.

On changing the input, it will get the song ID in the playlist and use Youtube's API on moving the song order. This ofc needs authentication, so the script fetch it from the cookie, then execute it.

# AI Disclosure
The userscript is made by Gemini, Claude, and a direction from me. Some glitches or bugs are expected
