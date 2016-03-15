# [GetEventStore](https://geteventstore.com/)

Can be found on Docker Hub [tetsuobe/geteventstore](https://hub.docker.com/r/tetsuobe/geteventstore/)

## Defaults

- EXT IP: 0.0.0.0
- EXT HTTP PORT: 2113
- EXT TCP PORT: 1113
- LOG: /data/logs
- DB: /data/db
- MAX MEM TABLE SIZE: 100000
- WORKER THREADS: 12
- RUN PROJECTIONS: All

## Override environment variables

in ```docker-compose.yml```

```
eventstore:
  environment:
    - EVENTSTORE_MEM_DB=True
```