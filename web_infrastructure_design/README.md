# Web Infrastructure Design

## Description
Whiteboard project: design web infrastructures for `www.foobar.com`, starting from a single server and growing it with redundancy, security, monitoring and scaling. Each answer file contains the link to the diagram screenshot plus the explanation of every component, the reasoning for each addition and the issues of the design.

## Tasks

| Task | Description | File |
| :--- | :--- | :--- |
| **0. Simple web stack** | One server with Nginx, an application server, the code base and MySQL. | `0-simple_web_stack` |
| **1. Distributed web infrastructure** | HAProxy load balancer plus two servers, with a MySQL Primary-Replica cluster. | `1-distributed_web_infrastructure` |
| **2. Secured and monitored web infrastructure** | Adds 3 firewalls, an SSL certificate for HTTPS and 3 monitoring clients. | `2-secured_and_monitored_web_infrastructure` |
| **3. Scale up** | HAProxy cluster and one dedicated server per component. | `3-scale_up` |

## Author
* **Luis Gonzalez** - Holberton School
