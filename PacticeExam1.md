- SWF
- MTurk
- VPC peering
- Shared subnets
- AWS RAM
- CloudTrail - Global option
- Config
- Parameter store
- Direct connect LAG - public, private
- Inter-region VPC peering - Although the Inter-Region VPC Peering provides a cost-effective way to share resources between regions or replicate data for geographic redundancy, its connections are not dedicated and highly available
- CloudFront - encryption and cache 
- Use field level encryption. To use this, origin must support chunked encoding.
- Manage cache
- DynamoDB uses federated access using Web Identity Provider, and uses fine grained access privileges for authenticating the access
- AWS Management Portal for vCenter is primarily used as an easy-to-use interface for creating and managing AWS resources from VMware vCenter.
- Vm import/export
- SSM - Patch manager
- **AWS SCT** agent to extract data from your on-premises data warehouse and migrate it to Amazon Redshift
- You can then use AWS SCT to copy the data to Amazon Redshift.
- Route53 Alias A-record
- Redis: [AOF](https://docs.aws.amazon.com/AmazonElastiCache/latest/red-ug/RedisAOF.html)
- Stored volumes provide your on-premises applications with low-latency access to the entire datasets.
- You can create storage volumes and mount them as iSCSI devices from your on-premises application servers. Data written to your stored volumes are stored on your on-premises storage hardware. These data are asynchronously backed up to Amazon S3 as Amazon Elastic Block Store (Amazon EBS) snapshots
- Cached volume gateway provides you low-latency access to your frequently accessed data but not to the entire data.
- OpsWork: [AutoHealing](https://docs.aws.amazon.com/opsworks/latest/userguide/workinginstances-autohealing.html)
- SCPs do not affect any service-linked role. Service-linked roles enable other AWS services to integrate with AWS Organizations and can’t be restricted by SCPs.
- With AWS Direct Connect plus VPN, you can combine one or more AWS Direct Connect dedicated network connections with the Amazon VPC VPN. This combination provides an IPsec-encrypted private connection that also reduces network costs, increases bandwidth throughput, and provides a more consistent network experience than Internet-based VPN connections.
- For a more cost-effective solution, you can configure a backup VPN connection for failover with your AWS Direct Connect connection.
- If you want a short-term or lower-cost solution, you might consider configuring a hardware VPN as a failover option for a Direct Connect connection. 
- Register the domain name on Route 53 and enable DNSSEC validation for all public hosted zones to ensure that all DNS requests have not been tampered with during transit. Use AWS Certificate Manager (ACM) to generate a valid TLS/SSL certificate for the domain name. Configure the Application Load Balancer with an HTTPS listener to use the ACM TLS/SSL certificate. Use Server Name Identification and HTTP to HTTPS redirection on CloudFront.
- If your Lambda function needs Internet access, attach it only to private subnets with Internet access through a NAT instance or an Amazon VPC NAT gateway.
# Exam 3
1. To achieve performance for HPC cluster place it in a placement group.
	1. Cluster - low-latency network for HPC apps.
	2. Partitiion - No partition share same hardware, workloads like Hadoop, Cassandra, Kafka
	3. Spread - distinct hardware to avoid failuers.
	4. **Elastic Fabric Adapter** : EFA OS to enhance network performances.
	5. FSx - HPC workloads, video processing, ML modelling.
