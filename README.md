# Rtsp_video_server
Copy the video <file_name>=`input_src.mp4` to the `\src\samples` directory and update the `SOURCE_URL` environmental variable in `docker-compose.yml` file

```
 SOURCE_URL=file:///samples/<file_name>
``` 
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

