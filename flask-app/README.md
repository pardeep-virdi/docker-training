docker build -t pardeepvirdi/myfirstapp .

#  login to user
docker login

# push to docker hub
docker push pardeepvirdi/myfirstapp

# run the container and map to user
docker run -p 8888:5000 --name myfirstapp YOUR_USERNAME/myfirstapp
