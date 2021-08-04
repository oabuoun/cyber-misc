# Cybersecurity - Miscellaneous

##	Diffie-Hellman Algorithm

-	 [Diffie-Hellman Key Exchange – A Non-Mathematician’s Explanation](docs/dh/WP_Palmgren_DH.pdf)

-	[Diffie-Hellman - Practical Networking](https://www.practicalnetworking.net/series/cryptography/diffie-hellman/)

-	[An Introduction to Mathematical Cryptography (Undergraduate Texts in Mathematics)](docs/dh/MathCrypto-SampleSections.pdf)

	The full text can be bought on Amazon [An Introduction to Mathematical Cryptography (Undergraduate Texts in Mathematics) 2nd ed. 2014 Edition](https://www.amazon.com/Introduction-Mathematical-Cryptography-Undergraduate-Mathematics/dp/1493917102/ref=dp_ob_title_bk)


##	Threat Modelling - Examples

-	[Threat Modeling: 12 Available Methods ](https://insights.sei.cmu.edu/blog/threat-modeling-12-available-methods/)

-	[Threat Modeling w/ PASTA - Risk Centric Threat Modeling Case Studies](docs/threat_modelling/Threat-Modeling-with-PASTA.pdf)

-	[Real World Threat Modeling Using the PASTA Methodology](docs/threat_modelling/AppSecEU2012_PASTA.pdf)

##	TLS/Certificates

-	[TLS Basics](https://www.internetsociety.org/deploy360/tls/basics/)

-	[What is a TLS/SSL certificate, and how does it work?](https://protonmail.com/blog/tls-ssl-certificate/)

##	Container Security

-	[NIST Special Publication 800-190- Application Container Security Guide](docs/container/NIST.SP.800-190.pdf)

-	[Containers: Security Challenges and How to Address Them](docs/security/DevOps.com-Container_Security_Challenges.pdf)

##	Nginx + TLS Certificate (Reverse Proxy)

-	[How To Configure Nginx as a Web Server and Reverse Proxy for Apache on One Ubuntu 18.04 Server](https://www.digitalocean.com/community/tutorials/how-to-configure-nginx-as-a-web-server-and-reverse-proxy-for-apache-on-one-ubuntu-18-04-server)

-	[Maximizing Python Performance with NGINX, Part 1: Web Serving and Caching](https://www.nginx.com/blog/maximizing-python-performance-with-nginx-parti-web-serving-and-caching/)


##	AWS

###	AWS WAF

AWS WAF (https://aws.amazon.com/waf/) is a firewall that protects your applications by allowing or blocking specific access, and also by stopping common attack patterns. You can define various customizable security rules through the service. For example, you can block a request originating from a specific country or one in which the header matches a desired set of external request patterns. WAF is commonly used with Application Load Balancing, Amazon CloudFront and API Gateway, among others.

###	AWS Shield

AWS Shield (https://aws.amazon.com/shield) is a managed service designed to protect you from distributed denial of service (DDoS) attacks. AWS Shield offers two service tiers -- its free Standard infrastructure network and transport layer protection and its paid Advanced service, which includes more detailed protection, integration with AWS WAF and access to a 24/7 AWS DDoS response team.

###	AWS Firewall Manager

AWS Firewall Manager (https://aws.amazon.com/firewall-manager/) is a tool with which you can centralize security rules. It works with both AWS WAF and Shield and is designed to support multiple AWS accounts through its integration with AWS Organizations. With Firewall Manager, you can deploy new rules across multiple AWS environments instead of having to manually configure everything.
###	IAM Best Practices

-	**Users** – Create individual users (https://aws.amazon.com/iam/features/manage-users/)

-	**Groups** – Manage permissions with groups (https://aws.amazon.com/iam/features/manage-users/).

-	**Permissions** – Grant least privilege (https://aws.amazon.com/iam/features/manage-permissions/).

-	**Auditing** – Turn on AWS CloudTrail (https://aws.amazon.com/cloudtrail/).

-	**Password** – Configure a strong password policy (https://aws.amazon.com/iam/features/managing-user-credentials/).

-	**MFA** – Enable MFA for privileged users (https://aws.amazon.com/iam/features/mfa/).

-	**Roles** – Use IAM roles for Amazon EC2 instances (https://aws.amazon.com/iam/features/manage-roles/).

-	**Sharing** – Use IAM roles to share access (https://aws.amazon.com/identity/federation/).

-	**Rotate** – Rotate security credentials regularly (http://docs.aws.amazon.com/AWSEC2/latest/UserGuide/iam-roles-for-amazon-ec2.html).

-	**Conditions** – Restrict privileged access further with conditions (http://docs.aws.amazon.com/IAM/latest/UserGuide/PermissionsAndPolicies.html).

-	**Root** – Reduce or remove use of root (https://aws.amazon.com/iam/features/manage-users/).

##	Terraform

###	Best Practices

-	https://github.com/ozbillwang/terraform-best-practices

-	https://dzone.com/articles/secure-terraform-delivery-pipeline-best-practices

-	https://www.thedevcoach.co.uk/terraform-best-practices/

-	https://blog.gft.com/pl/2020/03/04/secure-terraform-delivery-pipeline-best-practices-part-1-2/

-	https://blog.gft.com/pl/2020/03/12/secure-terraform-delivery-pipeline-best-practices-part-2-2/

###	Terraform Vault
https://learn.hashicorp.com/tutorials/vault/getting-started-install

https://learn.hashicorp.com/tutorials/terraform/secrets-vault

https://jryancanty.medium.com/hashicorp-vault-and-terraform-on-google-cloud-security-best-practices-3d94de86a3e9

https://registry.terraform.io/providers/hashicorp/vault/latest/docs
