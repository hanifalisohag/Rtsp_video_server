# Rtsp_video_server
Building RTSP Video Server
```
docker-compose -f docker-compose.yml build 
```

Running RTSP Video Server
```
docker-compose -f docker-compose.yml up -d rtsp-relay
```

The final rtsp url woud be: 
```
rtsp://<URL>:8554/rtspvideo
```

