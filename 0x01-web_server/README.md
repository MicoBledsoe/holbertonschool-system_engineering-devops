### Web Server Configuration

This section of the repository focuses on setting up and configuring a web server using Nginx. Learn the essentials of managing web servers, handling domain configurations, and customizing HTTP responses.

#### Table of Contents

- [Overview of Web Server](#overview-of-web-server)
- [Scripts Included](#scripts-included)
- [Usage Examples](#usage-examples)
- [Contributions](#contributions)

#### Overview of Web Server

In this project, we explore the basics of setting up a web server with Nginx, one of the most popular web servers in the world. Key tasks include transferring files, setting up a domain, and configuring redirection and custom error pages.

#### Scripts Included

- **0-transfer_file:** Transfers a file from our client to a server using SCP.
- **1-install_nginx_web_server:** Installs Nginx on a web server.
- **2-setup_a_domain_name:** Configures a hosted .tech domain to point to our server.
- **3-redirection:** Sets up a redirection from `/redirect_me` to another URL.
- **4-not_found_page_404:** Configures your Nginx server to have a custom 404 page that responds with "404 page not found".

#### Usage Examples

To transfer a file named `example.txt` to your server:
#```bash
./0-transfer_file example.txt

To install Nginx on your server:
./1-install_nginx_web_server

To configure a .tech domain:
./2-setup_a_domain_name yourdomain.tech

To set up HTTP redirection:
./3-redirection

To configure a custom 404 not found page:
./4-not_found_page_404

## Collaborators
Mico Bledsoe - LinkedIn(www.linkedin.com/in/micobledsoe)
