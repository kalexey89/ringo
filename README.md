# Pings
Pings is a small and simply utility to ping webservers from client-side (browser)

## Usage
```js
const ping = require('pings');

ping('https://domain.com', (error, status) => console.log(error, status), 3000);
// $ null "online"
```
