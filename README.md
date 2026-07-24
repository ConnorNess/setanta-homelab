Each container in its own dir, check the compose.ymls before running `docker compose up -d`. 

Any dir that has a .env.example needs a .env placed in with the relevant fields so it will work.

Recommended order:
- Plex (feel free to swap to jellyfin etc...)
- Komga (feel free to swap to calibre etc...)
- Gluetun
- qBittorrent
- Sonarr
- Radarr
- FlareSolverr
- Prowlarr
- Bazarr
- Seerr
- Recyclarr
- Tautulli (super optional)
- Cloudflared (Only if you want out of network access)

