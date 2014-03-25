# Client library for the yammer api.

[![Build Status](https://travis-ci.org/polotek/node-yammer.svg?branch=master)](https://travis-ci.org/polotek/node-yammer)

```
var Yammer = new require('node-yammer').Yammer;

// oauth2 access token
var yam = new Yammer({ access_token: token });
yam.messages(function(res, body) {
  console.log(body.messages);
});
```

Docs coming soon. But the method names in the source are pretty straight forward.
