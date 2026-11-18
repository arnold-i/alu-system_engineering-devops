# Load balancer

- `0-custom_http_response_header`: installs Nginx and adds an `X-Served-By` header set to the server's hostname.
- `1-install_load_balancer`: installs HAProxy on lb-01 and spreads traffic across web-01 and web-02 with roundrobin.
