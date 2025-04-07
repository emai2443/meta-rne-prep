# Scripting

This folder contains Python scripts to automate network operations and parse logs.

## Sample Scripts:

- [Log Parser](#)
- [Ping Sweep Tool](#)
- [SSH Automation with Paramiko](#)

## Starter Template:

```python
import paramiko

def ssh_connect(host, user, password):
    client = paramiko.SSHClient()
    client.set_missing_host_key_policy(paramiko.AutoAddPolicy())
    client.connect(host, username=user, password=password)
    return client
```
