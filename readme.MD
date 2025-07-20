## THIS IS FOR USING DOCKER WE CAN CREATE ROBOSHOP PROJECT ###

1. We are using Docker-compose.yaml file to run the images along with containers and it    dependencies

2. while creating images and cointainers for our roboshop is not an option.
   we need to do docker best practices for our roboshop project.

3. we are optimizing images using "alphine os" to reduce the image size in catalogue.

4. We are also creating named volumes to our containers. Because containers are 
   ephemeral by default.If we are removing the containers then it will remove the data by default.

5. We are also using Multi stage Build in our project, to reduce memory and 
   unnecessarey installations in catalogue component.

6. we are also implementing docker layers to reducing cache data to decrease the sizes.
