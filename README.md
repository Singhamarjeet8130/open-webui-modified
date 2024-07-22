Use the below command to install

docker run -d -p 3000:8080 --add-host=host.docker.internal:host-gateway -v open-webui-modified:/app/backend/data --name open-webui-modified --restart always singhamarjeet8130/open-webui-modified:latest
