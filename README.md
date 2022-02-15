# nodejs-with-docker
This sample app and made for deployment

# Clone the node image in docker

 - Install node with seperate container
  docker run node:version_number
  
 - Enter into installed container bash 
  docker run -i -t node:version_number bash
  
 - Check node version
  node -v
  //output version
  
 - Check NPM version 
  npm -v
  //output npm version.
  
 - List all the docker container
   dokcer ps -a
   
 - Delete the particular image
   docker rm fghjkhghdj
 
 - List all the images
   docker images
   
 - Remove images 
   docker rm image_name
 
 - Monitor all the container 
   watch -n1 -t docker ps -a
   
   ##### Open new terminal and run the below command and look at the watch terminal which you have run previousally.
   
   docker run --rm -it any_container  || docker rmi
   After running the command you can observe container and images will be the deleted.
   
   
   
   
   
 
  
  
