# docker-imdb
Create + Dockerize a python application for scraping data from imdb movies site ('http://www.imdb.com/chart/top'
) and then recommend/suggest a random movie to the user </br >
Libraries used: beautifulsoup, requests

# Steps to run the application on Docker
- Check the docker version installed on the machine

![image](https://user-images.githubusercontent.com/56335301/191912014-b5b83c06-e6b7-48d1-84b4-2ceac2bf37b3.png)

- Create main.py file which contains the script for scraping website data and recommending a random movie to the user, the script keeps recommending
movies continuously to the user continuously until the user inputs 'n'
- Create the docker file (attached in the repository for reference)
- Build docker image

![image](https://user-images.githubusercontent.com/56335301/191912495-075e2dd2-4bc4-4de1-a685-3a2f7bd898d5.png)


- You can see the built image also on Docker desktop UI

![image](https://user-images.githubusercontent.com/56335301/191912538-836e30f7-5731-4bd1-bb11-0db3f58bbba7.png)

In the above image, also observe the steps that are performed in sequence as per the sequence mentioned in the docker file

- Start/run the docker container (while using docker run command with user input -t -i should be used, -t for sudo terminal & -i for interactive mode)

![image](https://user-images.githubusercontent.com/56335301/191917614-01f58192-9efe-464e-b836-c9ccd85ce093.png)

![image](https://user-images.githubusercontent.com/56335301/191917868-7e0c60e1-2d6c-41dc-856b-8f162ae537be.png)


View the container on docker desktop UI as well!

[image](https://user-images.githubusercontent.com/56335301/191917941-b9ba948a-071a-4d7a-a451-37b8194532f5.png)

- Output is nothing but the movie recommended from the app

![image](https://user-images.githubusercontent.com/56335301/191917868-7e0c60e1-2d6c-41dc-856b-8f162ae537be.png)

![image](https://user-images.githubusercontent.com/56335301/191918221-9b7e5555-1719-4bba-8aa9-a3338d27f21d.png)


# Credits
This application is created based on video tutorial by Youtube channel "Python Engineer"


