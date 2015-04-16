# ip-validator
Super simple IP Address validator for ipv4 &amp; ipv6

```javascript
var validator = require('ip-validator');

var ipv4 = "212.212.100.110"
var ipv6 = "0000:0000:0000:0000:0000:0000:0000:0001"

validator.ipv4(ipv4); // true
validator.ipv4(ipv6); // false

validator.ipv6(ipv4); // false
validator.ipv6(ipv6); // true

validator.ip(ipv4); // true
validator.ip(ipv6); // true

```
