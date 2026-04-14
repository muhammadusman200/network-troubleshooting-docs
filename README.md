# Network Troubleshooting & Cloud Infrastructure Docs

Real-world documentation from hands-on IT work — network issues, 
cloud management, firewall configs, and more.

---

## Firewall Management

### App Restriction via Firewall
- Block specific applications using firewall rules
- Create inbound/outbound rules for app control
- Use Azure Network Security Groups (NSG) to restrict traffic

### Firewall Best Practices
- Always use deny-all default rule
- Allow only required ports (80, 443, 3389)
- Review firewall logs weekly
- Separate rules for internal vs external traffic

---

## Azure Cloud Management

### Common Azure Tasks
- Setting up Virtual Machines (VMs)
- Configuring Virtual Networks (VNet)
- Managing Network Security Groups (NSG)
- Azure Active Directory user management
- Resource group organization

### Rujie Load Balancing
- Use Azure Load Balancer for traffic distribution
- Configure health probes to monitor backend VMs
- Set load balancing rules for port 80/443
- Use Application Gateway for app-level routing

## Network Troubleshooting

### Common Issues & Fixes

| Problem | Cause | Fix |
|---|---|---|
| No internet | DNS failure | Change DNS to 8.8.8.8 |
| Slow network | Bandwidth overload | Check QoS settings |
| Can't reach server | Firewall blocking | Check NSG rules |
| VPN not connecting | Wrong config | Re-check gateway IP |
| IP conflict | DHCP issue | Release/renew IP |

---

## VPN & Remote Access

- Configure Site-to-Site VPN on Azure
- Set up Point-to-Site VPN for remote workers
- Troubleshoot VPN connectivity issues
- Manage remote desktop access securely

---

## Documentation & Runbooks

- Always document every network change
- Keep before/after screenshots
- Note date, time, and reason for changes
- Test changes in staging before production
