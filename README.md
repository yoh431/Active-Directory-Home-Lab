# Homelab Projects

A hands-on IT lab built in VirtualBox to simulate enterprise IT support — Active Directory, 
Group Policy, PowerShell automation, and helpdesk ticketing.

> Built to develop practical skills for an IT support apprenticeship, not just to follow tutorials.

---

## Lab environment

| Component | Detail |
|---|---|
| Virtualisation | VirtualBox |
| Server OS | Windows Server 2022 |
| Client OS | Windows 10 Pro |
| Domain | `mydomain.local` |
| Domain Controller | DC01 — 192.168.1.10 |

---

## Projects

| # | Project | What it covers |
|---|---|---|
| 1 | [Active Directory Setup](./active-directory/README.md) | DC setup, OUs, users, domain join, helpdesk tasks |
| 2 | [PowerShell User Management](./powershell-scripts/README.md) | Bulk AD user creation + offboarding via CSV |
| 3 | [Group Policy Objects](./group-policy/README.md) | Password policy, account lockout, desktop restrictions |
| 4 | [osTicket Helpdesk](./osticket-helpdesk/README.md) | Full ticket lifecycle simulation |

---

## What I learned

These projects gave me hands-on experience with the tasks that come up daily in IT support:
resetting passwords, managing accounts, joining machines to a domain, enforcing security 
policies, and working through real configuration errors. Every troubleshooting log entry 
reflects an issue I actually hit and had to diagnose myself.

---

## Roadmap

| Status | Task |
|---|---|
| ✅ Done | Active Directory + domain join |
| ✅ Done | PowerShell bulk user management |
| ✅ Done | Group Policy Objects |
| ✅ Done | osTicket helpdesk simulation |
| 🔲 Planned | File server with NTFS permissions + audit logging |
| 🔲 Planned | Second client VM for GPO testing |
