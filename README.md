## Overview
This Power BI dashboard analyzes the most streamed tracks on Spotify. It includes detailed information on track names, artists, release dates, chart presence, playlist inclusions, and various musical features such as danceability, energy, and more.

## Data Description
The dataset used for this analysis contains the following columns:

1. **track_name**: Name of the song.
2. **artist(s)_name**: Name of the artist(s) of the song.
3. **artist_count**: Number of artists contributing to the song.
4. **released_year**: Year when the song was released.
5. **released_month**: Month when the song was released.
6. **released_day**: Day of the month when the song was released.
7. **in_spotify_playlists**: Number of Spotify playlists the song is included in.
8. **in_spotify_charts**: Presence and rank of the song on Spotify charts.
9. **streams**: Total number of streams on Spotify.
10. **in_apple_playlists**: Number of Apple Music playlists the song is included in.
11. **in_apple_charts**: Presence and rank of the song on Apple Music charts.
12. **in_deezer_playlists**: Number of Deezer playlists the song is included in.
13. **in_deezer_charts**: Presence and rank of the song on Deezer charts.
14. **in_shazam_charts**: Presence and rank of the song on Shazam charts.
15. **bpm**: Beats per minute, a measure of song tempo.
16. **key**: Key of the song.
17. **mode**: Mode of the song (major or minor).
18. **danceability_%**: Percentage indicating how suitable the song is for dancing.
19. **valence_%**: Positivity of the song's musical content.
20. **energy_%**: Perceived energy level of the song.
21. **acousticness_%**: Amount of acoustic sound in the song.
22. **instrumentalness_%**: Amount of instrumental content in the song.
23. **liveness_%**: Presence of live performance elements.
24. **speechiness_%**: Amount of spoken words in the song.
25. **cover_url**: Web URL of the cover art.

## Dashboard Overview
The Power BI dashboard provides the following insights:

- **Total Streams**: Total number of streams for all tracks in the dataset.
- **Tracks**: Total number of tracks analyzed.
- **Average Streams**: Average number of streams per track.
- **Streams by Release Date**: Visualization showing the distribution of streams by the release date of the tracks.
- **Tracks and Streams by Month**: Table showing the number of tracks and average streams per month.
- **Daily Streams for all Tracks**: Bar chart showing daily streams.
- **Artist(s) Most Streamed Track**: Details of the most streamed track by the artist(s) including track name, release date, streams, mode, key, and other musical features.
- **Top 6 Most Streamed Tracks**: List of the top 6 most streamed tracks with their cover art.
