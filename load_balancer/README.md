Load Balancer
This project implements redundancy and load balancing for web servers using HAProxy to distribute traffic between multiple Nginx servers.

0-custom_http_response_header: Configures Nginx with custom X-Served-By header showing server hostname
1-install_load_balancer: Installs and configures HAProxy with round-robin load balancing between web-01 and web-02
