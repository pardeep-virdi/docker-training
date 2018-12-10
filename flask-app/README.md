docker build -t pardeepvirdi/myfirstapp .

#  login to user
docker login
docker push pardeepvirdi/myfirstapp
docker run -p 8888:5000 --name myfirstapp YOUR_USERNAME/myfirstapp
