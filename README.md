# moresand-helloworld

Step 1 - Installing Docker

Step 2 — Installing Docker Compose

Step 3 - Create Hello world Docker File

	I - Create to Sample Helow world Appication using docker image
	
		docker build -t moresand-hello-world:1.1 .

	II - Run Hello World Docker Image

		docker run -d -p 8080:8080 moresand-hello-world:1.1

		Link - http://localhost:8080/sample/

Step 4 - Create Nginx Docker File

	I - Create to Nginx using docker image
	
		docker build -t moresand-nginx:1.1 .

	II - Run Nginx Docker Image

		docker run -d -p 80:80 moresand-nginx:1.1

		Link - http://localhost/sample/

Step 5 - Create Maria-DB database Docker File

	I - Create to maria-DB using docker image

		docker build -t moresand-mariadb .

	II - Run maria-DB Docker Image
	
		docker run -d -p 3306:3306 --name moresand-mariadb -e MYSQL_ROOT_PASSWORD=123456 moresand-mariadb