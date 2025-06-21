# Explanation


### We need to make an user interact with an mongo-express web interface likw where it will turn to communicate with mogodb to read and write data

In this we need to setup the database backend and after that database needs a secure way to store its credentials and a stable address for other applications to find it.first we need to set up a secert vault using name secret to store the credientials before this using some command we need to get the admin user and  secretkey output. In this we have to create a secret in yaml file in this file we need to give apiversion as v1 and kind as secret in this we will have our admin user and scret key details.we need to create this secret.yaml with kubernetes using command kubectl apply -f. and next we need to deploy mongodb using deployment and services as kind in this for both there are different type of apiversions and after this run apply command it will create this after this we need to create configmap where it will store the non-confidentalk data and its an api object.till this we done with frontend and now we need to create a backend for this we need to deploy mongo-express uisng externl as service in this some part of coide is missing so here we need to add piece of code like basic authentication for admin user and for password.we can see all things that we are created so we need to use the command get all this will display info about all. For getting the service url we need to use command mongo-express as service then it will display a url or some times it will automatically direct to the webiste and after accessing hte url it will display login authentication we need to give username and password then it will diaply the mongo-express where we can create a database.After this we need to cleanup the services that we create using delete command 


# Deliverables:

![Screenshot (107)](https://github.com/user-attachments/assets/0e8a7d7e-5044-4378-b739-bc78e316c8ca)

![Screenshot (108)](https://github.com/user-attachments/assets/5b7e5d13-2c77-44cb-a558-83a82e347178)

![Screenshot (110)](https://github.com/user-attachments/assets/2cb5b14e-32d9-4f67-bd97-b14094fcedf1)

![Screenshot (111)](https://github.com/user-attachments/assets/32fcbf4d-2c8b-48cc-aca0-c76e8f5c39db)

![Screenshot (112)](https://github.com/user-attachments/assets/7d8ce6b6-f339-453c-852e-cefa69a04b44)








