# Spotify-music-clustering
Nowadays we don't have time to listen to each and every song that we come across in a playlist. so, this project helps you. we used Spotify API for collecting the dataset information and able to  do EDA and used K- means clustering technique and created new playlists in Spotify again.


follow these steps:
1. click this link and open spotify devoloper https://developer.spotify.com/dashboard/login
2. login and create an app
3. Find client id and client secret and paste in the code snippet.
4. Open Spotify music app open profile and copy username ( to create new playlists in the Spotify music app)
5. to generate new playlists in spotify app:

go to console  and click  /v1/users/{user_id}/playlists  ( used to create playlist) and generate auth token.
similarly go to console and click add items to playlist and generate auth token.
![image](https://user-images.githubusercontent.com/70406667/152685802-0c8da5e8-4579-42ad-aba8-59f7a28de539.png)
![image](https://user-images.githubusercontent.com/70406667/152685857-78954e76-0f51-4706-a516-466747013b3f.png)
(click get token in both of them. copy and paste in code snippet) 

6.  copy all those id's and usernames in notebook file ( follow those comments further)
