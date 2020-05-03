# Project-IIECRISE

#Inside the dir.
#Run-
docker build -t project:v1 -f ./Dockerfile.txt .
#after image formtion-
docker run -d --name ok -p 8000:80 project:v1
#open browser-
<localhost>8000
