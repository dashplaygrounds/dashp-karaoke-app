# dashp-karaoke-app

```
sudo mkdir -p /jw-songs /ke-config
sudo chown -R kubeadmin:kubeadmin /jw-songs

docker network create ke-net
docker compose -f ke-compose.yml up -d
```