#Results of lab6-microservices

##1st Part - The two microservices are running and registered:

###Accounts service:

![Accounts service](/screenshots/1_accounts.png)

###Web service:

![Web service](/screenshots/1_web.png)

##2nd Part - The service registration service has the two microservices registered

###Dashboard:

![Dashboard](/screenshots/2_dashboard.png)

##3rd Part - Second account microservice is running in the port 4444 and it is registered

![Accounts service 2](/screenshots/3_accounts.png)

##4th Part - Brief report describing what happens when you kill the microservice with port 2222
When accounts service in port 2222 is killed, the service keeps working after a few time down. This is because the web service lost his connection with accounts and try to discover the new accounts service. After find it, the system keeps working normally.