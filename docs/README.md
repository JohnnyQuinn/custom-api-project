# Johnny's Playlist API

> An API that catalogues my music playlists 

## Resources and fields

- ### Song
    - title
    - artist
    - release_date
    - album
    - genre
- ### Artist
    - name
    - genre
- ### Playlist
    - title 
    - num_songs
    - type (mood, genre, era, etc.)
    - description

## Relationships
- Songs have one Artist (one to one) 
- Artists have many Songs (one to many)
- Playlists have many Songs (one to many) 

## Routes
- **/playlist**: returns titles of all playlists
- **/playlist/&lt;name&gt;**: returns the contents of a particular playlist (all songs in playlist)
- **/playlist/&lt;type&gt;**: returns all playlists of a particular type

