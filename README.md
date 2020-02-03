# brightwheel-project

# to start the application run following command from /email-service
./mvnw spring-boot:run

# Changes to be added to application.properties before starting the application
1. service name
emailServiceProvider.serviceName=mailgun 
or 
emailServiceProvider.serviceName=sendgrid

2. Add the api keys
mailgun.apiKey= and 
sendgrid.apiKey=

3. Add your domain name for mailgun 
mailgun.domainName=

# Following is Swagger doc link
http://localhost:8080/swagger-ui.html

# Following is the sample POST object from swagger
{
  "body": "<h1>Your Bill</h><p>$10</p>",
  "from": "noreply@mybrightwheel.com",
  "from_name": "brightwheel swagger",
  "subject": "brightwheel test email",
  "to": "nikita.kale.nov89@gmail.com",
  "to_name": "nikita"
}

# Note that
1. sendgrid message can be found in spam emails
