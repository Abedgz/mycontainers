# Assignment #1

## Dockerize your applcation
🐋 Create a Dockerfile and dockerize the attached python web application [app.py](../../materials/app.py):

✔️ The image will be based on the alpine:3.9

✔️ Make sure you mark yourself as the maintainer

✔️ The image should update package repository and install python3

✔️ The image should have the following python packages installed:

    📦 Click==7.0

    📦 Flask==1.0.2

    📦 itsdangerous==1.1.0

    📦 Jinja2==2.10

    📦 MarkupSafe==1.1.1

    📦 Werkzeug==0.14.1

✔️ The image should contain our app

✔️ Push your newly created image to your dockerhub account

✔️ Run a container deamon from your newly created image and map it to a port on your host 
> HINT: the webserver is using port 5000)

🦉 Deliverables:

✔️ Access the dockerized web application and save 2 screen captures from your browser :

    📷 Print the browser screen with the webpage you got on the default server path (/)

    📷 Print the browser screen with the webpage you got on the goaway server path (/goaway)

✔️ Save the following files in your personal git repo and attach the link to this assignment:

    📁Dockerfile

    📁Application file (app.py)

    📁Any other file you think are required for the docker build to succeed

✔️ Attach a link to your dockerhub repo with the required image

# 🏁 That's it your'e done!🏁 

![](https://media.giphy.com/media/7FgDPLLKh1v4d2XLkl/giphy.gif)