# sscs-chipathon-2025-sharc-team-1

Based on the guide from:  https://github.com/iic-jku/iic-osic-tools?tab=readme-ov-file#434-installing-x11-server

Guide for Macbooks

1. Install docker
  
2. Clone the tools repo

`git clone --depth=1 https://github.com/iic-jku/iic-osic-tools.git`
  
5. create the docker container from the image
   
  in the terminal:
  
    `cd <Dockerfile_Directory>
    
    docker build . `
    
3. Install X Quartz
   
   `brew install xquartz` 

4. change xquartz settings

  - disable "authenticate connections"
  - enable  "allow connections from network clients"

4. Use x11 forwarding for GUI
   
` ./start_x.sh `
