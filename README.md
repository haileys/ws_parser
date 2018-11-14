# ws_parser

ws_parser is a streaming parser for the WebSocket protocol ([RFC 6455](https://tools.ietf.org/html/rfc6455)).

This library is loosely inspired by [joyent/http_parser](https://github.com/joyent/http-parser) and shares many of the same attributes: it has no dependencies, makes no allocations or syscalls, and only requires 16 bytes of memory to maintain its parse state.
