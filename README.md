# Node-Express-Cassandra CRUD sample Application

This is a simple Node-Express CRUD application using Cassandra.

### Configuration

Cassandra connection configuration requires `CASSANDRA_IP` environment and datacenter name :


Express configuration requires `PORT` environment variable. The default port is 3000: 	

	app.listen(process.env.PORT || 3000);

### How to run

To start the Node application:

	npm install
	npm start

