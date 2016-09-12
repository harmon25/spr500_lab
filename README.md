# spr500_lab

SPR500 Lab environment using docker containers + docker compose.

## Getting Started
Clone repository
`git clone https://github.com/harmon25/spr500_lab.git`

Install Docker Compose
```
sudo -i curl -L https://github.com/docker/compose/releases/download/1.8.0/docker-compose-`uname -s`-`uname -m` > /usr/local/bin/docker-compose
sudo chmod +x /usr/local/bin/docker-compose
```

Launch Lab Infrastrucure
```
cd spr500_lab
docker-compose up
```

- Logs available via ELK stack container
- can SSH into, or attach to container environment to change firewall rules

