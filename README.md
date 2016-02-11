# Request Header Parser Microservice

Create a file named `.env` in the root directory. This file should contain:

```
PORT=8080
APP_URL=http://localhost:8080/
```

### Starting the App

`node server.js` 

### Heroku app

header-parser-api-imadmk.herokuapp.com

### Using this app

     User stories:

        - I can get the IP address, language and operating system for my browser.

Example usage:
header-parser-api-imadmk.herokuapp.com/api/whoami

Example output:
{"ipaddress":"180.245.185.0","language":"en-US","software":"Windows NT 10.0; WOW64; rv:46.0"}