# Mailchimp Newsletter Website
In this project I have used the mailchimp API, to create a newsletter website

# Running Project locally
- Clone repository
- change directory
```terminal
cd mailchimp-newsletter
```
- Get list ID and API Key from mailchimp and add in app.js

```code
  var options={
        url: "https://${dc}.api.mailchimp.com/3.0/lists/${listId}",
        method: "POST",
        headers: {
            "Authorization" : "Pratyay ${API-Key}"
        },
        body: jsonData
    };
```
- Run project

```terminal
node app.js
```

![alt text](https://github.com/PratyayMallik1006/mailchimp-newsletter/blob/main/screenshots/signup.PNG?raw=true)
