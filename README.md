# 🔱 VikingC2Framework

**VikingC2Framework** is a custom Command and Control (C2) framework designed for red team operations and adversary simulation. Built with modularity, stealth, and flexibility in mind, it enables secure command execution, file transfer, and session management on compromised systems during authorized testing engagements.

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
./agent.exe
