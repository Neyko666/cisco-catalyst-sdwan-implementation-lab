# cisco-catalyst-sdwan-implementation-lab
Overall device deployment: 
vManage *1
vSmart *1
vBond *1
vEdge *4
cEdge *2
<br>
Technologies implemented:
• Onboarded SD-WAN contollers and WAN edges initially with CLI and migrated to templates
• Deployed OSPF, EIGRP, IBGP respectively on site 2, 3 and 4 for underlay networks 
• Network segmentation (transport vpn0, management vpn512, service vpn1, 2) and data isolation
• TLOC Extention allowing WAN Edges with single transport link to have dual transport and failover (site 4)
• NAT on TLOC with internet color 
• AAR(Application Aware Routing) and SLA policies (protocol based, DPI, etc)
• Create Zone-Based-Policy firewall and security policies restricting SSH traffic
<br>
GNS3 dedicated server specs:
Model: Dell PowerEdge R630
RAM: 96G(42G assigned)
CPU: 36 cores(26 assigned)
Storage: 600G
OS: Proxmox VE 8.3
<br>
<br>
<div align = "center">
<img src="https://github.com/Neyko666/hospital-system-network-design/assets/171580092/070d1b30-8d74-478d-a6a8-6ddc778b95ed" width="800">
</div>
<br>
<br>
<div align = "center">
<img src="https://github.com/Neyko666/hospital-system-network-design/assets/171580092/c138d575-125a-4c26-8428-a96ccb26f0c1" width="800">
</div>
<br>
<br>
<div align = "center">
<img src="https://github.com/Neyko666/hospital-system-network-design/assets/171580092/1f46b944-1e29-499c-a979-2126a673e100" width="800">
</div>
<br>
<br>
<div align = "center">
<img src="https://github.com/Neyko666/hospital-system-network-design/assets/171580092/5308d61a-26d7-4dcd-ba3c-0edfda94e15c" width="800">
</div>
<br>
<br>
<div align = "center">
<img src="https://github.com/Neyko666/hospital-system-network-design/assets/171580092/d67e3ae5-0357-4195-a247-8a61ddbe2f07" width="800">
</div>
<br>
<br>
<div align = "center">
<img src="https://github.com/Neyko666/hospital-system-network-design/assets/171580092/f2503719-7b5a-4852-8948-8aba2dee203f" width="800">
</div>
<br>
<br>
<div align = "center">
<img src="https://github.com/Neyko666/hospital-system-network-design/assets/171580092/932ab65c-bf4c-495a-8a65-82780f927071" width="800">
</div>
<br>




