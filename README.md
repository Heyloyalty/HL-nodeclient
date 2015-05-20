# HeyLoyalty Node ApiClient

## Usage

```js
var api_key = 'HL-API-KEY';
var api_sec = 'HL-API-SECRET';

var Client = require('./client.js');
var client = new Client(api_key, api_sec);

client.getListClient().getAll(function(err, json) {console.log(json)});
```


