# aws-3-tier-architecture-capstone
End-to-End 3-Tier Web Architecture deployed on AWS featuring VPC, ALB, EC2, and RDS MySQL

As part of this hands-on project, I designed and deployed a secure, scalable, and isolated 3-tier web application from scratch. Here is a brief breakdown of the architecture and implementation:

🌐 Network Layer: Built a custom VPC featuring Public and Private Subnets across multiple Availability Zones, integrated with an Internet Gateway and custom Route Tables.

🔒 Security & IAM: Enforced strict security best practices using dedicated Security Groups (allowing standard web traffic and restricting database access exclusively to the web tier) and least-privilege IAM roles.

🗄️ Data Layer: Deployed an Amazon RDS database securely inside isolated private subnets, ensuring it is completely non-publicly accessible.

💻 Compute & Presentation Layer: Launched web servers running behind an Application Load Balancer (ALB), successfully establishing live database connectivity and verifying data read/write operations.

This project deeply strengthened my core understanding of AWS cloud infrastructure, network isolation, and security principles.
