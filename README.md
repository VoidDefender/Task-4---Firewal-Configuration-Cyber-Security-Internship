# Task 4 - Firewall Configuration | Cyber Security Internship

## Objective:

Configure and test basic firewall rules using **UFW (Uncomplicated Firewall)** on Linux. Understand how to block or allow network traffic on specific ports and verify the behavior through command-line testing.

---

## Tool Used:

- UFW (Uncomplicated Firewall)
- Platform: Linux (Ubuntu/Debian based)

---

## Actions Performed:

1. Enabled UFW and verified default rules.
2. Blocked inbound traffic on port **23** (Telnet).
3. Allowed inbound traffic on port **22** (SSH).
4. Tested port blocking and connection behavior.
5. Removed the Telnet block to restore original state.
6. Verified the final firewall rule configuration.

---

## Files Included:

- `Summary.md` – Date, tool, objectives, and author.
- `Firewall Rules.md` – All UFW commands and actual outputs.
- `Firewall Test Result.md` – Test results verifying port block and allow behavior.
- `Terminal-Outputs/`
  - `firewall-rules.md` – Full UFW rule status and application steps.
  - `port-23-blocked-test.md` – Telnet block test command and result.
  - `ssh-allowed-rule.md` – SSH allow rule verification.

---

## Learning Outcomes:

- Learned how to use UFW to allow and deny specific ports.
- Understood the difference between inbound and outbound rules.
- Gained hands-on experience with testing network port restrictions.
- Improved understanding of firewall behavior and rule priority.

---
