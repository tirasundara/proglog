# Commit Log

## API Testing
- Produce Log - `POST /`
```bash
curl -X POST http://localhost:8080 -d '{"record": {"value": "TGV0J3MgR28gIzEK"}}'
curl -X POST http://localhost:8080 -d '{"record": {"value": "TGV0J3MgR28gIzIK"}}'
curl -X POST http://localhost:8080 -d '{"record": {"value": "TGV0J3MgR28gIzMK"}}'
```

- Consume Log - `GET /`
```bash
curl -X GET http://localhost:8080 -d '{"offset": 0}'
curl -X GET http://localhost:8080 -d '{"offset": 1}'
curl -X GET http://localhost:8080 -d '{"offset": 2}'
```

