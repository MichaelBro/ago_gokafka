Build and run project 
```bash
docker-compose up -d
```

Emulate payment
```bash
docker-compose run --rm payments --userId 1 --message "Your payment (150$) is successful"
```

Read logs:
```bash
docker-compose logs tokens
```

For register new push token use test request **./client/requests.http**


