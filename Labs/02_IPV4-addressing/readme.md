# 🛰️ Lab 1: Configure, Verify, and Troubleshoot IPv4 Addresses  

## 🎯 Objective  

The goal of this lab is to learn how to configure IPv4 addresses on Cisco router interfaces, verify connectivity, and troubleshoot common addressing issues using Cisco IOS commands.  

## 📘 Purpose  

Configuring IPv4 addressing is one of the most **fundamental skills** for a Cisco engineer. In real-world networking (and in the CCNA exam), you’ll not only configure IP addresses but also fix incorrect setups. This lab builds confidence with essential verification and troubleshooting commands.  

## 🛠️ Solution  

1. Assigned the correct IPv4 addresses and subnet masks to router interfaces:  
   - S0/0 → 172.16.1.1 /26  
   - S0/1 → 172.16.1.2 /26  

2. Enabled the interfaces with the `no shutdown` command.  


3. Verified configuration with `show ip interface brief`.  

4. Tested end-to-end connectivity using `ping`.  

5. Troubleshot initial issues (interface was down, fixed by `no shutdown`).  

✅ After applying these steps, R1 successfully pinged R3.  




