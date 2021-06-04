# bypass-CORS-policy

using: web proxy +  axios

```javscript 
    // Make a request for a user with a given ID
        axios.get('https://edu.glogster.com/proxy?url=[api link]')
        .then(function (response) {
            // handle success
            console.log(response);
        })
        .catch(function (error) {
            // handle error
            console.log(error);
        })
        .then(function () {
            // always executed
        });
```
