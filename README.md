# DockerApacheWebsite

|   I created a dockerized apache website hosting my very own resume!   |
|:-----------------:|

Want to see?
Clone my branch and run these following commands:
```
docker build -t apache .
```
This will build the image and add a tag called apache
<br><br>
```
docker run -dit --rm --name docker-resume apache
```
This will create and run a container called "docker-resume". Container will be deleted once stopped.
<br><br>
Now use this link to see my resume!
```
localhost:8080/
```
