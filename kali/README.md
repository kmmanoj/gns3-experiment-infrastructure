# Attacking machine

Attacking machine

* Start the kali docker container by running `docker run -it kalilinux/kali-rolling`
* Then run `apt-get update` followed by `apt-get install kali-linux-headless`
* Then, from the host computer, run `docker commit <container_id> <image_name>:<tag>`
* Persist the directory `/data/` (to edit code from host computer) in GNS3, when creating the container template 
