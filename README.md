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
![image](https://user-images.githubusercontent.com/27902633/177020974-990de7b5-dd3a-4a82-b829-ec4c605a4022.png)

