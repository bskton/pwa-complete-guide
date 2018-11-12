# Progressive Web Apps - Complete Guide
This source code is part of Maximilian Schwarzmüller's "Progressive Web Apps - Complete Guide" course.

# How to Use
You need Docker installed on your machine.

Once Docker is installed, open your command prompt or terminal and **navigate into this project folder**. There, run `docker run --rm -it -v $PWD:/app -w /app -u $(id -u):$(id -g) node:10.12.0 npm install` to install all required dependencies.

Finally, run `docker-compuse up` to start the development server and visit [localhost:8080](http://localhost:8080) to see the running application.
