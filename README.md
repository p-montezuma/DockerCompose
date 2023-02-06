Command to start the dynamic Selenium Grid (will start multiple instances of Chrome, Edge, and Firefox, managed by Selenium Grid):

```
docker-compose -f docker-compose-v3-dynamic-grid.yml up
```

Command to start the hub and nodes in Selenium Grid (will start one instances of Chrome, Edge, and Firefox):

```
 docker-compose -f docker-compose-v3.yml up
```


Command to start the hub and nodes in Selenium Grid (will start 5 instances of Chrome, and one of Edge, and Firefox):

```
docker-compose -f docker-compose-v3.yml up --scale chrome=3
```
