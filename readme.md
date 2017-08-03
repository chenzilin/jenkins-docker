Usage:

	1. Run Container
		sudo docker-compose up -d

	2. Enter Container
		sudo docker exec -it autoio-jenkins-docker /bin/bash

	3. Stop Container
		sudo docker stop autoio-jenkins-docker

Version: 1.0

Login: admin:autoio-admin:autoio_jenkins_admin


Reference:

Create Image:

	cd autoio-jenkins-docker/

	sudo docker build -t autoio-jenkins-docker:v1.0 .

List Images:

	sudo docker images

Remeve Image:

	sudo docker rmi 7d9495d03763

	sudo docker image remove 7d9495d03763

Run Container:

	sudo docker-compose up -d

List Containers:

	sudo docker ps

	sudo docker ps -a

Remove Container:

	sudo docker rm d48b68282c03
