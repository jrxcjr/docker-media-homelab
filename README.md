# docker-media-homelab
This is a repo that houses the dockerfile for setting up the media setup in my homelab.

The services that are contained in the dockerfile allow you to setup a media server that downloads torrents via indexers that are setup in sonarr/radarr (that organize the files and tracks the media downloads).

The way to stream the downloaded in sonarr/radarr, you need to setup the Jellyfin server and access it in any of the available devices that have the jellyfin app.

To better run this setup and easily access and setup on the associated devices, it is highly recommended that you setup a static ip for your host network or a reverse proxy with the properly ssl certificates.