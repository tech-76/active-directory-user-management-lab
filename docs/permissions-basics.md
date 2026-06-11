# Permissions Basics

## Purpose

Permissions control what users can access and what actions they can perform. In Active Directory environments, permissions are often managed using security groups.

## Common Permission Types

| Permission | Meaning |
|---|---|
| Read | User can view the resource |
| Write | User can modify the resource |
| Modify | User can read, write, change, and delete content |
| Full Control | User can fully manage the resource |
| No Access | User cannot access the resource |

## Access Control Concepts

- Users should receive only the access they need.
- Access should usually be assigned through groups.
- Direct user permissions can be harder to manage.
- Sensitive access should require approval.
- Permissions should be reviewed regularly.

## Common Help Desk Access Requests

- User needs shared folder access
- User cannot open a network drive
- User needs access to a printer
- User needs application access
- User needs access removed after role change

## Basic Access Troubleshooting

1. Confirm the user is signing in correctly.
2. Confirm the resource path or application name.
3. Confirm the user is in the approved security group.
4. Ask user to sign out and back in if group membership changed.
5. Confirm the issue is not local device or network related.
6. Escalate if permissions appear incorrect.

## Security Notes

- Never grant access without approval.
- Do not add users to admin groups unless clearly authorized.
- Avoid broad permissions when limited permissions are enough.
- Document all access changes.
- Escalate unusual access requests.

## Example Ticket Note

User requested shared folder access. Verified approval from manager and added user to the approved security group. User signed out and back in, then confirmed access was working.
