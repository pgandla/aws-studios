# Cost Control

1. Select a cost-effective pricing model for a solution
2. Determine which controls to design and implement that will ensure cost optimization
3. Identify opportunities to reduce cost in an existing solution
- Pricing models
	- Pay-as-you-go or on-demand
	- Long term reservations
	- Spot
	- Volume discounts
- Spot use for extra capacity, stateless servers and handle interruptions.
- Mixed pricing model - for example Redshift - one reserved leader node and mix of on-demand or spot nodes.
- S3 intelligent tiering
- Delete idle resources
- Rightsizing
- Enterprise programs
- Savings plan
- Scheduling
- RIs
-  Spot, Serverless, Auto scaling, cost-aware architecture
- Tools : Cost explorer, Organizatinal mechanisms, AWS Budgets
- Oversized resources
- Compute Optimizer, Resource optimizer, Trusted advisor
- Instance scheduler
- EC2 Savings Plans - Instance type + region
- Compute Savings plans 

##  9 ways to reduce bill
	- Stop paying for idle EC2 and RDS instances
	- Resize Redshift clusters. Elastic resize
	- S3 intelligent tiering 
	- On-demand dynamoDB 
	- Underutilized EC2 instances
	- Cleanup underutilized Network resources - Use TA
	- Choose Spot instances
	- Compute savings plans
	- Use RIs

## [Cost-effective on AWS](https://youtu.be/Kj0TgxbKKc0)
- AWS Budget
- 