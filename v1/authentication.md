---
title: Authentication
type: info
order: 1
---
# Authentication

The sendwithus API uses [HTTP Basic Authentication](http://en.wikipedia.org/wiki/Basic_access_authentication).

All requests require you to authenticate using a sendwithus API Key as the username with an empty string as the password:

```
curl -u live_1234qwerzxcv7890: https://api.sendwithus.com/api/v1
```

All API calls must use HTTPS. Any calls made using HTTP will return an appropriate error code.
