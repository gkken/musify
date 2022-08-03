# Musify

Musify is a web based application that utilises Spotify's API to provide users with recommendations based on either user's top tracks/artist or tracks/artist specified by the user. The results can be previewed,removed or can be added as a new playlist into your library.

## Demo

![Musify Demo](/musifyDemo.gif)

## How To Use

To access Musify, users must first login into Spotify and will be redirected to the main page. There are three main components to the app: (1) the Search Bar, (2) Playlist and (3) Media Player.

### `Searchbar`

To perform a search, type in your desired input and confirm by selecting an option from the autocomplete dropdown list. The search bar will only accept up to five (5) chips, once the limit is reached the autocomplete dropdown list will be disabled. Click "SEARCH" to generate a playlist based on your search. Alternatively, click "SURPRISE ME" to get a random playlist based on your top artists/songs.

1. Chips
   - Chips are search inputs that is selected from the autocomplete dropdown list.
   - You can remove a chip by clicking on the `X` button on the right of the chip.
   - You can clear all chips by clicking on the `X` button on the right side of the search bar
   - Chips are color-coded: blue for artist and green for tracks.
2. Autocomplete dropdown list
   - The list will be populated by tracks and artist most relevent to your search input.
   - You can toggle the dropdown by click the up or down button on the right of the searchbar.

### `Playlist`

Initially, the Playlist will be populated with the user's top 15 songs. Upon clicking the "SEARCH" or "SURPRISE ME" button, the Playlist will be updated with the new results. The Playlist can be saved by clicking the "SAVE" button or emptied by clicking the "CLEAR" button. To name the Playlist, click on the text "Playlis Name..." and you will be able to input any name.

1. Playlist items
   - Each track in the Playlist will display # (number), TITLE (album art,song title & artist), ALBUM (album name) and TIMER ICON (song runtime)
   - Hovering the cursor over each individual item will display a REMOVE button, click it to remove the track from the playlist.
   - Hovering the cursor over each number will display a PLAY button, click it to play a preview of the song.
   - Clicking on anywhere EXCEPT the REMOVE button will play a preview of the song.

### `Media Player`

The Media Player will only display at the bottom of the page once a song is played. The player will display the information of the current song (song name, artist & album art) or the song from the previous session. You can play or pause by clicking the PLAY/PAUSE button on the right of the album art.

1. Playback Bar
   - You can click on the Playback Bar to skip to different parts of the song.
   - Alternatively, you can also drag the round pointer to set the point.

## Built With

- [React](https://reactjs.org/)
- [Material UI](https://mui.com/)
- [Spotify API](https://developer.spotify.com/)

## Acknowledgment

Big thanks to my teammates, Edmund and Mun Hin, for their contributions to the codebase.
