🏠 [`pokebot-gen3` Wiki Home](../Readme.md)

# 📡 HTTP Server Config

[`profiles/http.yml`](../../modules/config/templates/http.yml)

This configuration can be used to drive custom stream overlays and web UIs.

## HTTP server
The `http_server` config will enable a Flask HTTP server, which can be used to retrieve data and drive stream overlays.

`enable` - toggle HTTP server on/off

`ip` - IP address for HTTP server to listen on

`port` - TCP port for HTTP server to listen on
- Port must be unique for each bot instance

### HTTP Endpoints
The bot has a Flask HTTP server that can serve lots of data about the running emulator the current profile.

The following pages are available if the HTTP server is enabled:
- Test/example UI: [http://127.0.0.1:8888/](http://127.0.0.1:8888/)
- Swagger UI (API Documentation): [http://127.0.0.1:8888/docs/](http://127.0.0.1:8888/docs/)

![image](../images/http_api.png)