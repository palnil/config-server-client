# config-server-client
config-server-client

Steps to run Config-Server-Client Demo

1. Checkout all three projects
2. Run ConfigServer (port 9999) - http://localhost:9999/accountdetails/development
3. Run AccountSummaryService (port 8081) set spring.profiles.active=production at runtime - http://localhost:8082/msg
4. Run AccountDetailsService (port 8082) set spring.profiles.active=development at runtime - http://localhost:8081/msg


It uses github repo at https://github.com/palnil/config-public

Enjoy !!
