#### remove all running and exited containers

```docker rm  -f $(docker ps -a -q)```

#### Go inside container as root

```docker exec -it 731187e088bd bash```
