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

18. Question?
    - A.
    - B.
    - C.
    - D.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D
        <p>
        Explanation: 
   </p>
    </details>

19. Question?
    - A.
    - B.
    - C.
    - D.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D
        <p>
        Explanation: 
   </p>
    </details>