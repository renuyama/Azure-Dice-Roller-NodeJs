
# Dice Roller WebService (Node.js)

This project provides a server-side WebService that generates all random dice values. 
It is designed for deployment on Azure App Service using Windows and iisnode.

## Endpoints

GET /api/ping  
Returns a simple health check response.

GET /api/roll?sides=6&count=2  
Returns dice rolls generated using crypto.randomInt.

GET /api/roll-nocors  
Same as /api/roll but intentionally missing CORS headers.