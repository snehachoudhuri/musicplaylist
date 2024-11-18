# musicplaylist
This C code implements a basic music player with features like song management, playlist creation, playback control, and song information display. It uses a linked list to store the playlist and provides a command-line interface for user interaction.

How it works:

Data Structures:

Song: Stores information about a song (title, album, URI, ID, year, duration).
PlaylistNode: Represents a node in a linked list, containing a song pointer and pointers to the previous and next nodes.
Core Functionalities:

Song Pool: Manages a pool of songs that can be added to playlists.
Playlist Management: Creates, deletes, and adds songs to a playlist.
Playback Control: Allows users to play, pause, skip, and go back to previous songs.
Song Information: Displays detailed information about the currently playing song, including lyrics.
