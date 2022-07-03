# todo

## Start Postgres Container
	docker run -d \
		--name some-postgres \
		-p 5432:5432 \
		-e POSTGRES_DB=tododb \
		-e POSTGRES_PASSWORD=password \
		-e PGDATA=/var/lib/postgresql/data/pgdata \
		-v ~/data:/var/lib/postgresql/data \
		postgres

During further access we can use docker start <container ID>

