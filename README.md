# testLab10
## 1.2
```
docker compose up -d

```

## 1.3
```
docker compose down

```

## 1.4

Restart
```
docker compose up -d

```
Show Docker Volumes
```
docker volume ls

```

## 1.5 

Step 1: Shut Down the Cluster
```
docker compose down

```
Step 2: Find the Volume Name
```
docker volume ls

```
Step 3: Remove the Volume
```
docker volume rm <volume_name>
```
Step 4: Restart the Containers
```
docker compose up -d

```
Step 5: Verify the Reset
```
http://localhost:9000
```
