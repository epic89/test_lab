# ADMINER is used for managing the database

## Postgresql,Nginx with Docker

### Setup 
`docker-compose up -d`

### Adminer endpoint
[http://localhost](http://localhost)

### Adminer Setup
- System: `PostgreSQL`
- Server: `db`
- Username: `postgres`
- Password: `p@ssw0rd`
- Database: ` ` 

### Useful Commands
```$xslt
docker-compose up -d
docker-compose stop
docker-compose rm -f
docker-compose down --rmi all
```
