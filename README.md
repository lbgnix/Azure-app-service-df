# Azure-app-service-df
Azure-app-service-df

docker run --rm -it --network none -v $(pwd):/input:rw pmsipilot/docker-compose-viz render -m image --output-file output/docker-compose.png docker-compose.yml
