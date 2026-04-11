Access the app
  frontend http://localhost
  backend  http://localhost:3001


Ports
  nginx   80
  backend(nodejs)  3001
  DB (postgres)    5432


API EndPoints
  GET /api/health - Health check
  GET /api/items - List all items
  POST /api/items - Create new item  


Environment Variables

 Backend
  PORT 	            3001 	API port
  DATABASE_URL 	- 	PostgreSQL connection string


  Database 
   POSTGRES_USER 	    app 	  Database user
   POSTGRES_PASSWORD 	secret 	  Database password
   POSTGRES_DB 	        myapp 	  Database name




----------------------------------

docker exec -u root agent3 chmod 666 /var/run/docker.sock











