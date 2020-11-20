Sample app to deploy the asp.net application in docker container.
command to build docker image 
cd to directory of dockerfiler

To build docker image

docker build -t sampleapp .

to run the doker image
docker run -it --rm -p 5000:80 sampleapp
you can then access the http://localhost:5000/ to verify the app running in web

What docker file is doing:

This docker file publishes the source code and stores the content to app directory
when you run the docker images it deployes the code and run the application on the web.
 


 


    





