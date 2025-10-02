# TASK 7 — Monitor System Resources Using Netdata

## Objective
Install Netdata and visualize system and app performance metrics.

## How I ran Netdata
- Docker image: `netdata/netdata`
- Command used (recommended mode):

docker run -d --name=netdata -p 19999:19999 --cap-add=SYS_PTRACE --cap-add=SYS_ADMIN -v /proc:/host/proc:ro -v /sys:/host/sys:ro -v /etc/passwd:/host/etc/passwd:ro -v /var/run/docker.sock:/var/run/docker.sock:ro --restart unless-stopped netdata/netdata

Below are the Screenshots attached step by step:-

