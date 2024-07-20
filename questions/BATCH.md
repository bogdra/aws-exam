1. Which of these AWS services helps you to trace requests across different components and AWS services?
    - A. AWS X-Ray
    - B. Amazon CloudWatch
    - C. AWS Config
    - D. AWS CloudTrail

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A
      <p>Explanation: X-Ray - Trace request across microservices/AWS services - Analyze, Troubleshoot errors, Solve performance issues
        </p>
   </details>

2. Which of these database services is used to create an AWS managed Oracle database?
    - A. Amazon DynamoDB
    - B. Amazon RDS
    - C. Amazon ElastiCache
    - D. Amazon Redshift

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B
    <p>
        Explanation: 
   </p>
    </details>

3. Which of these can be used to review, accept, and manage your agreements with AWS?
    - A. AWS Artifact
    - B. Amazon GuardDuty
    - C. AWS Security Hub
    - D. Amazon Macie

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B
       <p>
        Explanation: 
   </p>
    </details>

4. Which of these is NOT a responsibility of AWS under the shared responsibility model?
    - A. Ensuring that services like Amazon S3 and Amazon DynamoDB are highly available
    - B. Providing information on AWS IT control environment (white papers, certifications etc)
    - C. Controls based on the applications deployed to AWS
    - D. Ensuring adherence of AWS IT Infrastructure with IT security standards

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C
       <p>
        Explanation: 
   </p>
    </details>

5. Your enterprise does not have in house AWS expertise. Which of these services can help with your cloud migration? Please select two correct answers
    - A. AWS Abuse team
    - B. AWS Marketplace
    - C. AWS Partner Network
    - D. AWS Professional Services
    - E. AWS Systems Manager

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C, D
       <p>
        Explanation: 
   </p>
    </details>

6. Which of these devices are used to setup AWS Managed VPN connectivity between On-premises and AWS (Select 2)?
    - A. VPN gateway
    - B. NAT Gateway
    - C. Internet Gateway
    - D. NAT instance
    - E. Customer gateway

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A, E
       <p>
        Explanation:
   - VPN gateway to connect one VPC to customer network
   - Customer gateway installed in customer network
   </p>
    </details>

7. Which of these AWS services is recommended to track changes made to your AWS resources?
    - A. AWS X-Ray
    - B. Amazon CloudWatch
    - C. Amazon GuardDuty
    - D. AWS CloudTrail

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D
       <p>
        Explanation: AWS CloudTrail - Track events, API calls, changes made to your AWS resources.  Who (made the request), What (action, parameters, end result) and When?
   </p>
    </details>

8. You need to quickly run a mission critical batch program that cannot be interrupted. Which of these options would you choose?
    - A. Reserved Instances
    - B. On Demand Instances
    - C. Spot Instances
    - D. Savings Plans

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B
       <p>
        Explanation: On Demand Instances - Request when you want it. Flexible and Most Expensive.   Immediate workloads (web applications/batch programs). Applications that cannot be interrupted.
   </p>
    </details>

9. Which of these is an AWS managed service to allow instances in a private subnet to download software patches while denying inbound traffic from internet?
    - A. Internet Gateway
    - B. NAT instance
    - C. AWS Direct Connect
    - D. NAT Gateway

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D
       <p>
        Explanation:  NAT Devices allow instances in a private subnet to download software patches while denying inbound traffic from internet.  NAT Gateway: Managed Service (PREFERRED - No maintenance, more availability & high bandwidth)
   </p>
    </details>

10. Which of these AWS support plans provides you with 24x7 phone, email, and chat access to Cloud Support Engineers and technical support for unlimited contacts? (Select 2)
    - A. Developer
    - B. Enterprise
    - C. Business
    - D. Basic
    - E. Operations

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B, C
        <p>
        Explanation: AWS Support Plans
        - Four Plans: Basic (FREE), Developer ($), Business ($$), Enterprise ($$$$$$)
        - Technical Support
        - Basic Plan - 24x7 access to customer service and forums
        - Developer Plan - Business hours email access to Cloud Support Associates  Unlimited cases / 1 primary contact
        - Business Plan - 24x7 phone, email, and chat access to Cloud Support Engineers Unlimited cases / unlimited contacts (IAM supported)
        - Enterprise Plan - Same as Business Plan
        </p>
         </details>

11. Security and Compliance in AWS is a:
    - A. Responsibility of AWS
    - B. None of the above
    - C. Shared Responsibility of AWS and Customer
    - D. Responsibility of Customer

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C
        <p>
        Explanation: 
            Shared Responsibility Model
            - Security & Compliance - Shared responsibility:
            - AWS manages security of the cloud:
            - Operates, manages & controls Host OS and virtualization layer down to the physical security.
            - YOU are responsible for security in the cloud:
            - Guest OS (patches), Application S/W, Security Groups, Integrating AWS Services with IT environments
       </p>
        </details>

12. Question 46
    Incorrect
    Which of these allow you to create tunnels from VPC to on premises with encrypted communication over internet?
    - A. Internet Gateway
    - B. AWS Managed VPN
    - C. AWS Direct Connect
    - D. NAT Gateway

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B
        <p>
        Explanation: 
            Overall explanation
                - AWS Managed VPN: Tunnels from VPC to on premises
                - Traffic over internet - encrypted using IPsec protocol
       </p>
        </details>

13. Overall explanation
- AWS Managed VPN: Tunnels from VPC to on premises

- Traffic over internet - encrypted using IPsec protocol
    - A. Pay monthly installments for the infrastructure bought
    - B. Trade capital expenditure (capex) for operational expenditure (opex)
    - C. Buy infrastructure ahead of time
    - D. Trade operational expenditure (opex) for capital expenditure (capex)
    - E. Pay-as-you-go

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B E
        <p>
        Explanation: 
            Important Cloud Characteristics:
              - Elasticity
              - On-demand resource provisioning.
              - Trade "capital expense (capex)" for "variable expense (opex)" (Pay-as-you-go)
              - "Go global" in minutes
     </p>
      </details>

14. Which of these is NOT a category of checks provided by Trusted Advisor?
    - A. Reliability
    - B. Cost optimization
    - C. Service limits
    - D. Performance

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A
        <p>
        Explanation: 
           Overall explanation
            - AWS Trusted Advisor: Provides Cost optimization, performance, security & fault tolerance recommendations
            - Cost Optimization: Unused resources, Other opportunities (ex: reserved instances)
            - Security : Settings to make your AWS solution more secure (ex: security group)
            - Fault Tolerance: Redundancy improvements, over-utilized resources
            - Performance: Improve speed and responsiveness of your AWS solutions
            - Service Limits: Is your usage is more than 80% of service limits?
       </p>
        </details>

15. You want to reserve compute capacity in AWS to reduce costs. You need the flexibility to switch from EC2 instances to AWS Lambda or AWS Fargate. Which of these options would you choose?
    - A. Reserved Instances
    - B. Savings Plans
    - C. On Demand Instances
    - D. Spot Instances

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer:  B
        <p>
        Explanation: 
            Savings Plans - Commit spending $X per hour on (EC2 or AWS Fargate or Lambda).  Upto 66% off. Lot of flexibility. 1 or 3 years reservation.  No Upfront or Partial Upfront or All Upfront Payments
       </p>
        </details>

16. When do you go for EC2 spot instances? (Select 2)
    - A. Your workloads cannot be stopped
    - B. Your workloads are immediate
    - C. Your workloads are NOT fault tolerant
    - D. Your workloads can be stopped at a minute's notice and can continue from where they stopped
    - E. Your workloads are non immediate

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D E
        <p>
        Explanation: 
            - Spot Instances - Cheapest (upto 90% off). Quote the maximum price. Terminated with 2 minute notice. Cost sensitive, Fault tolerant, Non immediate workloads.
   </p>
    </details>

17. Which of these AWS services helps you to estimate the cost of your architecture solution in AWS? (Select 2)
    - A. TCO - Total Cost of Ownership Calculator
    - B. AWS Simple Monthly Calculator
    - C. AWS Cost Explorer
    - D. AWS Pricing Calculator
    - E. AWS Budgets

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D
        <p>
        Explanation: 
            - AWS Pricing Calculator (NEW) - Estimate cost of your architecture solution
            - AWS Simple Monthly Calculator (OLD) - Estimate charges for AWS services
       </p>
        </details>

18. Which of these allow you to monitor network traffic and troubleshoot network connectivity issues (NACL and/or Security Groups misconfiguration)?
    - A. NAT Gateway
    - B. VPC Peering
    - C. VPC Endpoint
    - D. VPC Flow Logs

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D
        <p>
        Explanation:  Overall explanation
            - VPC Flow Logs: Enable logs to debug problems
            - VPC Peering - Connect VPCs from same or different AWS accounts (across regions)
            - Allows private communication between the connected VPCs
            - Peering uses a request/accept protocol (Owner of requesting VPC sends a request)
            - Peering is not transitive.
       </p>
        </details>

19. Which of these provides you with access to AWS auditor issued reports, certifications, accreditations and other third-party attestations?
    - A. Amazon GuardDuty
    - B. AWS Security Hub
    - C. AWS Artifact
    - D. Amazon Macie

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C
        <p>
        Explanation: 
    <ul>
            <li> - AWS Artifact - Self-service portal for on-demand access to AWS compliance reports, certifications, accreditations, and other third-party attestations. Review, accept, and manage your agreements with AWS.</li>
            <li> - Amazon Macie - Fully managed data security and privacy service  Uses machine learning to identify sensitive data in Amazon S3 (Recommendation) When migrating data to AWS use S3 for staging and Run Macie</li>
            <li> - Amazon GuardDuty - Continuously monitor AWS environment for suspicious activity (Intelligent Threat Detection). Analyzes AWS CloudTrail events, VPC Flow Logs etc. </li>
            <li> - AWS Security Hub - Consolidated view of your security status in AWS. Automate security checks, manage security findings, and identify the highest priority security issues across your AWS environment.</li>
    </ul>
 </p>
    </details>

20. Which of these is used to continuously monitor AWS environment for suspicious activity by analyzing AWS CloudTrail events, VPC Flow Logs etc?
   - A. AWS Shield
   - B. Amazon GuardDuty
   - C. Amazon Macie
   - D. AWS WAF (Web Application Firewall)

   <details markdown=1><summary markdown='span'>Answer</summary>
     Correct answer: B
       <p>
       Explanation: - Amazon GuardDuty - Continuously monitor AWS environment for suspicious activity (Intelligent Threat Detection). Analyzes AWS CloudTrail events, VPC Flow Logs etc.
   </p>
    </details>

21. Which of these are pillars in the AWS Well Architected Framework (Select 2)?
   - A. Resilience
   - B. Operational Excellence
   - C. Cost Optimization
   - D. Efficiency
   - E. Provisioning servers

   <details markdown=1><summary markdown='span'>Answer</summary>
     Correct answer: B C
       <p>
       Explanation: Well Architected Framework - Five Pillars: Operational Excellence; Security; Reliability; Performance Efficiency; Cost Optimization
     </p>
      </details>

22. Which of these are NOT shared responsibilities between AWS and customer under the Shared Responsibility Model? (Select 2)
    - A. Adherence of IT Infrastructure with IT security standards
    - B. Controls based on the applications deployed to AWS
    - C. Patch Management
    - D. Awareness & Training
    - E. Configuration Management

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A B
        <p>
        Explanation: 
            Compliance responsibilities will be shared : AWS ensures adherence of IT Infrastructure with IT security standards; AWS provides information on its IT control environment (white papers,  certifications, etc) ;Customers perform their evaluation (use AWS control and compliance documentation)
       </p>
        </details>


23. Which of these AWS services helps you to define Service control policies(SCP) to define cross account restrictions (Example: Require MFA to stop an Amazon EC2 instance)?
    - A. AWS CloudTrail
    - B. AWS Organizations
    - C. AWS Trusted Advisor
    - D. AWS Config

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B
        <p>
        Explanation:
        - AWS Organizations: Simple management for multiple AWS accounts
        - Consolidated bill for AWS accounts
        - Centralized management for AWS Config Rules
        - Send AWS CloudTrail data to one S3 bucket (across accounts)
        - AWS Firewall Manager to manage firewall rules (WAF, Shield and Security Groups)
   </p>
    </details>

24. Which of these is used to make programmatic calls against AWS Services?
    - A. IAM User Access keys (access key ID and secret access key)
    - B. IAM Group user id and password
    - C. IAM User user id and password
    - D. AWS CLI (Command Line Interface) ;Execute Commands  ; Create Scripts ; Use IAM Users Credentials - access key ID and secret access key
    <details markdown=1><summary markdown='span'>Answer</summary>
        Correct answer: A
    </details>


25. Which of these databases is recommended for data-warehousing, reporting and analytics usecases?
    - A. Amazon DynamoDB
    - B. Amazon ElastiCache
    - C. Amazon RDS
    - D. Amazon Redshift

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D
        <p>
        Explanation: 
            - Relational OLAP databases - Amazon Redshift - Datewarehouse, reporting, analytics & intelligence apps. Analyse Petabytes of data.
   </p>
    </details>

26. Which of these AWS services helps you to run pre-configured development stacks like LAMP, MEAN in AWS at a low predictable monthly price?
    - A. AWS Elastic Beanstalk
    - B. Amazon Lightsail
    - C. AWS Lambda
    - D. AWS Elastic Container Service (ECS)

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B
        <p>
        Explanation:  - Amazon Lightsail - Pre-configured development stacks in AWS - LAMP, MEAN. Run websites on WordPress.Low, predictable monthly price.
   </p>
    </details>

27. Which of these allows instances in a private subnet to download software patches while denying inbound traffic from internet?
    - A. Internet Gateway
    - B. AWS Direct Connect
    - C. NAT Gateway
    - D. Security Group

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C
        <p>
        Explanation: - NAT Devices allow instances in a private subnet to download software patches while denying inbound traffic from the internet
   </p>
    </details>

28. Which of these are used to manage permissions for a set of users in AWS?
    - A. IAM Policy
    - B. IAM User
    - C. IAM Group
    - D. IAM Role

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C
        <p>
        Explanation:   IAM groups: Collection of IAM users
   </p>
    </details>

29. Which of these AWS services can be used to protect Amazon Route 53, CloudFront, EC2 instances and Elastic Load Balancers (ELB) from distributed denial of service (DDoS) attacks?
    - A. AWS Shield
    - B. AWS KMS
    - C. AWS WAF (Web Application Firewall)
    - D. AWS Cloud HSM (Hardware Security Module)

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A
        <p>
        Explanation: 
            - AWS Shield - Shields from Distributed Denial of Service (DDoS) attacks
            - Disrupt normal traffic of a server by overwhelming it with a flood of Internet traffic
            - Protect Amazon Route 53, CloudFront, EC2 instances and Elastic Load Balancers (ELB)
       </p>
        </details>


30. Which of these AWS services provides predefined, customizable rules that are used to evaluate whether your AWS resources comply with common best practices?
    - A. Amazon CloudWatch
    - B. Amazon GuardDuty
    - C. AWS Config
    - D. AWS CloudTrail

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C
        <p>
        Explanation: 
            AWS Config - Auditing: Complete inventory of your AWS resources. Resource history and change tracking - Find how a resource was configured at any point in time Governance - Customize Config Rules for specific resources or for entire AWS account and Continuously evaluate compliance against the desired configuration
   </p>
    </details>

31. Which of these is an ephemeral storage that can be attached with an EC2 instance?
    - A. Amazon EC2 Instance Store
    - B. Amazon Elastic File System (EFS)
    - C. Amazon Elastic Block Store (EBS)
    - D. AWS Storage Gateway

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A
        <p>
        Explanation: 
             - Block - Storage connected to one EC2 instance. Your Hard Disks.
             - Elastic Block Storage (EBS - Permanent)
             - EC2 Instance Store (Ephemeral)
   </p>
    </details>

32. Which of these AWS services helps you to run commands and apply patches on a group of Amazon EC2 instances?
    - A. AWS Marketplace
    - B. AWS Professional Services
    - C. AWS Systems Manager
    - D. AWS Budgets

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C
        <p>
        Explanation: 
            - AWS Systems Manager - Run commands(operational tasks) on Amazon EC2 instances.  Manage your OS and Database patches.
   </p>
    </details>

33. Which of these AWS services can be used to protect your web applications from Common Vulnerabilities and Exposures (CVE) - information-security vulnerabilities and exposures?
    - A. AWS WAF (Web Application Firewall)
    - B. AWS Shield
    - C. AWS Cloud HSM (Hardware Security Module)
    - D. AWS KMS

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A
        <p>
        Explanation: AWS WAF protects your web applications from OWASP Top 10 exploits, CVE and a lot more!
   </p>
    </details>

34. Which of these is NOT a pillar in the AWS Well Architected Framework?
    - A. Resilience
    - B. Security
    - C. Reliability
    - D. Operational Excellence

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A
        <p>
        Explanation: 
   </p>
    </details>

35. Which of these databases supports relational databases with tables and SQL queries(Select 2)?
    - A. Amazon ElastiCache
    - B. Amazon Neptune
    - C. Amazon Redshift
    - D. Amazon RDS
    - E. Amazon DynamoDB

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C D
        <p>
        Explanation:
        - Relational OLAP databases - Amazon Redshift - Date warehouse, reporting, analytics & intelligence apps. Analyze Petabytes of data.
   </p>
    </details>

36. Which of these are attached to an IAM entity to provide it with permissions to access AWS resources?
    - A. IAM User
    - B. IAM Group
    - C. IAM Role
    - D. IAM Policy

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D
        <p>
        Explanation:  - Can be attached with IAM users, IAM groups and IAM Roles
   </p>
    </details>


37. Which of these are the types of Elastic Load Balancers available in AWS (select 3)?
    - A. Container Load Balancer
    - B. Classic Load Balancer
    - C. Network Load Balancer
    - D. Application Load Balancer
    - E. Modern Load Balancer

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B C D
        <p>
        Explanation: 
            1 Classic Load Balancer: Old generation. Not Recommended by AWS.
            2 Application Load Balancer: Most popular and frequently used ELB in AWS. Supports HTTP/HTTPS (Layer 7) and Advanced Routing(Headers, Query Params, Path and Host Based)
            3 Network Load Balancer: For very high performance usecases
        </p>
    </details>


38. Which of these AWS services can be used to protect your web applications from malicious requests from specific IP Addresses?
    - A. AWS WAF (Web Application Firewall)
    - B. AWS KMS
    - C. AWS Shield
    - D. AWS Cloud HSM (Hardware Security Module)

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A
        <p>
        Explanation:  
        - AWS WAF protects your web applications from OWASP Top 10 exploits, CVE and a lot more!
        - Web traffic filtering : block attacks - Filter traffic based on IP addresses, geo locations, HTTP headers and body (block attacks from specific user-agents, bad bots, or content scrapers)
        - AWS Shield - Shields from Distributed Denial of Service (DDoS) attacks
   </p>
    </details>

39. Which of these services automates the discovery of sensitive data at scale and lowers the cost of protecting your data in AWS?
    - A. AWS Shield
    - B. Amazon Macie
    - C. Amazon GuardDuty
    - D. AWS WAF (Web Application Firewall)

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B
        <p>
        Explanation: 
            - Amazon Macie - Fully managed data security and privacy service  Uses machine learning to identify sensitive data in Amazon S3 (Recommendation) When migrating data to AWS use S3 for staging and Run Macie
            - Amazon GuardDuty - Continuously monitor AWS environment for suspicious activity (Intelligent Threat Detection). Analyzes AWS CloudTrail events, VPC Flow Logs etc.
   </p>
    </details>

40. Which of these are shared responsibilities between AWS and customer under the Shared Responsibility Model? (Select 2)
    - A. Patch Management
    - B. Adherence of IT Infrastructure with IT security standards
    - C. Providing information on the AWS IT control environment
    - D. Controls based on the applications deployed to AWS
    - E. Configuration Management

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A E
        <p>
        Explanation: 
   </p>
    </details>

41. Which of these can be used to create network storage that can be attached with only one EC2 instance?
    - A. AWS Storage Gateway
    - B. Amazon Elastic Block Store (EBS)
    - C. Amazon S3
    - D. Amazon Elastic File System (EFS)

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B
        <p>
        Explanation: 
         Elastic Block Storage (EBS - Permanent)
            - Instance Store (Ephemeral)
       </p>
        </details>

42. Which of these provides hybrid storage (AWS + On Premises) for applications running on-premises?
    - A. Amazon Elastic File System (EFS)
    - B. Amazon Elastic Block Store (EBS)
    - C. Amazon S3
    - D. AWS Storage Gateway

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D
        <p>
        Explanation: - Hybrid - AWS Storage Gateway - Cloud + On Premise
   </p>
    </details>

43. Which of these helps you to investigate and quickly identify the root cause of potential security issues?
    - A. AWS Artifact
    - B. Amazon Detective
    - C. Amazon GuardDuty
    - D. Amazon Macie

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B
        <p>
        Explanation: 
          - Amazon Detective - Investigate and quickly identify the root cause of potential security issues. Automatically collect log data from your AWS resources and uses machine learning to help you visualize and conduct security investigations.
          - Amazon Macie - Fully managed data security and privacy service  Uses machine learning to identify sensitive data in Amazon S3 (Recommendation) When migrating data to AWS use S3 for staging and Run Macie
          - Amazon GuardDuty - Continuously monitor AWS environment for suspicious activity (Intelligent Threat Detection). Analyzes AWS CloudTrail events, VPC Flow Logs etc.
   </p>
    </details>

44. Which of these represents the need for an IAM Role?
    - A. Has User id and password attached to access AWS Resources
    - B. Has Temporary permissions to make AWS service requests
    - C. Helps you to manage permissions for multiple IAM users
    - D. Has Access keys (access key ID and secret access key) to access AWS Resources

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B
        <p>
        Explanation: 
            IAM Roles: Temporary identities
                - Does NOT have credentials attached
                - (Advantage) Expire after a set period of time
                - Used to give access to federated users or EC2 instances
       </p>
        </details>

45. Which of these AWS services provides a serverless approach to building applications in AWS?
    - A. Amazon Lightsail
    - B. AWS Lambda
    - C. AWS Elastic Container Service (ECS)
    - D. AWS Elastic Beanstalk

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B
        <p>
        Explanation: - AWS Lambda - Serverless - Do NOT worry about servers
   </p>
    </details>

46. Which of these S3 storage classes is recommended for archive data that can be accessed in 24 hours when needed?
    - A. Standard
    - B. One Zone-IA
    - C. Glacier
    - D. Glacier Deep Archive

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D
        <p>
        Explanation: 
            - Standard - Frequently accessed data. First Byte: ms
            - Standard-IA - Long-lived, infrequently accessed data (backups for disaster recovery). First Byte: ms
            - One Zone-IA - Long-lived, infrequently accessed, non-critical data (Easily re-creatable data - thumbnails for images). First Byte: ms
            - Intelligent-Tiering - Long-lived data with changing or unknown access patterns
            - Glacier - Archive data with retrieval times ranging from minutes to hours
            - Glacier Deep Archive - Archive data that rarely, if ever, need to be accessed with retrieval times in a few hours
            - Reduced Redundancy (Not recommended) - Frequently accessed, non-critical data
       </p>
        </details>


47. Which of these AWS services gives you real-time guidance to help you provision your resources following AWS best practices?
    - A. AWS Trusted Advisor
    - B. AWS CloudTrail
    - C. AWS CloudWatch
    - D. AWS X-Ray

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A
        <p>
        Explanation: 
            AWS Trusted Advisor: Provides Cost optimization, performance, security & fault tolerance recommendations
                - Cost Optimization: Unused resources, Other opportunities (ex: reserved instances)
                - Security: Settings to make your AWS solution more secure (ex: security group)
                - Fault Tolerance: Redundancy improvements, over-utilized resources
                - Performance: Improve speed and responsiveness of your AWS solutions
                - Service Limits: Is your usage is more than 80% of service limits?
       </p>
        </details>


48. Which of these IAM entities can have policies attached with them?
    - A. All of the Above
    - B. IAM User
    - C. IAM Role
    - D. IAM Group

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A
        <p>
        Explanation:  - Can be attached with IAM users, IAM groups and IAM Roles
   </p>
    </details>

49. Which of these AWS services can be used to store user sessions from web applications?
    - A. Amazon ElastiCache
    - B. Amazon RDS
    - C. Amazon S3
    - D. Amazon Redshift

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A
        <p>
        Explanation:  - In memory databases/caches - Amazon ElastiCache - Applications needing microsecond responses - Cache Query Results from databases. Can act as a session store as well.
   </p>
    </details>

50. Which of these AWS services are auto-scaling by default(Select 2)?
    - A. Amazon RDS
    - B. Amazon Elastic Block Store (EBS)
    - C. Amazon EC2
    - D. Amazon Elastic File System (EFS)
    - E. Amazon S3

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D E
        <p>
        Explanation: Amazon S3 and EFS are auto-scaling.
   </p>
    </details>

51. Which of these sits between public subnet (VPC) resources and the internet (provides access to the internet to and from public subnet resources)?
    - A. NAT Gateway
    - B. NAT instance
    - C. Security Group
    - D. Internet Gateway

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D
        <p>
        Explanation: 
            An Internet Gateway enables internet communication for public subnets
                - Public Subnet: Subnet having a route to an internet gateway
                - Private Subnet: Subnet DOES NOT have a route to an internet gateway
   </p>
    </details>

52. Which of these AWS services would you use to check for security groups having unrestricted access (0.0.0.0/0)?
    - A. AWS Config
    - B. AWS Trusted Advisor
    - C. AWS CloudTrail
    - D. AWS Organizations

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B
        <p>
        Explanation: 
            AWS Trusted Advisor: Provides Cost optimization, performance, security & fault tolerance recommendations
                - Cost Optimization: Unused resources, Other opportunities (ex: reserved instances)
                - Security : Settings to make your AWS solution more secure (ex: security group)
       </p>
        </details>


53. Which of these AWS services provides inventory of your AWS resources including resource history?
    - A. Amazon CloudWatch
    - B. AWS CloudTrail
    - C. Amazon GuardDuty
    - D. AWS Config

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D
        <p>
        Explanation: 
            - AWS Config - Auditing: Complete inventory of your AWS resources. Resource history and change tracking - Find how a resource was configured at any point in time Governance - Customize Config Rules for specific resources or for entire AWS account and Continuously evaluate compliance against the desired configuration
   </p>
    </details>

54. Which of these AWS services helps you to track the CPU Utilization of an EC2 instance?
    - A. Amazon GuardDuty
    - B. Amazon CloudWatch
    - C. AWS CloudTrail
    - D. AWS Config

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B
        <p>
        Explanation: Amazon CloudWatch Metrics - Metrics for AWS services Example EC2: CPUUtilization, NetworkIn, NetworkOut
   </p>
    </details>

55. Which of these allow you to execute commands and create scripts to interact with AWS services from the command line?
    - A. AWS Management Console
    - B. AWS CLI
    - C. AWS SDKs
    - D. AWS Management Console Mobile App

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B
        <p>
        Explanation: 
            AWS CLI (Command Line Interface)
                - Execute Commands
                - Create Scripts
                - Use IAM Users Credentials - access key ID and secret access key
       </p>
        </details>


56. Which of these architectural principles helps you to avoid cascading failures while architecting your cloud applications?
    - A. Maintain Redundancy
    - B. Prefer loosely coupled architectures
    - C. Scale horizontally
    - D. Automate recovery from failure

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B
        <p>
        Explanation: - Prefer loosely coupled architectures: SQS, SNS
   </p>
    </details>

57. Which of these are inherited controls (controls that a customer fully inherits from AWS) under the shared responsibility model?
    - A. Awareness & Training
    - B. Configuration Management
    - C. Physical and environmental controls
    - D. Patch Management

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C
        <p>
        Explanation: 
   </p>
    </details>

58. Which of these AWS services would you reach out to for getting technical expertise and advice from AWS Teams for Application Migration, Application Modernization etc?
    - A. AWS Partner Network
    - B. AWS Systems Manager
    - C. AWS Marketplace
    - D. AWS Professional Services

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D
        <p>
        Explanation:  - AWS Professional Services - Get help from AWS for your cloud migration. Get technical expertise and advice from AWS Teams for Application Migration, Application Modernization, etc
   </p>
    </details>

59. Which of these AWS support plans is the cheapest option providing business hour email access to support teams?
    - A. Enterprise
    - B. Basic
    - C. Developer
    - D. Business

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C
        <p>
        Explanation: 
            - Basic Plan - 24x7 access to customer service and forums
            - Developer Plan - Business hours email access to Cloud Support Associates  Unlimited cases / 1 primary contact
            - Business Plan - 24x7 phone, email, and chat access to Cloud Support Engineers Unlimited cases / unlimited contacts (IAM supported)
            - Enterprise Plan - Same as Business Plan
       </p>
        </details>


60. Compared to the traditional approach (data centers), how is cloud different?
    - A. Increased capital expenditure (capex) and reduced operational expenditure (opex)
    - B. Reduced capital expenditure (capex) and increased operational expenditure (opex)
    - C. Reduced capital expenditure (capex) and reduced operational expenditure (opex)
    - D. Increased capital expenditure (capex) and increased operational expenditure (opex)

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B
        <p>
        Explanation: 
            Advantages of Cloud:
                - Trade "capital expense (capex)" for "variable expense (opex)" (Pay-as-you-go)
                  - Benefit from massive economies of scale
                  - Stop guessing capacity
                  - Increase speed and agility
                  - Stop spending money running and maintaining data centers
                  - "Go global" in minutes
         </p>
          </details>


61. Which of these can be used to setup a MySQL database in AWS? (Select 2)
    - A. Amazon RDS
    - B. Amazon EC2
    - C. Amazon Redshift
    - D. Amazon DynamoDB
    - E. Amazon ElastiCache

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A B
        <p>
        Explanation: 
            1 Use Managed Service : Amazon RDS
            2 Setup your own database: Amazon EC2 + Elastic Block Store (Amazon EBS)
        </p>
    </details>


62. Which of these is an AWS managed service to allow instances in a private subnet to download software patches while denying inbound traffic from the internet?
    - A. Internet Gateway
    - B. NAT Gateway
    - C. NAT instance
    - D. AWS Direct Connect

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B
        <p>
        Explanation: 
            Overall explanation
            NAT Devices allow instances in a private subnet to download software patches while denying inbound traffic from the internet
                - NAT Instance: Install an EC2 instance with specific NAT AMI and configure as a gateway
       </p>
        </details>


63. Which of these is a fully managed continuous delivery service that helps you automate your release pipelines for fast and reliable application and infrastructure updates?
    - A. AWS CodePipeline
    - B. AWS CodeCommit
    - C. Amazon CloudWatch
    - D. AWS CodeDeploy

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A
        <p>
        Explanation: 
            CI/CD Tools:
                - AWS CodeCommit - Private source control (Git)
                - AWS CodePipeline - Orchestrate CI/CD pipelines
                - AWS CodeBuild - Build and Test Code (packages and containers)
                - AWS CodeDeploy - Automate Deployment(EC2, On premises, ECS, Lambda etc)
       </p>
        </details>

64. Which of these is NOT a category of checks provided by Trusted Advisor?
    - A. Cost optimization
    - B. Reliability
    - C. Performance
    - D. Service limits

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B
        <p>
        Explanation: 
            AWS Trusted Advisor: Provides Cost optimization, performance, security & fault tolerance recommendations
                - Cost Optimization: Unused resources, Other opportunities (ex: reserved instances)
                - Security: Settings to make your AWS solution more secure (ex: security group)
                - Fault Tolerance: Redundancy improvements, over-utilized resources
                - Performance: Improve speed and responsiveness of your AWS solutions
                - Service Limits: Is your usage is more than 80% of service limits?
       </p>
        </details>

65. Which of these AWS services helps you to run commands and apply patches on a group of Amazon EC2 instances?
    - A. AWS Marketplace
    - B. AWS Systems Manager
    - C. AWS Budgets
    - D. AWS Professional Services

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B
        <p>
        Explanation: 
             - AWS Systems Manager - Run commands(operational tasks) on Amazon EC2 instances.  Manage your OS and Database patches.
             - AWS Marketplace - Digital catalog to find, test, buy, and deploy licensed software solutions using flexible pricing options: Bring Your Own License (BYOL), free trial, pay-as-you-go, hourly, monthly etc.
       </p>
        </details>

66. Which of these is NOT a pillar in the AWS Well Architected Framework?
    - A. Operational Excellence
    - B. Security
    - C. Reliability
    - D. Resilience

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D
        <p>
        Explanation: 
            Well Architected Framework - Five Pillars
                - Operational Excellence
                - Security
                - Reliability
                - Performance Efficiency
                - Cost Optimization
       </p>
        </details>

67. Which of these are pillars in the AWS Well Architected Framework (Select 2)?
    - A. Operational Excellence
    - B. Resilience
    - C. Provisioning servers
    - D. Cost Optimization
    - D. Efficiency

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A D
        <p>
        Explanation: 
   </p>
    </details>

68. Which of these are shared responsibilities between AWS and customer under the Shared Responsibility Model? (Select 2)
    - A. Adherence of IT Infrastructure with IT security standards
    - B. Providing information on the AWS IT control environment
    - C. Patch Management
    - D. Configuration Management
    - D. Controls based on the applications deployed to AWS

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C D
        <p>
        Explanation: 

    THREE TYPES OF IT CONTROLS
        - Inherited Controls (Customer fully inherits from AWS): Physical and Environmental controls
        - Shared Controls (Controls shared by AWS and Customer)
            >>  Patch Management: AWS (Infrastructure Patches), Customer (Guest OS Patches and Software Patches)
            >>  Configuration Management: AWS (Infrastructure), Customer (Guest OS, databases, and applications)
            >>  Awareness & Training
        - Customer Owned Controls
            >>   Controls based on the applications deployed to AWS
            >>  Data Security Requirements
         </p>
    </details>

69. Which of these are NOT shared responsibilities between AWS and customer under the Shared Responsibility Model? (Select 2)
    - A. Adherence of IT Infrastructure with IT security standards
    - B. Awareness & Training
    - C. Patch Management
    - D. Configuration Management
    - E. Controls based on the applications deployed to AWS

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A E
        <p>
        Explanation: 
            Following are NOT shared responsibilities:
                - AWS ensures adherence of IT Infrastructure with IT security standards
                - Customer owns controls based on the applications deployed to AWS
       </p>
        </details>

70. Which of these AWS support plans provides you with all AWS Trusted Advisor checks? (Select 2)
    - A. Basic
    - B. Business
    - C. Developer
    - D. Operations
    - D. Enterprise

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B E
        <p>
        Explanation: 
            AWS Trusted Advisor
                - Basic and Developer plans provide 7 core checks
                - Business and Enterprise plans provide all checks
       </p>
        </details>
71. Which one of these is a design principle for AWS?
    - A. Test First
    - B. Think Parallel
    - C. Detail Orientation
    - D. Error handling

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B
        <p>
        Explanation:  Think Parallel is a design principle of AWS, which encourages users to design service architectures using highly parallelizable work to ensure higher availa
   </p>
    </details>

72. Which AWS service will help protect applications running on AWS from DDoS attacks?
    - A. Amazon GuardDuty
    - B. AWS Shield
    - C. Amazon Inspector
    - D. AWS WAF

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B
        <p>
        Explanation: 
            AWS Shield provides protection against DDoS attacks at both the application and network layers. It offers two tiers: AWS Shield Standard and AWS Shield Advanced.
            AWS Shield Standard is automatically included at no extra cost with all AWS services that are deployed on AWS infrastructure, providing protection against common and most frequently observed DDoS attacks.
            AWS Shield Advanced is a premium service that offers enhanced DDoS protection, 24/7 access to the AWS DDoS Response Team (DRT), and additional features to protect against more sophisticated and larger-scale DDoS attacks.
   </p>
    </details>

73. What design principle suggests that instead of building a single, monolithic application, it is better to break it down into smaller, loosely coupled components?
    - A. Design for modularity
    - B. Design for scalability
    - C. Decoupling components
    - D. Design for flexibility

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C
        <p>
        Explanation:  Decoupling components is a design principle that suggests breaking down a monolithic application into smaller, independent components. This approach allows for greater flexibility and scalability, as each component can be updated or replaced without affecting the entire system. It also allows for greater fault tolerance, as a failure in one component will not necessarily affect the entire system.
   </p>
    </details>

74. What is the MOST operationally efficient solution to delegate permissions for an EC2 instance to access AWS resources such as S3 and DynamoDB?
    - A. Creating an IAM user and using its access key and secret access key to create a CLI profile in the EC2 instance
    - B. Creating an IAM role with the required permissions and attaching the role to the administrative IAM user
    - C. Create an IAM role with the required permissions and attach the role to the EC2 instance.
    - D. Creating an IAM user and using its access key and secret access key in the application

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C
        <p>
        Explanation:  The recommended approach to delegate permissions for an EC2 instance to access AWS resources is by creating an IAM role with the required permissions and attaching the role to the EC2 instance. This approach reduces the risk of access key exposure and avoids the need to manage access keys for individual users. Additionally, it allows for more granular permission management and simplifies the process of rotating access keys.
   </p>
    </details>

75. Which of the following is an AWS service that enables customers to assess, implement, and automate security and compliance controls in the cloud?
    - A. AWS CloudTrail
    - B. Amazon Inspector
    - C. AWS Artifact
    - D. AWS Config

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D
        <p>
        Explanation: AWS Config is a service that allows you to assess, implement, and automate security and compliance controls in the cloud. It provides a detailed view of the configuration settings and changes of your AWS resources. With AWS Config, you can define rules for resource configurations, track changes over time, and receive notifications about resource configuration changes that violate your defined rules. This helps in maintaining a secure and compliant cloud environment.
   </p>
    </details>

76. Which of the following acts as an instance-level firewall to control inbound and outbound access?
    - A. AWS Trusted Advisor
    - B. Virtual private gateways
    - C. Security groups
    - D. Network access control list

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C
        <p>
        Explanation:  Security groups act as an instance-level firewall to control inbound and outbound access in AWS. Security groups are associated with EC2 instances and provide a virtual firewall that controls the traffic for one or more instances. They act as a stateful firewall, which means that any changes to inbound rules are automatically applied to outbound rules.
   </p>
    </details>

77. Which benefit of the AWS Cloud ensures that resources are always available and performing as expected, with minimal downtime or interruptions?
    - A. Security
    - B. Reliability
    - C. Elasticity
    - D. High Availability

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D
        <p>
        Explanation: High Availability in AWS refers to the ability of a system or application to remain operational and accessible even in the face of hardware or software failures. AWS achieves high availability by distributing resources across multiple availability zones (AZs) within a region and by providing features such as load balancing, automatic failover, and redundancy. This ensures that if one availability zone experiences an issue, the workload can seamlessly switch to another availability zone without significant disruption.
        High availability specifically addresses the goal of minimizing downtime and interruptions by providing redundant infrastructure and failover mechanisms.
   </p>
    </details>

78. How can multiple AWS accounts aid in allocating costs across departments?
    - A. By providing separate access control for each department
    - B. By allowing departments to share resources without additional costs
    - C. By providing separate billing for each department
    - D. By consolidating billing into a single payment

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C
        <p>
        Explanation: Multiple AWS accounts can be used to allocate costs across departments by providing separate billing for each department. Each department can have its own AWS account and the costs associated with that account can be allocated to that department. This helps to ensure that each department is only paying for the resources that it is using and helps to prevent one department from incurring costs that should be allocated to another department.
   </p>
    </details>

79. Which of the following options is the recommended way to get billing support on AWS?
    - A. Use the AWS Billing and Cost Management dashboard
    - B. Use third-party partners and tools
    - C. Open a billing support case
    - D. Contact your account manager

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C
        <p>
        Explanation: If you have a billing issue or question, the recommended way to get support is to open a billing support case through the AWS Support Center. This allows you to receive personalized support from AWS billing experts.
   </p>
    </details>

80. Which AWS service or tool should a company use to centrally request and track service limit increases?
    - A. AWS Service Catalog
    - B. AWS Budgets
    - C. Service Quotas
    - D. AWS Config

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C
        <p>
        Explanation: Service Quotas. This service allows you to view and manage your AWS service quotas centrally. You can request quota increases for some AWS services using Service Quotas. It is designed to help manage quotas within a multi-account environment.
   </p>
    </details>

81. What is the benefit of using a region in the AWS Cloud?
    - A. Regions provide additional security and compliance features.
    - B. Regions allow users to control the performance of their applications.
    - C. Regions allow users to choose the physical location of their data.
    - D. Regions provide access to a specific set of AWS services.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C
        <p>
        Explanation: A region is a physical location in the world where AWS has multiple data centers. Each region is completely independent and isolated from the others. Users can choose the region where their resources will be provisioned, and can also use multiple regions for high availability and disaster recovery. One of the benefits of using a region is that it allows users to choose the physical location of their data, which can help with data residency requirements and compliance.
   </p>
    </details>

82. What is the role of the Concierge for AWS Enterprise Support Plan customers?
    - A. To provide training and certification support
    - B. To provide security and compliance support
    - C. To manage AWS billing and cost optimization
    - D. To provide technical support for AWS services

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C
        <p>
        Explanation: The Concierge is a dedicated support team that provides proactive guidance and assistance for AWS Enterprise Support Plan customers. They help with billing and cost optimization, as well as account management and access to AWS resources.
   </p>
    </details>

83. Which of the following is a recommended way to protect data at rest in AWS?
    - A. Use a VPN to access AWS resources.
    - B. Use AWS Shield to protect against DDoS attacks.
    - C. Implement encryption on AWS services that support it.
    - D. Set up firewalls to block incoming traffic.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C
        <p>
        Explanation: Encrypting data at rest is a best practice to protect sensitive data stored in AWS services such as S3 and EBS. AWS provides encryption options for many of its services, including S3, EBS, RDS, and Redshift.
   </p>
    </details>

84. Which of the following is a benefit of using On-Demand Instance pricing on AWS?
    - A. Long-term cost predictability.
    - B. Maximum flexibility and no long-term commitments.
    - C. Short-term and unpredictable workloads.
    - D. Upfront payment for a specified amount of time.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B
        <p>
        Explanation:  On-Demand Instance pricing on AWS is best suited for scenarios where maximum flexibility and no long-term commitments are required. This pricing model is designed for users who need compute capacity on an as-needed basis, without any upfront payment or long-term obligation. It is ideal for applications with unpredictable workloads, or for those being tested or developed for the first time. Users pay for the compute capacity by the hour or second, depending on the instances they run, allowing them to scale up or down based on their immediate needs. This flexibility comes at a higher per-hour cost compared to other options like Reserved Instances or Savings Plans.
   </p>
    </details>

85. Which of the following operations would reduce costs by moving to the cloud?
    - A. Right-sizing infrastructure
    - B. Manually managing infrastructure
    - C. Increasing compliance scope
    - D. Using legacy software that is not compatible with the cloud

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A
        <p>
        Explanation:  Right-sizing infrastructure is an operation that would reduce costs by moving to the cloud, and is a factor that would be part of a Total Cost of Ownership (TCO) proposal. By using the cloud's ability to scale resources up or down as needed, organizations can reduce costs associated with over-provisioning or under-provisioning of infrastructure.
   </p>
    </details>

86. What is the role of the Concierge in the AWS Enterprise Support Plan?
    - A. To manage AWS resources.
    - B. To provide technical expertise for the full range of AWS services and obtain a detailed understanding of your use case and technology architecture.
    - C. To inspect your AWS environment and alert you of opportunities to save money
    - D. To serve as your primary point of contact and provide assistance with billing or account inquiries.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D
        <p>
        Explanation: Your Amazon Web Services Concierge is a senior customer service agent who is assigned to your account when you subscribe to an Enterprise or qualified Reseller Support plan. This Concierge agent is your primary point of contact for billing or account inquiries; when you don’t know whom to call, they will find the right people to help. In most cases, the Amazon Web Services Concierge is available during regular business hours in your headquarters’ geography.
   </p>
    </details>

87. Which of the following benefits of AWS cloud refers to the ability to access resources and services that are always available and fault-tolerant?
    - A. High Availability
    - B. Reliability
    - C. Security
    - D. Elasticity

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A
        <p>
        Explanation: High Availability is one of the benefits of AWS cloud. It refers to the ability to access resources and services that are always available and fault-tolerant. AWS achieves high availability by deploying resources across multiple availability zones within a region, ensuring that your applications and services remain available even if one or more availability zones experience an outage.
   </p>
    </details>

88. How does the AWS cloud enable users to focus on business value?
    - A. By offering managed services that automate common administrative tasks
    - B. By offering pay-as-you-go pricing that enables users to start small and scale up as their needs grow
    - C. By providing a global infrastructure with regions and availability zones spread across the world
    - D. By providing a comprehensive set of security services and features

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A
        <p>
        Explanation: AWS cloud enables users to focus on business value by offering managed services that automate common administrative tasks. These services include managed databases, application load balancers, and serverless computing, which reduce the burden of managing infrastructure and allow users to focus on their core business.
   </p>
    </details>

89. What is the role of OpEx in a TCO proposal for moving to the cloud?
    - A. It represents the ongoing costs associated with using and managing cloud services
    - B. It represents the cost of licensing proprietary software
    - C. It is not relevant to a TCO proposal for moving to the cloud
    - D. It represents the upfront costs of acquiring and maintaining hardware and software
    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A
        <p>
        Explanation: OpEx represents the ongoing costs associated with using and managing cloud services, such as the cost of data transfer, storage, and compute resources. These costs can be lower than the upfront costs associated with acquiring and maintaining hardware and software, which is represented by CapEx
   </p>
    </details>

90. Which AWS service provides detailed cost and usage reports?
    - A. AWS Cost and Usage Report
    - B. AWS Marketplace
    - C. Amazon QuickSight
    - D. AWS Trusted Advisor

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A
        <p>
        Explanation: AWS Cost and Usage Report. The AWS Cost and Usage Report provides detailed information about AWS usage and costs. Users can download the report and use it to understand their costs, optimize their usage, and forecast future costs.
   </p>
    </details>

91. What is AWS Simple Monthly Calculator?
    - A. A tool for calculating the cost of AWS services based on usage
    - B. A tool for monitoring AWS resource utilization
    - C. A tool for automating AWS infrastructure deployment
    - D. A tool for managing AWS user access

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A
        <p>
        Explanation: AWS Simple Monthly Calculator is a tool that allows users to estimate the cost of AWS services based on their usage. It can help users to plan and budget their AWS usage, and make informed decisions about which services to use.
   </p>
    </details>

92. Which of the following is true about managed policies in IAM?
    - A. They are defined and managed by the AWS Customer
    - B. They can only be attached to IAM groups
    - C. They cannot be modified by the AWS Customer
    - D. They are defined and managed by AWS

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D
        <p>
        Explanation: Managed policies are pre-built policies that are defined and managed by AWS. They can be attached to multiple IAM entities such as groups, users, and roles. Unlike custom policies, managed policies cannot be modified by the AWS Customer.
   </p>
    </details>

93. What is the AWS Shared Responsibility Model?
    - A. A model that outlines the shared responsibilities between AWS and its customers for ensuring security and compliance in the cloud
    - B. A model that outlines the shared responsibilities between AWS and its customers for managing and maintaining AWS infrastructure
    - C. A model that outlines the shared responsibilities between AWS and third-party vendors for providing support to AWS customers
    - D. A model that outlines the shared responsibilities between AWS and its customers for financial management of AWS services
    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A
        <p>
        Explanation: The AWS Shared Responsibility Model is a model that outlines the shared responsibilities between AWS and its customers for ensuring security and compliance in the cloud. It specifies which security responsibilities are the responsibility of the customer and which are the responsibility of AWS.
   </p>
    </details>

94. Where can you find pricing information for AWS services?
    - A. AWS Services product pages
    - B. AWS CloudFormation
    - C. AWS Marketplace
    - D. AWS CloudTrail

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A
        <p>
        Explanation: Pricing information for AWS services can be found on the AWS Services product pages. These pages provide information on pricing models, pricing examples, and pricing details for each service. Users can also use the AWS Simple Monthly Calculator or the AWS Pricing API to get pricing information for AWS services.
   </p>
    </details>

95. What are the three main cloud models?
    - A. Public Cloud, Private Cloud, Hybrid
    - B. Cloud-only, Hybrid, Virtual Machines
    - C. On-premises, Cloud-native, Hybrid
    - D. On-premises, Hybrid, Virtual Machines
    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A
        <p>
        Explanation: The different types of cloud models are public cloud, private cloud, and hybrid cloud. Public cloud refers to cloud services that are provided over the internet and are accessible to anyone who wants to use them. Private cloud refers to cloud services that are used exclusively by a single organization and are hosted either on-premises or by a third-party provider. Hybrid cloud refers to a combination of both public and private cloud services.
   </p>
    </details>

96. Which IAM entity is used to define permissions and access control for AWS resources?
    - A. Policies
    - B. Users
    - C. Groups
    - D. Roles

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A
        <p>
        Explanation: Policies are used to define permissions and access control for AWS resources. They can be attached to IAM groups, users, and roles. Policies can be either custom policies created by the user or managed policies provided by AWS.
   </p>
    </details>

97. A large company has multiple departments. Each department has its own AWS account. Each department has purchased Amazon EC2 Reserved Instances.
Some departments do not use all the Reserved Instances that they purchased, and other departments need more Reserved Instances than they purchased. The company needs to manage the AWS accounts for all the departments so that the departments can share the Reserved Instances.
Which AWS service or tool should the company use to meet these requirements?
    - A. AWS Organizations
    - B. Cost Explorer
    - C. AWS Trusted Advisor
    - D. AWS Systems Manager
    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A
        <p>
        Explanation: AWS Organizations is a service that allows an organization to consolidate multiple AWS accounts into an organization that can be centrally managed. It provides a way to manage policies across multiple AWS accounts, which can help to ensure compliance with security and compliance standards, and also allows for sharing of Reserved Instances between departments. With AWS Organizations, a master account can purchase Reserved Instances and share them with other accounts in the organization. This allows departments that do not use all their Reserved Instances to share them with departments that need more Reserved Instances. AWS Systems Manager provides a suite of tools for managing multiple AWS resources and applications, Cost Explorer provides cost and usage reports for AWS services, and AWS Trusted Advisor provides recommendations for optimizing AWS resources. While these tools can be useful for managing AWS accounts, they do not provide the functionality to manage Reserved Instances sharing between accounts.
   </p>
    </details>

98. Which of the following IAM entities can be used to grant temporary access to AWS resources?
    - A. Groups
    - B. Roles
    - C. Policies
    - D. Users
    - E. All actions taken by root users are tracked and logged within AWS Billing
    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B
        <p>
        Explanation: Roles can be used to grant temporary access to AWS resources without the need to create or manage an AWS identity. They can be assumed by trusted entities such as AWS services, IAM users or federated users, and are used to provide access to resources that would otherwise be unavailable to those entities.
   </p>
    </details>

99. Which of the following is a scenario that would best fit with On-Demand Instance pricing on AWS?
    - A. Running a development environment for a small team that only needs occasional access.
    - B. Running a high-performance computing (HPC) workload that requires specific hardware configurations.
    - C. Running an application 24/7 with predictable, steady traffic.
    - D. Running a production database that requires consistent performance and uptime.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A 
        <p>
        Explanation: On-Demand Instances are ideal for short-term and unpredictable workloads where you pay for compute capacity by the hour or the second with no long-term commitments.
   </p>
    </details>

100. Which of the following benefits of AWS cloud refers to the ability to ensure the confidentiality, integrity, and availability of your data and resources?
    - A. Security
    - B. High Availability
    - C. Reliability
    - D. Elasticity
     <details markdown=1><summary markdown='span'>Answer</summary>
     Correct answer: A
        <p>
        Explanation: On-Demand Instances are ideal for short-term and unpredictable workloads where you pay for compute capacity by the hour or the second with no long-term commitments.
</p>
    </details>

101. A company is migrating to the AWS Cloud instead of running its infrastructure on-premises.
Which of the following are advantages of this migration? (Choose two.)
    - A. Increased global reach and agility
    - B. Elimination of the need to perform security auditing
    - C. Ability to deploy globally in minutes
    - D. Redundancy by default for all compute services
     <details markdown=1>
         <summary markdown='span'>Answer</summary>
         Correct answer: A C
         <p>Explanation: Increased global reach and agility and Ability to deploy globally in minutes are advantages of migrating to the AWS Cloud instead of running infrastructure on premises.</p>
     </details>

102. What is the role of capital expenses (CapEx) in a Total Cost of Ownership (TCO) proposal?
    - A. They are a one-time cost associated with the purchase of physical assets.
    - B. They are expenses related to employee salaries and benefits.
    - C. They are ongoing expenses related to the operation and maintenance of physical assets
    - D. They are expenses related to software licensing and maintenance.
    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A
        <p>Explanation: Capital expenses (CapEx) are a one-time cost associated with the purchase of physical assets, and are a factor that would be part of a Total Cost of Ownership (TCO) proposal. This includes expenses such as hardware and software purchases.</p>
    </details>

103. A company wants to protect its AWS Cloud information, systems, and assets while performing risk assessment and mitigation tasks.
     Which pillar of the AWS Well-Architected Framework is supported by these goals?
    - A. Reliability
    - B. Security
    - C. Operational excellence
    - D. Performance efficiency
    <details markdown=1><summary markdown='span'>Answer</summary>
        Correct answer: B
        <p>Explanation:</p>
    </details>

104. A company has an AWS account. The company wants to audit its password and access key rotation details for compliance purposes.
     Which AWS service or tool will meet this requirement?
    - A. IAM Access Analyzer
    - B. AWS Artifact
    - C. IAM credential report
    - D. AWS Audit Manager
    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C
        <p>
        Explanation:  You can use credential reports to assist in your auditing and compliance efforts. You can use the report to audit the effects of credential lifecycle requirements, such as password and access key updates.
        </p>
    </details>

105. A company wants to receive a notification when a specific AWS cost threshold is reached.
     Which AWS services or tools can the company use to meet this requirement? (Choose two.)
    - A. Amazon Simple Queue Service (Amazon SQS)
    - B. AWS Budgets
    - C. Cost Explorer
    - D. Amazon CloudWatch
    - E. AWS Cost and Usage Report
    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B D
        <p>
            Explanation: B. AWS Budgets: AWS Budgets is a service that allows you to set custom cost and usage budgets for your AWS resources. You can configure a budget with a specific threshold and define actions, such as sending notifications, when that threshold is reached.
            D. Amazon CloudWatch: Amazon CloudWatch is a monitoring service that can be used to collect and track metrics, logs, and events from various AWS resources. It supports setting up alarms based on cost metrics, so you can create an alarm for a specific cost threshold and configure it to send notifications when the threshold is breached.
        </p>
    </details>

106. Which tasks are customer responsibilities, according to the AWS shared responsibility model? (Choose two.)
    - A. Configure the AWS provided security group firewall.
    - B. Classify company assets in the AWS Cloud.
    - C. Determine which Availability Zones to use for Amazon S3 buckets.
    - D. Patch or upgrade Amazon DynamoDB.
    - E. Select Amazon EC2 instances to run AWS Lambda on.
    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A B
        <p>
        Explanation:
        Not C: S3 is available across all AZ's and customer does not choose the AZ.
        Not D: Dynamo DB patching is "of the cloud", not "in the cloud", hence is AWS responsibility
        Not E: AWS Lambda is a serverless service
   </p>
    </details>

107. A company needs to block SQL injection attacks.
     Which AWS service or feature can meet this requirement?
    - A. AWS WAF
    - B. AWS Shield
    - C. Network ACLs
    - D. Security groups
    <details markdown=1>
     <summary markdown='span'>Answer</summary>
      Correct answer: A
        <p>Explanation: Confusion will come to choose between WAF or Shield. but all common web attack patterns (XSS, SQL Injection, etc...) dealt by WAF, special cases which can't be handled by WAF - will be handled by Shield primarily DDoS</p>
    </details>

108. A cloud practitioner needs to obtain AWS compliance reports before migrating an environment to the AWS Cloud.
     How can these reports be generated?
    - A. Contact the AWS Compliance team.
    - B. Download the reports from AWS Artifact.
    - C. Open a case with AWS Support.
    - D. Generate the reports with Amazon Macie.
    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B
        <p>
        Explanation: AWS Artifact is a portal that provides access to various compliance reports, including certifications, attestations, and other relevant documents. You can download these reports directly from AWS Artifact.
   </p>
    </details>

109. Which AWS service can be used at no additional cost?
    - A. Amazon SageMaker
    - B. AWS Config
    - C. AWS Organizations
    - D. Amazon CloudWatch
    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C
        <p>
        Explanation: AWS Organizations is an account management service that enables you to consolidate multiple AWS accounts into an organization that you create and centrally manage. AWS Organizations is offered at no additional charge. You are charged only for AWS resources that users and roles in your member accounts use. For example, you are charged the standard fees for Amazon EC2 instances that are used by users or roles in your member accounts.
   </p>
    </details>

110. Which AWS Cloud Adoption Framework (AWS CAF) capability belongs to the people perspective?
     - A. Data architecture
     - B. Event management
     - C. Cloud fluency
     - D. Strategic partnership
    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C
        <p>
        Explanation: 
        Data architecture => Platform
        Event management => Operations
        Cloud fluency => People
        Strategic partnership => Business
   </p>
    </details>

111. Which AWS service gives users the ability to discover and protect sensitive data that is stored in Amazon S3 buckets?
     - A. Amazon Macie
     - B. Amazon Detective
     - C. Amazon GuardDuty
     - D. AWS IAM Access Analyzer
     <details markdown=1><summary markdown='span'>Answer</summary>
     Correct answer: A
        <p>
        Explanation: Amazon Macie: A security service that uses machine learning to automatically discover, classify, and protect sensitive data, such as personally identifiable information (PII), in Amazon S3.
</p>
    </details>

112. Which AWS service can identify when an Amazon EC2 instance was terminated?
    - A. AWS Identity and Access Management (IAM)
    - B. AWS CloudTrail
    - C. AWS Compute Optimizer
    - D. Amazon EventBridge
     <details markdown=1><summary markdown='span'>Answer</summary>
     Correct answer: B
        <p>
        Explanation: AWS CloudTrail is a service that records all API activity in your AWS account, including the termination of EC2 instances. It creates log entries for various events, providing an audit trail of actions taken on resources. By reviewing CloudTrail logs, you can identify when an EC2 instance was terminated, who initiated the termination, and other relevant details about the event. 
</p>
    </details>

113. Which AWS services or features provide disaster recovery solutions for Amazon EC2 instances? (Choose two.)
     - A. EC2 Reserved Instances
     - B. EC2 Amazon Machine Images (AMIs)
     - C. Amazon Elastic Block Store (Amazon EBS) snapshots
     - D. AWS Shield
     - E. Amazon GuardDuty
     <details markdown=1><summary markdown='span'>Answer</summary>
     Correct answer: B C
        <p>
        Explanation: EC2 Amazon Machine Images (AMIs): AMIs are used to create backups of EC2 instances, and they can be used to launch replacement instances in the event of a disaster or data loss. AMIs are essential for creating recovery points for your EC2 instances.  Amazon Elastic Block Store (Amazon EBS) snapshots: EBS snapshots allow you to create point-in-time backups of your EBS volumes. These snapshots can be used to restore data or create new EBS volumes, making them a key component of disaster recovery for EC2 instances.
</p>
    </details>

114. A network engineer needs to build a hybrid cloud architecture connecting on-premises networks to the AWS Cloud using AWS Direct Connect. The company has a few VPCs in a single AWS Region and expects to increase the number of VPCs to hundreds over time.
     Which AWS service or feature should the engineer use to simplify and scale this connectivity as the VPCs increase in number?
     - A. VPC endpoints
     - B. AWS Transit Gateway
     - C. Amazon Route 53
     - D. AWS Secrets Manager
     <details markdown=1><summary markdown='span'>Answer</summary>
     Correct answer: B
        <p>
        Explanation: AWS Transit Gateway connects your Amazon Virtual Private Clouds (VPCs) and on-premises networks through a central hub. This connection simplifies your network and puts an end to complex peering relationships. Transit Gateway acts as a highly scalable cloud router—each new connection is made only once.
</p>
    </details>

115. Which AWS billing services are capable of forecasting cost and usage? select 2
     - A. AWS Cost and Usage Report
     - B. AWS Budgets
     - C. AWS Cost Explorer
     - D. Amazon Forecast
     <details markdown=1><summary markdown='span'>Answer</summary>
     Correct answer: A B
        <p>
        Explanation: 
</p>
    </details>

116. Which AWS service is used to calculate the Total Cost of Ownership?
     - A. AWS Cost Explorer
     - B. TCO Calculator
     - C. AWS Pricing Calculator
     - D. AWS Budgets
     <details markdown=1><summary markdown='span'>Answer</summary>
     Correct answer: C
        <p>
        Explanation: The AWS Pricing Calculator is the recommended tool for estimating the cost of AWS services and calculating the Total Cost of Ownership. It allows users to model and compare different configurations and scenarios, making it suitable for both initial cost estimations and ongoing cost management.
</p>
    </details>

117. Which is a significant financial benefit of shifting on-premises data center systems to AWS?
     - A. Replaces variable operational expenses (OPEX) with low upfront capital expenses (CAPEX) over time
     - B. Replaces upfront operational expenses (OPEX) with low variable operational expenses (OPEX) over time
     - C. Replaces upfront capital expenses (CAPEX) with low variable costs over time
     - D. CAPEX upfront costs are lower, adding increased privacy and security as well as computing power over time
     <details markdown=1><summary markdown='span'>Answer</summary>
     Correct answer: C
        <p>
        Explanation: This statement is correct. When organizations move from on-premises data centers to cloud services like AWS, they shift from a CAPEX model to an OPEX model. In the CAPEX model, companies incur substantial upfront costs for purchasing and maintaining physical hardware and infrastructure. When they transition to the cloud, these upfront costs are significantly reduced or eliminated, as the cloud provider owns the infrastructure. Instead, the organization pays for the services it consumes, typically on a variable cost basis, which can adjust according to the organization's usage. This model provides flexibility and can lead to cost savings, particularly for organizations that experience fluctuating demands.
</p>
    </details>

118. A company has an existing web application running on AWS Cloud within North America. The company has observed an increase of users from Asia however due to the distance between the customer and the North American these users are experiencing severe latency. The company decides to launch an identical server within an Asia Region to reduce the latency. Which benefit of AWS Cloud does this best describe?
     - A. Agility
     - B. High Availability
     - C. Global Reach
     - D. Economy of scale
     <details markdown=1><summary markdown='span'>Answer</summary>
     Correct answer: C
        <p>
        Explanation: Global Reach is about being able to provide better operational performance to new or existing but underserved geographical areas. Go global in minutes – Easily deploy your application in multiple regions around the world with just a few clicks. This means you can provide lower latency and a better experience for your customers at a minimal cost.
</p>
    </details>

119. Which AWS security services are capable of detecting publicly accessible S3 buckets in an organization where multiple departments manage their own AWS accounts?
    - A. Amazon GuardDuty
    - B. Amazon Macie
    - C. AWS IAM Access Analyzer
    - D. Amazon Detector
    - E. S3 Bucket Scanner
     <details markdown=1><summary markdown='span'>Answer</summary>
     Correct answer: B C
        <p>
        Explanation:  Macie automatically and continually evaluates all of your S3 buckets and alerts you to any unencrypted buckets, publicly accessible buckets, or buckets shared with AWS accounts outside those you have defined in the AWS Organizations.
AWS IAM Access Analyzer helps you identify the resources in your organization and accounts, such as Amazon S3 buckets or IAM roles, shared with an external entity. This lets you identify unintended access to your resources and data, which is a security risk. Access Analyzer identifies resources shared with external principals by using logic-based reasoning to analyze the resource-based policies in your AWS environment.
</p>
    </details>

120. An enterprise is evaluating whether to adopt AWS to offload most of their on-premise Virtual Machines to Ec2. The enterprise does not have much domain expertise, and they need a point of contact that will help proactively manage their account and connect them with AWS experts. Which Enterprise offering does this best describe?
    - A. AWS Technical Support
    - B. Concierge Support Team
    - C. TAM
    - D. Werner Hans Peter Vogels
     <details markdown=1><summary markdown='span'>Answer</summary>
     Correct answer: C
        <p>
        Explanation: Designated Technical Account Manager (TAM) to proactively monitor your environment and assist with optimization and coordinate access to programs and AWS experts. TAMs are part of AWS's Enterprise Support Plan and play a key role in helping customers optimize their AWS environments. They provide guidance, best practices, and expertise in AWS services. The TAM serves as a primary point of contact, helping to plan and monitor the AWS environment, and connecting the customer with other AWS experts as needed. This service is particularly valuable for enterprises that lack deep domain expertise in AWS and need ongoing support and strategic guidance.
</p>
    </details>

121. In order to use CloudWatch Alarms to monitor Billing information, what two things must you do?
    - A. Enable Cost and Usage Reports
    - B. Create a Billing Alarm
    - C. Enable Billing Alerts
    - D. Create an AWS Cost and Usage Report
    - E. Create an AWS Budget
     <details markdown=1><summary markdown='span'>Answer</summary>
     Correct answer: B C 
        <p>
        Explanation: Before you can create an alarm for your estimated charges, you must enable billing alerts, so that you can monitor your estimated AWS charges and create an alarm using billing metric data. After you enable billing alerts, you can't disable data collection, but you can delete any billing alarms that you created. After you enable billing alerts for the first time, it takes about 15 minutes before you can view billing data and set billing alarms.
</p>
    </details>

122. Which of the following are examples of Capital Expenses (CAPEX)?
    - A. IT Personnel
    - B. Subscription for software license
    - C. Datacenter Costs
    - D. Network Costs
    - D. Billing Based on Compute Metrics
     <details markdown=1><summary markdown='span'>Answer</summary>
     Correct answer: C D
        <p>
        Explanation: 
</p>
    </details>

123. Which of the following can not be used to work with AWS services programmatically?
    - A. AWS SDK
    - B. AWS Console
    - C. AWS CLI
    - D. AWS CloudShell
     <details markdown=1><summary markdown='span'>Answer</summary>
     Correct answer: B
        <p>
        Explanation: 
</p>
    </details>

124. Which of the following features of an Amazon VPC allows your VPC to span multiple Availability Zones?
    - A. Network Access Control Lists
    - B. None of these
    - C. Route Tables
    - D. Subnet
     <details markdown=1><summary markdown='span'>Answer</summary>
     Correct answer: B
        <p>
        Explanation: By default, a VPC spans all of the Availability Zones in a Region.
</p>
    </details>

125. You are planning on deploying a video-based application onto the AWS Cloud. Users across the world will access these videos. Which of the below services can help efficiently stream the content to users across the globe?
    - A. Amazon SES
    - B. Amazon CloudFront
    - C. Amazon S3
    - D. Amazon Cloudtrail
     <details markdown=1><summary markdown='span'>Answer</summary>
     Correct answer: B
        <p>
        Explanation:  Amazon CloudFront is a web service that gives businesses and web application developers an easy and cost effective way to distribute content with low latency and high data transfer speeds. Like other AWS services, Amazon CloudFront is a self-service, pay-per-use offering, requiring no long term commitments or minimum fees. With CloudFront, your files are delivered to end-users using a global network of edge locations.
</p>
    </details>

126. Which of the following are components of the AWS Compliance Programs? choose 3
    - A. Laws, Regulations, and Privacy
    - B. Certifications and Attestations
    - C. Following industry best practices
    - D. Partner Validations
    - E. Alignments and Frameworks
     <details markdown=1><summary markdown='span'>Answer</summary>
     Correct answer: A B E
        <p>
        Explanation: AWS customers remain responsible for complying with applicable compliance laws, regulations, and privacy programs.  Compliance certifications and attestations are assessed by a third-party, independent auditor and result in a certification, audit report, or attestation of compliance. Compliance alignments and frameworks include published security or compliance requirements for a specific purpose, such as a specific industry or function.
</p>
    </details>

127. Which of the following statements are FALSE when it comes to elasticity?
     - A. Diverting traffic across multiple regions
     - B. Diverting traffic to instances with high loads
     - C. Diverting traffic to instances with the least load
     - D. Diverting traffic to instances based on the demand
     <details markdown=1><summary markdown='span'>Answer</summary>
     Correct answer: A B
        <p>
        Explanation: The concept of Elasticity is the means of an application having the ability to scale up and scale down based on demand. An example of such a service is the Autoscaling service.  Auto scaling groups can span across multiple Availability Zones within a Region but cannot span across multiple Regions. You would not want to divert traffic to instances that already have high workloads. A good auto scaling policy would create more instances to offload traffic to instances so none of them have high workloads .
</p>
    </details>

128. Which is a significant financial benefit of shifting on-premises data center systems to AWS?
     - A. Replaces upfront operational expenses (OPEX) with low variable operational expenses (OPEX) over time
     - B. Replaces upfront capital expenses (CAPEX) with low variable costs over time
     - C. CAPEX upfront costs are lower, adding increased privacy and security as well as computing power over time
     - D. Replaces variable operational expenses (OPEX) with low upfront capital expenses (CAPEX) over time
     <details markdown=1><summary markdown='span'>Answer</summary>
     Correct answer:  B
        <p>
        Explanation: When organizations move from on-premises data centers to cloud services like AWS, they shift from a CAPEX model to an OPEX model. In the CAPEX model, companies incur substantial upfront costs for purchasing and maintaining physical hardware and infrastructure. When they transition to the cloud, these upfront costs are significantly reduced or eliminated, as the cloud provider owns the infrastructure. Instead, the organization pays for the services it consumes, typically on a variable cost basis, which can adjust according to the organization's usage. This model provides flexibility and can lead to cost savings, particularly for organizations that experience fluctuating demands.
</p>
    </details>

129. Which of the following does AWS perform on its behalf for EBS volumes to make it less prone to failure?
     - A. Replication of the volume across Availability Zones
     - B. Replication of the volume in the same Availability Zone
     - C. Replication of the volume across Edge locations
     - D. Replication of the volume across Regions
     <details markdown=1><summary markdown='span'>Answer</summary>
     Correct answer: B
        <p>
        Explanation: When you create an EBS volume in an Availability Zone, it is automatically replicated within that zone to prevent data loss due to failure of any single hardware component
</p>
    </details>

130. Which of the following services is most useful when a Disaster Recovery method is triggered in AWS?
     - A. Amazon SNS
     - B. Amazon Route 53
     - C. Amazon Inspector
     - D. Amazon SQS
     <details markdown=1><summary markdown='span'>Answer</summary>
     Correct answer: B
        <p>
        Explanation:  Amazon Route 53 is a highly available and scalable cloud-Domain Name System (DNS)-web service. It is designed to give developers and businesses an extremely reliable and cost-effective way to route end users to Internet applications by translating names like www.example.com into the numeric IP addresses like 192.0.2.1 that computers use to connect to each other. Amazon Route 53 is fully compliant with IPv6 as well
</p>
    </details>

131. A company is exploring the AWS services and wants a tool or method to estimate the cost that fits their business use case.
Which of the following would help them model their solutions and estimate the calculated cost for the services needed?
     - A. AWS Config
     - B. AWS Pricing Calculator
     - C. AWS Consolidating billing
     - D. AWS Cost Explorer
     <details markdown=1><summary markdown='span'>Answer</summary>
     Correct answer: B
        <p>
        Explanation: AWS Pricing Calculator is a web based service that you can use to create cost estimates to suit your AWS use cases. AWS Pricing Calculator is useful both for people who have never used AWS and for those who want to reorganize or expand their usage. AWS Pricing Calculator allows you to explore AWS services based on your use cases and create a cost estimate. You can model your solutions before building them, explore the price points and calculations behind your estimate, and find the available instance types and contract terms that meet your needs.
</p>
    </details>

132. A company wants to make an upfront commitment for continued use of its production Amazon EC2 instances in exchange for a reduced overall cost.
     Which pricing options meet these requirements with the LOWEST cost? (Choose two.)
     - A. Spot Instances
     - B. On-Demand Instances
     - C. Reserved Instances
     - D. Savings Plans
     - E. Dedicated Hosts
     <details markdown=1><summary markdown='span'>Answer</summary>
     Correct answer: C D
        <p>
            Explanation: We can rule out Spot instances since this is a production environment.
            So the right answers are:
            C. Reserved Instances: Reserved Instances provide a significant discount (up to 75%) compared to On-Demand pricing in exchange for a one-time upfront payment and/or a lower hourly rate. The more you commit, the greater the discount.
            D. Savings Plans: Savings Plans offer flexible pricing and savings on your AWS usage, with discounts of up to 72% compared to On-Demand pricing. With Savings Plans, you commit to a certain amount of usage (measured in dollars per hour) for a one- or three-year term, and receive a lower rate for that usage.
</p>
    </details>

133. A company wants to assess its operational readiness. It also wants to identify and mitigate any operational risks ahead of a new product launch.
     Which AWS Support plan offers guidance and support for this kind of event at no additional charge?
     - A. AWS Business Support
     - B. AWS Basic Support
     - C. AWS Developer Support
     - D. AWS Enterprise Support
     <details markdown=1><summary markdown='span'>Answer</summary>
     Correct answer: A
        <p>
        Explanation: But "AWS count down" premium - a service which has these features are offerd to Business, Enterprise on-ramp and Enterprise support for an additional fee. "AWS Countdown Premium is available for Business Support customers as a monthly subscription for an additional fee." " no additional cost" is misleading.
</p>
    </details>

134. Which AWS service helps deliver highly available applications with fast failover for multi-Region and Multi-AZ architectures?
     - A. AWS WAF
     - B. AWS Global Accelerator
     - C. AWS Shield
     - D. AWS Direct Connect
     <details markdown=1><summary markdown='span'>Answer</summary>
     Correct answer: B
        <p>
        Explanation: AWS Global Accelerator: A service that uses static IP addresses to route traffic over the AWS global network to optimal AWS endpoints based on health, geography, and routing policies. It provides highly available and performant applications with features like fast failover for multi-Region and Multi-AZ (Availability Zone) architectures.
</p>
    </details>

135. Question?
     - A.
     - B.
     - C.
     - D.
     <details markdown=1><summary markdown='span'>Answer</summary>
     Correct answer: E
        <p>
        Explanation: 
</p>
    </details>

136. Question?
     - A.
     - B.
     - C.
     - D.
     <details markdown=1><summary markdown='span'>Answer</summary>
     Correct answer: E
        <p>
        Explanation: 
</p>
    </details>

137. Question?
     - A.
     - B.
     - C.
     - D.
     <details markdown=1><summary markdown='span'>Answer</summary>
     Correct answer: E
        <p>
        Explanation: 
</p>
    </details>
