# 📁 Basic Linux Commands Cheat Sheet

## 📂 File & Directory Management
| Command | Description |
|--------|-------------|
| `pwd` | Show current directory |
| `ls` | List files and directories |
| `ls -l` | Long listing format |
| `ls -a` | Show hidden files |
| `cd [dir]` | Change directory |
| `cd ..` | Go up one directory |
| `mkdir [dir]` | Create a new directory |
| `rmdir [dir]` | Remove empty directory |
| `rm -r [dir]` | Remove directory and contents |
| `touch [file]` | Create an empty file |
| `cp [src] [dest]` | Copy file/directory |
| `mv [src] [dest]` | Move or rename file/directory |
| `rm [file]` | Remove a file |

---

## 📄 File Viewing & Editing
| Command | Description |
|--------|-------------|
| `cat [file]` | Show contents of file |
| `more [file]` | View file (paged) |
| `less [file]` | View file (paged, scrollable) |
| `head -n 10 [file]` | First 10 lines |
| `tail -n 10 [file]` | Last 10 lines |
| `nano [file]` | Simple text editor |
| `vim [file]` | Vim editor |
| `echo "text" > file.txt` | Write to file (overwrite) |
| `echo "text" >> file.txt` | Append to file |

---

## 🔍 Searching
| Command | Description |
|--------|-------------|
| `grep "text" file.txt` | Find text in a file |
| `grep -r "text" /dir` | Recursively search in dir |
| `find /path -name file.txt` | Find file by name |

---

## 🔐 Permissions
| Command | Description |
|--------|-------------|
| `chmod 755 file` | Change permissions |
| `chown user:group file` | Change owner and group |
| `ls -l` | View permissions & owner |

---

## 🧠 System Info
| Command | Description |
|--------|-------------|
| `uname -a` | System info |
| `df -h` | Disk space usage |
| `free -m` | Memory usage |
| `top` / `htop` | System processes |
| `uptime` | Uptime |
| `whoami` | Current user |

---

## 🧩 Process Management
| Command | Description |
|--------|-------------|
| `ps aux` | List processes |
| `kill [PID]` | Kill process |
| `kill -9 [PID]` | Force kill |
| `pkill name` | Kill by name |

---

## 🌐 Networking
| Command | Description |
|--------|-------------|
| `ip a` | IP address info |
| `ping example.com` | Test network |
| `netstat -tuln` | Listening ports |
| `curl http://url` | Make HTTP request |
| `wget http://url` | Download file |

---

## 📦 Package Management

### Ubuntu/Debian:
```bash
sudo apt update
sudo apt install [package]
sudo apt remove [package]
