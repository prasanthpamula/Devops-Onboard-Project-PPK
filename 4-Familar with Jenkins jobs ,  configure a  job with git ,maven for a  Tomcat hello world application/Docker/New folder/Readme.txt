#Building an image
docker image build -t openmrs .

#listing images 
docker images

#Running openmrs java application container 
docker run -d -p 8080 openmrs

# greping openmrs to know container
docker ps -a

#inspecting container to know ip address to validate application
docker inspect 14ff7ff89d85
