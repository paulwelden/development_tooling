# How to build and use this image

## Build the image

docker build -t fabric-cli ./docker/fabric

## Run the image

docker run -it --name fabric \
  -v fabric-data:/root/.fabric \
  fabric-cli
