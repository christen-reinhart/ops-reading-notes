## Readings 10: VPC

Below you will find reading material and additional resources that support today’s topic and the upcoming lecture.

After you’ve completed the reading, answer the following:

## How can one host within a VPC any services that need to be public?
1. Public Subnets:
Create public subnets within your VPC and place your public-facing services in these subnets. These subnets have route tables that allow internet traffic to flow in and out, enabling services like web servers, APIs, and load balancers to be accessed publicly.
2. Security Groups:
Configure security groups to control inbound and outbound traffic for your public services. These groups allow specific ports and protocols through, ensuring only authorized access and protecting your services from unauthorized intrusions.
3. NAT Gateways:
If your services need to initiate outbound connections to the internet (e.g., sending emails or fetching updates), you can use NAT gateways in your VPC. These act as intermediaries, masking the internal IP addresses of your services and providing a single point of contact for outbound traffic.
4. Load Balancers:
For high availability and scalability, consider using load balancers in your public subnets. These distribute incoming traffic across multiple instances of your public services, ensuring smooth operation and handling traffic surges.


## What are examples of services that would live in the publicly-accessible part of the VPC? The privately-accessible part?
1.Web Servers: Hosted in public subnets to serve content to the internet.
2.Load Balancers: Distribute incoming network traffic across multiple servers to ensure no single server is overwhelmed.
3.Public-Facing APIs: APIs that need to be accessible from the internet.
Privately Accessible Part of VPC:
1.Database Servers: Placed in private subnets for security. Access is controlled, and they are not directly exposed to the internet.
2.Application Servers: Internal application components that don't need direct internet access.
3.Backend Services: Services used by internal systems or other backend components.


## What are the trade-offs of using a VPC vs traditional infrastructure?
1.Scalability: VPCs provide scalability and flexibility, allowing you to scale resources up or down based on demand.
2.Security: VPCs allow you to control network access with security groups and network access control lists (ACLs), enhancing the security of your infrastructure.
3.Isolation: VPCs provide isolation for your resources, enabling you to create private subnets for sensitive components.
4.Cost Management: VPCs can offer cost savings by allowing you to pay only for the resources you use.

	1.Complexity: VPCs introduce complexity, especially for beginners. Configuring subnets, route tables, and security groups requires careful planning.
2.Learning Curve: Understanding VPC concepts and best practices may require additional time and effort compared to traditional infrastructure.
3.Initial Setup Overhead: Setting up a VPC involves multiple steps, including defining subnets, configuring route tables, and setting up security groups.
4.Internet Gateway Costs: While the first 1 GB of data transfer out of an Amazon VPC is free each month, there are costs associated with data transfer over this limit.
5.Dependency on Cloud Provider: Using a VPC ties you to a specific cloud provider. Transitioning to a different provider or a hybrid model may involve additional complexities.
References

[What is a Virtual Private Cloud](https://www.cloudflare.com/learning/cloud/what-is-a-virtual-private-cloud/) 

[Chat GPT](https://chat.openai.com/share/e6b589eb-983a-4c3d-9d16-ef32c5892df0) 

## Things I wish I knew more about

How to implement services and develop in the cloud.
