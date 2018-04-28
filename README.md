# HTTP SERVER
version 1.0.0

This program uses a server module that is responsible for creating an http server. It defines all route behavior and exports an interface for starting and stopping the server. 

## HTTPie commands
```http POST :3000/pathname name=yourName
http GET :3000/pathname text=="foo bar"
```

### GET/
When you make a GET request the server sends back html with a project description and an achor to /cowsay.

```Get api/v1/cowsay?text={yourMessage}
```

### POST /api/cowsay
When a user makes a POST request to /api/cowsay it sends back  a JSON body that includes `{"content": "<cowsay cow>"}`.


Developed by Josiah Green

