# Universal Receiver (WIP)

A client to receive incoming data in an agnostic way. Can accept and parse any GET or POST request.

If the request comes from a browser you need to handle CORS, which you must do by responding to the OPTIONS call separately. One way of doing it is by using the [Preflight Request client template](https://github.com/gtm-templates-simo-ahava/preflight-request) by Simo Ahava.

# Roadmap
- add checkbox to make the client handle CORS by itself
- support Basic Auth (a particular case of claiming by header)
