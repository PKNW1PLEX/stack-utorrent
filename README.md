
# PKNW1-PLEX 
### stack-utorrent

```
docker image : 
docker run -d --restart=always --priviliged --name=utorrent \
           -v ./data/config:/config -v ./data/data:/data -v /:/hostro:ro -v /:/host \
           -p 48080:8080 \
           linuxserver/utserver

```

```
Encrypted Plex Stack - DEPLOYMENT TEST

- data                                  - config
- scripts

- utorrent                              - torwww
- sickrage                              - www-ca
- couchpotato                           - www-www
- htpc 
- owncloud

www.pknw1.co.uk | plex.pknw1.co.uk

```



