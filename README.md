# ansible-docker-playground
This is a docker setup I modified to get a playground for the mastering ansible udemy course 

`docker-compose up --build -d`

`docker container exec -it udemy-ansible_control_1 bash`

`ansible all -m ping`

`exit`

`docker-compose down --remove-orphan`

