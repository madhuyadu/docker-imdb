# docker-imdb
Create + Dockerize a python application for scraping data from imdb movies site ('http://www.imdb.com/chart/top'
) and then recommend/suggest a random movie to the user </br >
Libraries used: beautifulsoup, requests

# Steps to run the application on Docker
- Create main.py file which contains the script for scraping website data and recommending a random movie to the user, the script keeps recommending
movies continuously to the user continuously until the user inputs 'n'
- Create the docker file (attached in the repository for reference)
- Build docker image

![image](https://user-images.githubusercontent.com/56335301/191912495-075e2dd2-4bc4-4de1-a685-3a2f7bd898d5.png)


- You can see the built image also on Docker desktop UI

![image](https://user-images.githubusercontent.com/56335301/191912538-836e30f7-5731-4bd1-bb11-0db3f58bbba7.png)

In the above image, also observe the steps that are performed in sequence as per the sequence mentioned in the docker file

- Start/run the docker container



# Check the docker version installed on the machine

![image](https://user-images.githubusercontent.com/56335301/191912014-b5b83c06-e6b7-48d1-84b4-2ceac2bf37b3.png)

