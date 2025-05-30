# Firewall Test Result

## Step 1: Telnet Test (Before Blocking)

Command:

telnet localhost 23

Result:

Connection succeeded (if Telnet service running)

---

## Step 2: Block Telnet

Command:

sudo ufw deny 23

Result:

Rule added  
Rule added (v6)

---

## Step 3: Telnet Test (After Blocking)

Command:

telnet localhost 23

Result:

Trying 127.0.0.1...  
telnet: Unable to connect to remote host: Connection refused

---

## Step 4: Allow SSH

Command:

sudo ufw allow 22

Result:

SSH port remains open and reachable.

---

## Step 5: Remove Telnet Rule

Command:

sudo ufw delete deny 23

Result:

Rule deleted

---
