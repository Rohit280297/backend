# Research Kernel's Backend 

### Steps to run without docker :

1. Clone this repository on your local machine
2. Create .env file from env.example file
3. Run npm install into the terminal 
4. Sever will start on port 3000

### Steps to run with docker :

1. Run Docker command to build image from dockerfile `docker build --rm -f "Dockerfile" -t backend:latest-production .`
2. Run Image in Docker `docker run -i -t -d -p 3000:3000  backend:latest-production .`
3. It's better if you use Docker extension available in VSCode.




