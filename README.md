# connectify.js

* Usage:

```sh
  subscribe({
      delay: 100,
      useSockets: true,
      useHTTP: true,
      callback: function () {}
  });
```     
*  to keep sockets connection
```sh
  unsubscribe({
      useSockets: true
  });
```

*  to keep http connection
```sh
  unsubscribe({
      useHTTP: true
  });
```

*  to unsubscribe from all
```sh
  unsubscribe();
```
