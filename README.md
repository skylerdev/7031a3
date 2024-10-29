# 7031a3
React native implementation of Assignment 3 for COMP 7031

# client-api

To run the client API, you need Node.js
cd client-api
npm install
node server.js

This will launch a server on port 3000 on your local machine.

Endpoints:
	/clients
		Returns list of clients in JSON format
	/clients/:id
		Returns further details about specific client with this ID
	/photos/:photoname
		Serves photo with id statically. 