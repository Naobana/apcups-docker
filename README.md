# apcups-docker

sudo docker run --device=/dev/usb/hiddev0 --detach --rm --name apcupsd apcupsd/latest
sudo docker exec -it apcupsd apcaccess

# credits
https://github.com/fopina/docker-apcupsd
