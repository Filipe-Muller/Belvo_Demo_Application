# Belvo Demo Application

This is a guide explaining how to initialize the Application Demo for the Belvo Technical Challenge.

<ul><li> Note: For this process, I'm using the Ubuntu 20.04 LTS, so all the mentioned steps will be referred to the same OS. </ul>

# Prerequisites

You must have some python libraries configured in your environment before trying to run those applications·
```
belvo-python >= 0.24
click == 6.7
Flask >= 0.12.3
itsdangerous == 0.24
Jinja2 >= 2.9.5
MarkupSafe == 0.23
Werkzeug >= 0.14
requests == 2.24.0
flask-cors
pytest
pytest-flask
CORS ORIGINS disabled in the env
```
# How to run the application

This application is pretty easy to be initialized. You'll need to follow these steps:

1) Clone this repo to your local machine

```
git clone https://github.com/Filipe-Muller/Belvo_Application_Demo.git
```
2) Open and edit the .env file with your API credentials, that can be obtained in the Belvo dashboard

3) Open your terminal and access the folder where the repo is located, after that please run the following command
```
make run
```
4) You'll need to open the address provided at the end of the code execution in the terminal in any browser that you use
```
localhost:8080
```
5) After that, you'll have access to the Demo Application and can proceed with some tests

![image](https://user-images.githubusercontent.com/85353297/174397672-b8b3c7c8-1b2e-4127-9742-664df930dd61.png)

# Feedback

The API is quite easy to use and to understand all the functionalities, but I had some issues with the MFA process. For me, the documentation was not very clear.

Regarding the widget, his design is quite remarkable and efficient (for the proposal), I didn't face any issues with him (beside some CORS errors in my localhost).

For improvements, I would review the guide documentation and add more information about, because I felt that some topics were explained only at the surface level (without examples). I would review the access_mode to introduce an easy way to modify that in the app (as per user choice).

For the API, I don't have any improvements to suggest, facing that the API is already amazing and does a great job.
