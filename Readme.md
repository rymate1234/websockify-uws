# websockify-uws

[websockify](https://github.com/novnc/websockify/blob/master/other/js/websockify.js) by Joel Martin
modified to work with the high-performance [uWebSockets](https://github.com/uWebSockets/uWebSockets)
library, modernized and published to npm as an easy-to-use package.

## How to use

```bash
npm install -g websockify-uws
websockify [source_addr:]source_port target_addr:target_port
```

### Options

- `[--web dir]` serves files statically under `dir` with automatic indexing
- `[--cert cert.pem [--key key.pem]]` serves over SSL

## License

AGPL (per original license)

Copyright Joel Martin ® 2012
Copyright Zeit, Inc. ® 2017
