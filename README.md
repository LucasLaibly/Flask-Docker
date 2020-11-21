# Flask / Docker Container Base

Have a base python image to use. Current image is single stage, looking into multi stage compatiability with Redis. 

Build:
1. `docker build -t <imageName> .` 
2. `docker run -d -p 5000:5000 <imageName>`

Down:
1. `docker stop <imageid>`