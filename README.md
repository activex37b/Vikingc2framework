# 🔱 VikingC2Framework

**VikingC2Framework** is a custom Command and Control (C2) framework designed for red team operations and adversary simulation. Built with modularity, stealth, and flexibility in mind, it enables secure command execution, file transfer, and session management on compromised systems during authorized testing engagements.


<p><img width="1356" height="1000" alt="vikingc2 interface" src="https://github.com/user-attachments/assets/16a68909-e332-4e6a-a7f6-7d5c2c5158dc" /></p>




<p><img width="1347" height="1000" alt="commandexecution" src="https://github.com/user-attachments/assets/903844ff-b69f-4c0c-aff5-ae276909d1ac" /></p>








---

## 🚀 Features

- Encrypted C2 communication (beacon-based)
- Interactive remote shell sessions
- File upload/download support
- Modular structure for adding custom post-exploitation tools
- Windows and Linux agent compatibility
- Session and task logging for reporting

---

## 🛠️ Usage

> ⚠️ **Note:** Use only in lab environments or with explicit authorization.

```bash
# Start the C2 server
python3 Vikingc2.py

# Testing the agent on target machine
go run nimbo.go


# Deploy the agent on target machine
To deploy on target please check instruction on how to build go script into binary for various operating system architecture
