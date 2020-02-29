# apcups-docker for arm

git clone https://github.com/Naobana/apcups-docker.git  
cd apcups-docker  
(sudo) docker build -t apcupsd .  
(sudo) docker run --device=/dev/usb/hiddev0 --detach --rm --name apcupsd apcupsd  
(sudo) docker exec -it apcupsd apcaccess

# credits
https://github.com/fopina/docker-apcupsd
