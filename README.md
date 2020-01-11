# dash-meinheld-gunicorn-docker

This repository provides a template to easily get started with a dash application.  

Dependencies: Docker

### Usage
Navigate inside the directory of the OS you want to use, such as 'python3.7-alpine3.8'  
From there, run the following:  
```
sudo docker build -t mydash ./  

```
This will build the image and name is 'mydash'. Next,:  
```
sudo docker run -p 5446:80 mydash
```
This will run the docker image created earlier.  
If you want to run the program in the background, simply add the -d flag:
```
sudo docker run -d -p 5446:80 mydash
```

Now navigate to 0.0.0.0:5446 to view the application.  
To customize your dash application, simply edit the app.py file.  
Documentation on dash can be found here: https://dash.plot.ly/  

Good luck with your project!
