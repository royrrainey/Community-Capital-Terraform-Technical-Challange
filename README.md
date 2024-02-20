# Community Capital

### AWS Terraform Scripting Challenge

#### Objective:
Demonstrate your expertise in AWS by architecting a scalable and secure infrastructure
for a containerized application using Terraform. Your design should incorporate AWS
Fargate within a custom VPC that spans three Availability Zones, incorporating both
public and private networking strategies.

#### Requirements:

1. **VPC Configuration:**
- Design a VPC with a suitable CIDR block.
- Ensure the VPC covers three Availability Zones to enhance high availability.
- Include both public and private subnets in each Availability Zone.

2. **Networking:**
- Configure route tables for both public and private subnets to manage internet access
and internal communications effectively.
- Create an Internet Gateway for internet access from the public subnets.
- Utilize NAT Gateways or Instances to facilitate internet connectivity for the private
subnets.

3. **ECS Fargate:**
- Set up an ECS Cluster using Fargate as the launch type.
- Deploy a simple containerized application within an ECS Service in the private
subnet, ensuring it can access the internet as needed.

- Implement an Application Load Balancer in the public subnet to direct external traffic
to your application.

4. **Security Considerations:**
- Provide a written explanation of potential security implementations and
considerations at each infrastructure layer (VPC, subnet, ECS).
- This should include thoughts on Security Groups, NACLs, IAM roles, and secrets
management.

#### Instructions:

- Your task is to write Terraform code that defines the above infrastructure. Given the
expert level required for this challenge, we estimate this should take less than an hour
of work.
- **Please note:** There is no expectation for the code to be executable or error-
free upon submission. The primary goal is to review your approach and
architectural decisions.
- Your code should be well-commented to explain your design choices, especially
regarding high availability, scalability, and security.
- **Submission:** Once complete, upload your Terraform configuration files (.tf) and any
additional documentation to GitHub. You can either send me the link to your repository
or email me directly, and I will provide a GitHub repository where you can upload your
work.

#### Evaluation Criteria:
- **Architectural Design:** How well the solution uses AWS services to meet the
requirements.
- **Code Quality:** Organization, modularity, and use of Terraform best practices.
- **Security Approach:** Quality and depth of the security considerations and
explanations.
- **Documentation:** Clarity of comments and any provided documentation outlining
your design decisions.

## Solution
This project relies on components found in a private repository in a seperate account [Private Repo Account Link](https://github.com/geekincorp-devops). If you need access to this repository, please send a email request to info@geekinc.co for access 
