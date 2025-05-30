# Output – Telnet Block Test

Command:

    sudo ufw deny 23

Output:

    Rule added  
    Rule added (v6)

---

Command:

    telnet localhost 23

Output:

    Trying 127.0.0.1...  
    telnet: Unable to connect to remote host: Connection refused

---
