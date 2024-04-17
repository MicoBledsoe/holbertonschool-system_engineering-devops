### Load Balancer Configuration

This project section details the setup and configuration of a load balancer using HAProxy. The load balancer is essential for distributing incoming network traffic across multiple servers to ensure no single server bears too much demand.

#### Table of Contents

- [Overview of Load Balancing](#overview-of-load-balancing)
- [Scripts Included](#scripts-included)
- [Usage Examples](#usage-examples)
- [Contributions](#contributions)

#### Overview of Load Balancing

The objective of load balancing is to spread workloads across multiple computing resources. This increases reliability through redundancy and improves performance. This section covers the basics of setting up a load balancer to manage traffic efficiently across a server cluster.

#### Scripts Included

- **0-custom_http_response_header:** Configures the load balancer to add a custom HTTP response header.
- **1-install_load_balancer:** Automates the installation of HAProxy on a load balancer server.

#### Usage Examples

To install HAProxy and configure it as a load balancer:
#```bash
./1-install_load_balancer

To add a custom HTTP header for responses handled by the load balancer:
./0-custom_http_response_header

#Collaborators
Mico Bledsoe - LinkedIn(www.linkedin.com/in/micobledsoe)
