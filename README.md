# docker-unifi-video
Unifi Video Controller Software Running in Docker

##More details to be added however in the mean time:
Big thank you to ctindale for the work on creating the initial docker image for this and his helpful guidance on the UBNT forums.

From within the cloned folder run:

docker-compose up -d

Browse to https://ipaddress:7443 to access the gui stup wizard.

Data from inside the container at /var/lib/unifi-video will be stored in your cloned folder/data, ensure you have enough space on this drive else choose a different volume mount point with lots of free space for the video recordings.
