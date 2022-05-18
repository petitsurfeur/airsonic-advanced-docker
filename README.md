# airsonic-advanced-docker

If problem, see logs
docker logs XXXX

ln: /var/airsonic/transcode/ffmpeg/ffmpeg: cannot overwrite directory
Docker USER id: 0
Docker PUID env: 1001
Docker USER group: 0
Docker PGID env: 1001
usermod: no changes
Process will run as:
User: 1001
Group: 1001

-> Give correct rights 
chown airsonic:airsonic airsonic/
