#FIRST CLONE THE REPOSITORY TO THE SYSTEM 
Fork the repository to your github then clone it to you system using the command
1: git CLONE

#CREATE A BRANCH IN LIKE FEATURE BRANCH
always understand the concept of branching never make any change on main/master branch make a new branch using the command
2: git checkout -b "branch-name"

--------------------------------------------------------------------------------------------------------------------------------
#docker file 
will requird the image tu run over container thus will make a docker file you can use docker init but the best practice is using the dockerfile


from node:18
workdir /app
copy pakages.jason ./
run npm install
expose 5173
cmd ["npm","run","dev"]


After creating the dockerfile build a image using the command 
#build a image 

3: docker build -t "name-of-image" .

-------------------------------------------------------------------------------------------------------------------------------------
#containertization
image is craeted must check using docker images command for command you can use docker --help now make a conatiner using a command

docker run -d --name "container-name" -p 5173:5173 image-name:latest

to check container use 
docker ps ,docker ps -a if container gets fail

docker stop "container_id" && docker rm "conatiner_id" is used to remove non useable conatiner 


------------------------------------------------------------------------------------------------------------------------------------------
#docker compose.yml
make sure your docker compose is downaload 
to download sudo apt-get install docker-compose-v2
version: "3.8"
services:
    name:
      image: 
      container-name:
      ports:

always check you compose file using 
docker compose config
to check error
docker log "id"
to run compose file
docker compose up
to stop or rm conatiner
docker compose down
docker system prune
-----------------------------------------------------------------------------------------------------------------------------------------------------

#you can successfully deploy your website at port no 5173

Note : dont forgot to edit you inbound rules and add 5173 ports

linkedin: "https://www.linkedin.com/in/swayam-nakshane-3b29b0346?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=ios_app"
docker : "https://hub.docker.com/u/swayamnakshane"
github: "https://hub.docker.com/u/swayamnakshane"
------------------------------------------------------------------------------------------------------------------------------------------------------


![Screenshot 2025-02-20 234917](https://github.com/user-attachments/assets/22f51b76-b137-4187-900d-b1628c78ed3c)
-----------------------------------------------------------------------------------------------------------------------------------------------------
-----------------------------------------------------------------------------------------------------------------------------------------------------

![Screenshot 2025-02-20 234624](https://github.com/user-attachments/assets/01c6954b-5d20-4537-9640-42dd0a5b7223)

![Screenshot 2025-02-20 234647](https://github.com/user-attachments/assets/810e3aba-bd4d-47a7-96f4-b216adb588be)

---------------------------------------------------------------------------------------------------------------------------------------------------
![Screenshot 2025-02-20 234711](https://github.com/user-attachments/assets/1f396b09-3057-4c4c-9ca6-d67875ad4dec)
---------------------------------------------------------------------------------------------------------------------------------------------------


![Screenshot 2025-02-20 234825](https://github.com/user-attachments/assets/35a11ba9-4ebb-4876-b917-e9cd51c18dd6)
---------------------------------------------------------------------------------------------------------------------------------------------------

![Screenshot 2025-02-20 234957](https://github.com/user-attachments/assets/6f79ba4c-bbec-47e2-9522-9bfcf0386748)


![Screenshot 2025-02-20 234735](https://github.com/user-attachments/assets/813050b6-bd19-4e7a-bb2f-b35d68e776ad)
#WE ALSO ADDED TO DOKER.HUB
---------------------------------------------------------------------------------------------------------------------------------------------------
