I reached the part of the tutorial with firebase, realised I was spending 80% of my time fixing dependency issues (the course is five years old), so bailed and decided to leave here for now.

### Run

`cd` and `npm install` in each dir (including root directory to install `concurrently`), then run `npm start` from root

### BE

Set up Docker MySQL:

`docker pull mysql:latest`

`docker run -d -p 3306:3306 --name mysql-container -e MYSQL_ROOT_PASSWORD=my-secret-pw -v mysql-data:/var/lib/mysql mysql:latest`

[DB schema](./buy-and-sell-backend/database.sql)
