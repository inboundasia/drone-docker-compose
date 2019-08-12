# Github

ngrok http 80

修改 Github 上的 Authorization callback URL
https://github.com/settings/applications/1115192

docker-compose -f server/docker-compose.yaml up
docker-compose -f agent/docker-compose.yaml up

# Drone Cli

export DRONE_SERVER=https://a92a518e.ngrok.io
export DRONE_TOKEN=hkfoCcZALijhuPlKOffv7vNIojtyaAKt
drone info