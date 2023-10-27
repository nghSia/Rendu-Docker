# docker-moster
 
# to build
docker build . -f Dockerfile.moster -t moster


# to run
docker run -d -it --name mosters2 -p "8080:8080" moster
