# Firewall Rules | UFW Commands and Outputs

## 1. Enable UFW

sudo ufw enable

Output:
Firewall is active and enabled on system startup

---

## 2. Check Current Rules and Status

sudo ufw status verbose

Output:
Status: active  
Logging: on (low)  
Default: deny (incoming), allow (outgoing), disabled (routed)  
New profiles: skip  

    To                         Action      From  
    --                         ------      ----  
    22/tcp                     ALLOW       Anywhere

---

## 3. Block Inbound Traffic on Port 23 (Telnet)

sudo ufw deny 23

Output:
Rule added  
Rule added (v6)

---

## 4. Allow SSH (Port 22)

sudo ufw allow 22

Output:
Rule added  
Rule added (v6)

---

## 5. Delete the Rule for Port 23

sudo ufw delete deny 23

Output:
Deleting: deny 23  
Proceed with operation (y|n)? y  
Rule deleted  
Rule deleted (v6)

---

## 6. Final Rule Check

sudo ufw status numbered

Output:
Status: active  

    To                          Action        From  
    --                          ------        ----  
    22/tcp                      ALLOW        Anywhere

---
