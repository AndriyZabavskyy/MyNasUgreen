Install docker from UGREEN APPS
Install portainer
Create folders for immich

bash"""
root@NAS:/# tree -L 2 /volume2
/volume2
├── @appstore
   ├── com.ugreen.docker
   ├── com.ugreen.photo
   ├── com.ugreen.snapshot
   └── com.ugreen.syncbackup
├── @docker
   ├── buildkit
   ├── containers
   ├── engine-id
   ├── image
   ├── network
   ├── overlay2
   ├── plugins
   ├── runtimes
   ├── swarm
   ├── tmp
   └── volumes
├── docker
   ├── immich
   └── portainer
├── @exif
   └── dc
├── lost+found
├── @tmp
├── @uninstall
└── @upload

26 directories, 1 file
root@NAS:/#
"""

bash"""
root@NAS:/# tree  /volume2/docker/immich/
/volume2/docker/immich/
├── cache
├── db
├── matplotlib
   └── fontlist-v390.json
├── micro
└── redis

6 directories, 1 file

"""
