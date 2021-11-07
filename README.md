This example shows how 2 separate containers can interact with each other over the default "bridge" network using container IPs but not the container name. 

# go to these individual dirs and run:
cd redis
docker-compose up --build

cd ../flask
# start flask app container
docker-compose up --build

#run curl on http://localhost:5001
it should work

