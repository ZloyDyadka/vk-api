# vk-api [![Build Status](https://secure.travis-ci.org/Andromant/vk-api.png?branch=master)](http://travis-ci.org/Andromant/vk-api)

VK API wrapper for NodeJS

Feel free to use it.
If you have any wishes, you can post it there on GitHub

## Getting Started
Install the module

```javascript
var vk_api = require('vk-api');
var vk = new vk_api({appID: APPID, appSecret: APPSECRET});
    vk.api('users.get', {
        user_ids: id
    }, function(err,result) {
    });
```

=======

Server method

```javascript
var vk_api = require('vk-api');
var vk = new vk_api({appID: APPID, appSecret: APPSECRET});

    vk.api('secure.checkToken',{
        token: userToken,
        ip:    userIP
    }, function(err, result) {
    })
})
```

## Release History
0.1.1 - 03/02/2014
