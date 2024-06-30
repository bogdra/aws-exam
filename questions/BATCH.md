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
       Explanation: - Well Architected Framework - Five Pillars
            - Operational Excellence
              - Security
              - Reliability
              - Performance Efficiency
              - Cost Optimization
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
            Compliance responsibilities will be shared
        - AWS ensures adherence of IT Infrastructure with IT security standards
        - AWS provides information on its IT control environment (white papers,  certifications, etc)
        - Customers perform their evaluation (use AWS control and compliance documentation)
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
    - D. - AWS CLI (Command Line Interface)
         - Execute Commands
         - Create Scripts
         - Use IAM Users Credentials - access key ID and secret access key

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
            - Classic Load Balancer: Old generation. Not Recommended by AWS.
            - Application Load Balancer: Most popular and frequently used ELB in AWS. Supports HTTP/HTTPS (Layer 7) and Advanced Routing(Headers, Query Params, Path and Host Based)
            - Network Load Balancer: For very high performance usecases
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
        Explanation:  
- Amazon CloudWatch Metrics - Metrics for AWS services Example EC2: CPUUtilization, NetworkIn, NetworkOut
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
            - Use Managed Service : Amazon RDS
            - Setup your own database: Amazon EC2 + Elastic Block Store (Amazon EBS)
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
71. Question?
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

72. Question?
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

68. Question?
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