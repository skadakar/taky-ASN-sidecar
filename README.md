### TAKY ASN Server sidecar

https://github.com/skadakar/taky-rtsp-sidecar

https://hub.docker.com/r/skadakar/taky-rtsp-sidecar



Self contained RTSP missing link for taky, forcing 8554 port usage and RTSP.

It will also keep track of peoples last locations and attempt to match locations of videofeeds to users with the same name.

Bob1 will be given the same location as rtsp://example.com/Bob1

This implimentation is TAKY specific, in that it uses the TAKY monitoring port instead of SSL.

#### The RTSP Sidecar MUST be located on the same host as the RTSP server!

Overwrite settings by attaching config files to the /data/ folder, as with normal node-red docker.

Supported env variables:
```
    environment:
      - SERVER_ID=Something
```


### Bonus feature!

Add `del`as a remark to any marker you want gone. For a better version of this check forcedelete from Hayt here:

https://drive.google.com/drive/folders/1o8tsalgxUGxdg2HiDw5xVu_-bnr63F3d?usp=sharing

