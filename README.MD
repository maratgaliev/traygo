# TRAYGO API

Golang REST API with GORM, Postgres, JWT

## Run

- `.env` - setup your DB
- `go run main.go` - run API

## Example requests

`http://localhost:9000/api/user/new`

### Request
```json
{
	"email": "kazanlug@gmail.com",
	"password": "kazanlug@gmail.com"
}
```

### Response
```json
{
  "account": {
    "ID": 1,
    "CreatedAt": "2019-11-05T15:04:46.394806-05:00",
    "UpdatedAt": "2019-11-05T15:04:46.394806-05:00",
    "DeletedAt": null,
    "email": "kazanlug@gmail.com",
    "password": "",
    "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJVc2VySWQiOjJ9.bHzCP2yt40ISTCT3bgDju4T-qQfKz1LfbOgGB1qCS68"
  },
  "message": "Account has been created",
  "status": true
}
```
