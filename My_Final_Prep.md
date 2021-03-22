# Networking
- **Global accelerator**: 2 Anycast IPs
- AWS network closer
- Used as TCP/UDP and global performance
- No caching
- Transit over AWS backbone
**Site-to-Site VPN**
- Encrypted using IPsec
- Quick to provision
- VGW - CGW - VPN connection
- Static VPN
- Dynamic VPN - HA and multiple connections
- Route propogation on route table in Dynamic VPN
- Speed limit - 1.25Gbps with 2 tunnels
- VPN on public internet and latency concerns
- VPNs can be used as backup for Direct connect
**Transit Gateway**
- Transitive routing
**Advanced VPC routing**
- Ingress routing - Gateway route tables
- Site-2-Site VPN - accelerated - Global accelerator
- Only TGW
**Direct Connect**
- 1 Gbps or 10 Gbps
- No encryption. Use public VIF and site-2-site VPN
- DX LAGS: 
- 