# docker-quick-builds
Repository of Docker compose files for local development.

The Files containt docker-compose.yml files for any local development purpose. As it is for local development purpose the user and password is givel as `admin`
and `admin!`. Please do care about it and do not use such weak credentials in production use.

After cloning the following repo. and going to some specific folder, if you run `docker-compose up` It will create a new container and the persistant data
to a local folder to store the data. If you want to run the app in detach mode you can use `docler-compose up -d`, which will init. the app in background.

The compose files is test on Debian based machine and should works for unix system also. 
