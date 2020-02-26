run 'mvn clean package' in folder to clean.
run 'mvn azure-functions:run' to run on localhost. it will tell you right address. -> usually http://localhost:7071/api/HttpExample

This function listens at endpoint "/api/HttpExample". Two ways to invoke it using "curl" command in bash:
     * 1. curl -d "HTTP Body" {your host}/api/HttpExample
     * 2. curl "{your host}/api/HttpExample?name=HTTP%20Query"

---------------------