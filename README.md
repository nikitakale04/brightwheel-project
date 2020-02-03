# brightwheel-project

# to start the application run following command from /email-service
./mvnw spring-boot:run

# Changes to be added to application.properties before starting the application
1. service name
emailServiceProvider.serviceName=mailgun 
or
emailServiceProvider.serviceName=sendgrid

2. Add the api keys
mailgun.apiKey=
sendgrid.apiKey=

3. Add your domain name for mailgun

# Note that
1. sendgrid message can be found in spam emails
