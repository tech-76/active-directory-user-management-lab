# Sample Organizational Unit Structure

## Purpose

This sample OU structure shows how an organization may organize users, computers, service accounts, and disabled accounts in Active Directory.

This is a learning example only. Real environments may use different structures.

## Sample OU Diagram

```text
example.local
│
├── OU=Users
│   ├── OU=Administration
│   ├── OU=Finance
│   ├── OU=Human Resources
│   ├── OU=IT
│   ├── OU=Operations
│   └── OU=Sales
│
├── OU=Computers
│   ├── OU=Desktops
│   ├── OU=Laptops
│   ├── OU=Shared Workstations
│   └── OU=Servers
│
├── OU=Groups
│   ├── OU=Security Groups
│   └── OU=Distribution Groups
│
├── OU=Service Accounts
│
├── OU=Admin Accounts
│
└── OU=Disabled Accounts
    ├── OU=Disabled Users
    └── OU=Disabled Computers
```

## Why This Structure Helps

- Keeps users organized by department
- Separates computers from users
- Keeps disabled accounts away from active accounts
- Makes Group Policy application easier
- Makes account reviews easier
- Supports cleaner onboarding and offboarding

## Example Help Desk Use Cases

| Task | OU Area |
|---|---|
| New employee account | `OU=Users` under correct department |
| Company laptop joined to domain | `OU=Computers/OU=Laptops` |
| Departed user account | `OU=Disabled Accounts/OU=Disabled Users` |
| Shared application group | `OU=Groups/OU=Security Groups` |
| Service account | `OU=Service Accounts` |

## Best Practice Notes

- Do not move accounts without approval.
- Follow the company's naming and OU standards.
- Keep disabled accounts organized.
- Use security groups for access management.
- Document account moves in support tickets.
