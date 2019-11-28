# media-server

Docker compose scripts to setup a media server for automatically searching and downloading movies and series using torrents or usenets.

Includes the following:
* Transmission: `Responsible for downloading the torrents`
* Jackett: `Responsible for identifying the trackers, either torrents or usenets`
* Sonarr: `Responsible for orchstrating the tasks of searching and organising TV series`
* Radarr: `Responsible for orchestrating the tasks of searching and organising movies`
* Plex: `Media center for browsing through and track series and movies watched`
* Portainer: `Provides interface to monitor the media server and each individual container`

## How to get setup?

Download and install docker compose and run the following script:
```
docker-compose up
```

