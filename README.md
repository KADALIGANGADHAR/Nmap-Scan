# Network Scanning with Nmap

**Purpose**: Identify open ports, services, OS details, and vulnerabilities.

## Installation
### **Nmap is pre-installed on Kali Linux. If needed:```sudo apt update && sudo apt install nmap ```**

![Image](https://github.com/user-attachments/assets/9616ca18-7267-4feb-8e7b-fc8663ab0ed2)

### Common Scans to Perform:
### 1️.Basic Port Scan:```nmap  <target-IP>```

![Image](https://github.com/user-attachments/assets/09857841-3c79-4049-b28d-bb10575fe3db)

### 2️.Service & Version Detection:```nmap -sV  <target-IP>```

![Image](https://github.com/user-attachments/assets/7e06b4e5-3b8c-4aa6-9c0b-e5235719a542)

### 3️.Aggressive Scan (OS Detection, Services, Scripts, etc.):```nmap -A  <target-IP>```

![Image](https://github.com/user-attachments/assets/c2d99a23-b064-46ad-aaf3-674a7b8cac62)

### 4️.Scan All Ports (0-65535):``` nmap -p-  <target-IP>```

![Image](https://github.com/user-attachments/assets/8ca86f30-4c0d-45f0-968f-8af8e566ad67)

### Save Output:```nmap -sV -A -oN nmap_scan.txt  <target-IP>```

![Image](https://github.com/user-attachments/assets/022cacd7-246b-4f4f-ac2b-f1726b904369)

![Image](https://github.com/user-attachments/assets/d8549d5c-08a2-4232-a54e-c24dca8e9258)

![Image](https://github.com/user-attachments/assets/251e2275-5603-405b-85bb-f71e4fc1e491)

![Image](https://github.com/user-attachments/assets/02ce81b3-c3a4-41ba-84e7-d7a081b72bde)

![Image](https://github.com/user-attachments/assets/48f35d3b-d55a-4e30-ac05-3d2e90cf22ca)

![Image](https://github.com/user-attachments/assets/911b8d56-1a36-4f22-a66a-b422ad724b17)

![Image](https://github.com/user-attachments/assets/ae319fd0-f7a5-4b0b-9c9d-479ed3972114)

![Image](https://github.com/user-attachments/assets/6e200c72-2468-4c5f-991b-98d67b455434)

![Image](https://github.com/user-attachments/assets/b857e10f-6615-4981-aba5-2a1fcab64b21)
   ## Used Metasploitable Ip for Scanning
![Image](https://github.com/user-attachments/assets/13a8a2be-248a-49d8-b540-5611b69e8df1)

## Conclusion

**This project showcases the powerful capabilities of Nmap for performing comprehensive network scanning in a home lab environment. By targeting a vulnerable machine like Metasploitable, you gained hands-on experience in:**

**⚙Discovering open ports and running services.**

**⚙Identifying service versions and OS fingerprints.**

**⚙Running aggressive scans for deeper enumeration.**

**Nmap is an essential tool in any cybersecurity professional's toolkit. It helps in reconnaissance, vulnerability assessment, and penetration testing. Regular practice strengthens your ability to uncover potential attack surfaces and prepare defenses against them.**


