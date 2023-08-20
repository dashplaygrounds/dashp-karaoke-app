# dashp-karaoke-app

```
sudo mkdir -p /media/jw-songs /media/ke-config
sudo chown -R kubeadmin:kubeadmin /media/jw-songs

docker network create ke-net
docker compose -f ke-compose.yml up -d
```