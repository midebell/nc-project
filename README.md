# ncloud

# Solution

# Read me should explain how to run docker compose locally to bring up the environment 
Clone this repo
Run "docker-compose up -d"

# Read me on how to deploy the app to ecs 
Run terraform apply
docker build -t "your ecr url"
log in to ecr using aws ecr get-login
docker push "tagged image"

