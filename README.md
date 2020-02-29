# apcups-docker for arm

git clone https://github.com/Naobana/apcups-docker.git  
cd apcups-docker  
docker build -t apcupsd .  
docker run --device=/dev/usb/hiddev0 --detach --rm --name apcupsd apcupsd  
docker exec -it apcupsd apcaccess

# credits
https://github.com/fopina/docker-apcupsd
