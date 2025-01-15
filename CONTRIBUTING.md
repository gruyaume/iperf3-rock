# Contributing

## Build and deploy

```bash
rockcraft pack -v
sudo rockcraft.skopeo --insecure-policy copy oci-archive:iperf3_3.17.1_amd64.rock docker-daemon:iperf3:3.17.1
docker run iperf3:3.17.1
```
