# Design for New Solutions
   - Security requirements and controls
   - Strategy for reliability
   - Business continuity
   - Performance
   - Deployment startegy

- AWS WorkDocs: “content management”, “collaboration” and “document sharing”
- WAF - flood attack, XSS and SQL injections
- WAF web ACLs - Cloudfront, API gateway, ALBs
- Shield Std and Advanced for exclusive DDoS attack.
- Advanced Shield + EIPs allows to protect NLBs
- Use CloudFront + Route53 to infrastructure attacks
- CloudFront can mitigate common DoS, SYN floods, UDP reflections attacks from reaching your origin.
- Route53 uses shuffle sharding and anycast striping to counter DDoS.
# Storage
1. FSx for windows file server
2. Integrates with Directory or Managed AD
3. Support volume shadow/versions
4. Support VSS features
5. SMB file system - Windows - FSx
6. Windows permission model - files, folders and permissions
7. DFS - distributed file system
8. FSx Luster - HPC loads
9. File systems for performance and support POSIX
10. Scratch or Persistent deployment types
11. hsm_archive command to write data back to S3 from Luster
12. EFS - Linux File system
13. Linux based filesystems - NSFv4 protocol
14. Can be mounted on many EC2 instances
15. General and Max I/O modes
16. Bursting and Provisioned throughput modes
17. 