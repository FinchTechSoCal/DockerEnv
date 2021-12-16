# DockerEnv

##PUID & PGID
These are mainly used for what user has acess to the files. From shell use 'id' to get your user id & group id.
PUID=1000
PGID=1000

TZ=America/Los_Angeles

LOCVOL1=/volume1/docker/
LOCVOL2=/volume2/docker-ssd/

#bridge network for containers
CONNET=dbridge

#host interface & name for macvlan network if needed
HOSTINT=ovs_eth4
HOSTNET=directnet
