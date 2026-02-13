# identity-management-project

/my-identity-project
/infrastructure
    template.json
    parameters.json
    /web-app
[firewall-project-template.zip](https://github.com/user-attachments/files/25292573/firewall-project-template.zip) README.md
    

The Identity Fortress

​This project demonstrates a production-grade secure environment for a web application using Azure Network Security best practices.

​🛡️ Security Features
​Zero Public Exposure: The Web App is isolated from the public internet using Azure Private Link.
​Single Entry Point: All inbound traffic is forced through an Azure Firewall (Basic).
​Deep Packet Inspection: The Firewall acts as a gateway, allowing only specific traffic (HTTPS) while blocking everything else.
​Network Segmentation: The architecture uses a dedicated Hub-and-Spoke style layout within a single VNet, separating Management, Firewall, and Application traffic into distinct subnets.

