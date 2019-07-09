A sample docker project, which runs a python flask in one container and redis in another.

To build use: docker build -t %image name% .  
  
To start the image and expose ports run: docker-compose up -d

Check whether the process is running: docker-compose ps
