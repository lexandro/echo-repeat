echo-repeat
===========

This docker image created to test repetitive console output related activities with Docker. 

The image is printing the current time and the container name in every second.

Usage:
======
docker run -d --name=repeat lexandro/echo-repeat

Then you have a container named 'repeat' that runs in the background until get stopped.
