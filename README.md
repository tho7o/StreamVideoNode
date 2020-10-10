
# STREAM VIDEO .MP4 FROM NODEJS SERVER

## Install
```
npm install
node server.js
```

## PATH server
```
http://<youripserver>:3000/video
```

It will be enough to play the .mp4 video allocated in ./assets/ folder


## DOCKER

The videos will be played must be in assets folder. 
The docker-compose volumes will add the videos
inside the docker.

## RUN
```
docker-compose up -d --build
```

## PATH server
```
http://<youripserver>:3000/video
```
