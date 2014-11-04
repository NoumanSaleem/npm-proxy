### Private NPM setup
CouchDB/Kappa dockerized

### Setup
Clone and execute `configure` file in project root.
This will start three containers:
- `couchdb` on host port 5984
- `kappa` with command `bash /src/setup` to configure couchdb
- `kappa` on host port 80

