# TASK 7 — Monitor System Resources Using Netdata

## Objective
Install Netdata and visualize system and app performance metrics.

## How I ran Netdata
- Docker image: `netdata/netdata`
- Command used (recommended mode):

docker run -d --name=netdata -p 19999:19999 --cap-add=SYS_PTRACE --cap-add=SYS_ADMIN -v /proc:/host/proc:ro -v /sys:/host/sys:ro -v /etc/passwd:/host/etc/passwd:ro -v /var/run/docker.sock:/var/run/docker.sock:ro --restart unless-stopped netdata/netdata

Below are the Screenshots attached step by step:-

<img width="1916" height="1079" alt="Screenshot 2025-10-02 105455" src="https://github.com/user-attachments/assets/f828c61e-53b9-4215-8bd4-608a537f67a5" />
<img width="1917" height="1051" alt="Screenshot 2025-10-02 105444" src="https://github.com/user-attachments/assets/f2640c21-2284-4781-9839-37a977973f43" />
<img width="1919" height="949" alt="Screenshot 2025-10-02 105249" src="https://github.com/user-attachments/assets/2b271d86-63d8-4a63-86fe-cff3a61610cd" />
<img width="1919" height="949" alt="Screenshot 2025-10-02 105226" src="https://github.com/user-attachments/assets/52d8071d-7e6d-41a8-b819-5a8a2c4a1501" />
<img width="1919" height="1019" alt="Screenshot 2025-10-02 105211" src="https://github.com/user-attachments/assets/984660c6-59a4-4917-81a0-daf5e22a42a9" />
<img width="1914" height="1078" alt="Screenshot 2025-10-02 104917" src="https://github.com/user-attachments/assets/a9cc9814-7f11-4691-9e01-775cddf9d6dd" />

Then, finally intiated git into this directory and pushed README.md file mentioning everything.

<img width="1912" height="1074" alt="Screenshot 2025-10-02 110413" src="https://github.com/user-attachments/assets/fcd6d06a-f8c0-4b17-9e62-05697d8fd772" />
<img width="1902" height="1061" alt="Screenshot 2025-10-02 110404" src="https://github.com/user-attachments/assets/2f244089-ac48-4566-a238-529e35a969db" />



