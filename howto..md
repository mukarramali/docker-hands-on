# Using swarm to deploy stack in multiple VMs

- Create two VMs

- SSH into one vm, and swarm init

- SSH into another vm, join the swarm

- In local terminal set vm1's env: eval (docker-machine env vm1)

- In your current dir, docker stack deploy

- docker-compose file should have multiple services

- In browser, <vm ip>:4000 for web app

- In browser, <vm ip>:8080 for virtualizer app

