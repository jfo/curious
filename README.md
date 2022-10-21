docker run --name curious-moon -v ./c-moon-vol:/c-moon-vol -e POSTGRES_PASSWORD=mysecretpassword -d -p 5432:5432 postgres
psql -h 127.0.0.1 -U postgres
