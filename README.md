# Funkify

## An exploration of what makes _funk_ music dance-able:

- Via the use of `spotipy` (**python** library), the university github team `Beanie Intelligence` and me created a toolkit to mine data by _playlist_, _genre_ or _artist_.
  - https://github.com/beanie-intelligence/spotify_data_mining
- Using that download playlist feature, I mined a playlist of the top 200+ songs (according to https://digitaldreamdoor.com/pages/best_rb-funk.html).
- With that playlist and using the Spotify Analyzer `danceability` feature which ranges from `0` to `1` , I created `danceability labels`:
  - Split into the following 4 Classes:
    - 0 : `[0.0, 0.5)`
    - 1 : `[0.5, 0.7)`
    - 2 : `[0.7, 0.8)`
    - 3 : `[0.8, 1.0)`
- The report included only contains the `Funkify` hypothesis of the full group coursework.
