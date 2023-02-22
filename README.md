# StudentCoursesRestAPI
This Project consists of flask example with mysql connectivity

This project will be used to demonstrate APIs and Docker connectivity in the subsequent versions

## Architecture of the Application
![Preview](./images/StudentFlaskAppArchitecture.png)

 HOW TO PUSH TO DOCKER REGISTRY 
------------------------------
```
   git clone https://github.com/krishnareddy219/StudentCoursesRestAPI.git
   ls
   cd StudentCoursesRestAPI/
   docker image build -t studentcourseses:1.0 .
   docker login 
   docker image tag studentcourseses:1.0 krishnareddy219/studentcourseses:1.0
   docker image push krishnareddy219/studentcourseses:1.0
```
