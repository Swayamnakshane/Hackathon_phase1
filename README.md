#FIRST CLONE THE REPOSITORY TO THE SYSTEM 

1: git CLONE

#CREATE A BRANCH IN LIKE FEATURE BRANCH

2: git checkout -b "branch-name"

--------------------------------------------------------------------------------------------------------------------------------
#docker file 

from node:18
workdir /app
copy pakages.jason ./
run npm install
expose 5173
cmd ["npm","run","dev"]

#build a image 

3: docker build -t "name-of-image" .

-------------------------------------------------------------------------------------------------------------------------------------
#containertization

docker run -d --name "container-name" -p 5173:5173 image-name:latest

------------------------------------------------------------------------------------------------------------------------------------------
#docker compose.yml

version: "3.8"
services:
    name:
      image: 
      container-name:
      ports:
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
