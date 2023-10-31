
# TestApp Player 

## Requirements

* Install git 
* Check out the deployment repository 
* Install docker engine 
* Install docker compose

## Run as Docker Container

1. Switch to docker directory (cd docker)
2. Execute ./start.sh to start the TestApp Player
3. Execute ./stop.sh to stop the TestApp Player

## Application URLs

* Player: http://localhost
* Editor: http://localhost:8080
* Default login for the editor:
	* user: IRTlibAdmin
	* pwd: test123
* To update the default password:
	* `sudo htpasswd  ./nginx/.htpasswd IRTlibAdmin` 
