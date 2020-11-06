# Sev

**Commands**

- status
	- validate server is running or not
- start
	- runs server jar remotely
-  stop
	- stops server jar remotely 
- upload
	- upload new jar build to server
-  deploy
	- upload jar
	- stops current process 
	- runs new jar 
- restart
	- restarts a jar process
		
**Installation** 
1. Need to copy sev bash file to directory that is already included to $PATH env variable
2. Need to give permission to run
3. In your project folder create a config file .sev_config with variables:

	`user=[user] # server user`
	
	`server=[server] # server ip address`
	
	`jar_server_location=[path] # where you want to copy jar in your`
	
	`server jar_local_location=[path] # where your build located in your computer`
	

4. Enter your project folder and type:
	`sev status`

