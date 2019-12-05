# flask_with_docker

Please follow the instruction to run this application

1. create virtual environemt
  ```
  virtualenv -p python3 <envname>
  ```
2. install the requirement.txt file
  ```
  pip install -r requirement.txt
  ```
3.run the application 
  ```
  virtualenv -p python3 simplehttp
  ```
## With Docker

1.Run the following command to install Docker onto your Linux system:
```
sudo apt install docker.io
```
2. Run this command on your system:
  ```
  docker build -t dockertest .
  ```
  This command assigns a name dockertest and a tag latest to your container.
3.After the build is complete, we can run the container by using the following command:

  ```
  docker run -d -p 4000:80 dockertest
  ```
