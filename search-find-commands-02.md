# 🔍 Searching & Finding
- Search file by name
```
find /path -name filename
```
- Search text in file
```
grep "text" file.txt
```
- Recursively search in directory
```
grep -r "text" /dir
```

# 🛠️ File Permissions
- Change file permissions
```
chmod [mode] file
chmod 644 file
```
- Change file owner and group
```
chown user:group file
```
- View current permissions and owners
```
ls -l
```

# 🧠 System Information
- Kernel & system info
```
uname -a
```
- Disk space usage
```
df -h
lsblk
```
- Memory usage
```
free -m
free -g
```
- Real-time system processes
```
top / htop
```
- System uptime
```
uptime
```
- Current logged-in user
```
whoami
```

# 🧩 Process Management
- Show all running processes
```
ps aux
```
- Kill process by ID
```
kill [PID]
```
- Force kill
```
kill -9 [PID]	
```
- Kill by process name
```
pkill [name]
```