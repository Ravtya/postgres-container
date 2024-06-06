### Prerequisites

- Download .yml file from this repository
- Install & start Docker Desktop: https://docs.docker.com/engine/install/

### Running the container

- Run the following comand in your terminal

```powershell
docker compose up -d
```

- Open http://localhost:8888/ in your browser
	- Login: `admin@admin.com`
	- Password: `admin`

- Select **Add new server** and move to the **Connection** tab
  - Host name/address: `host.docker.internal`
  - Username: `postgres`
  - Password: `admin`
