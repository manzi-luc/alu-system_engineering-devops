# Load Balancer

## What's inside
- `0-custom_http_response_header`: configures nginx to add an X-Served-By header with the server hostname
- `1-install_load_balancer`: installs and configures HAProxy to balance traffic between web-01 and web-02
