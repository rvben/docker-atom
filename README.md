# Atom in Docker
Atom - The hackable text editor. Dockerized.  


The beloved Atom editor in Docker, using X11 socket.  


Quick start:
```
docker run -ti -e DISPLAY=$DISPLAY -v /tmp/.X11-unix:/tmp/.X11-unix rvben/atom
```
