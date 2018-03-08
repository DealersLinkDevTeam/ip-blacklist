# node-express-ip-blacklist

`node-express-ip-blacklist` is a cache-based, automatic, IP blacklist for use with [`expressJS`](https://www.npmjs.com/package/express). It caches  a store of IP addresses used to make bad requests and then temporarily blocks requests from those sources once a threshold of bad requests has been exceeded. In this way it is possible to limit access of bad actors to any system.


# [Installation](#installation)
<a name="installation"></a>

```shell
npm install @dealerslink/express-ip-blacklist
```

# [Usage](#usage)
<a name="usage"></a>

```js
const IPBlacklist = require('@dealerslink/node-express-ip-blacklist');
ipBlacklist = new IPBlacklist('blacklist');
```

See wiki for more details.
