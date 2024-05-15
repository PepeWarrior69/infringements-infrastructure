1) Build analyzer image: https://github.com/PepeWarrior69/infringements-id
2) Build backend image: https://github.com/PepeWarrior69/infringements-backend
3) Run infrastructure `docker-compose up -d`

Somehow there is a problem with networking and we can't use service name as a hostname. So you have to update `docker-compose.yml` with your IP address 