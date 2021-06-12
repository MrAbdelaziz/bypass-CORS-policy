# bypass-CORS-policy

using: web proxy +  axios

## axios cdn

```html
  <script src="https://cdn.jsdelivr.net/npm/axios/dist/axios.min.js"></script>
```
## script

```javscript 
    // get request 
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
