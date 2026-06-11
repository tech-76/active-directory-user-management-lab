# Account Lockout Troubleshooting

## Purpose

Account lockouts happen when a user account is locked after repeated failed sign-in attempts. Help desk teams troubleshoot lockouts to restore access and identify the source of failed logins.

## Common Causes

- User entered wrong password multiple times
- Saved old password on phone or email app
- Mapped drive using old credentials
- Remote desktop session with old credentials
- Scheduled task using old credentials
- VPN client using old credentials
- User recently changed password
- Possible unauthorized access attempt

## Initial Questions

- When did the lockout start?
- Did the user recently change their password?
- Is the issue happening repeatedly?
- Is the user signed in on multiple devices?
- Does the user use VPN?
- Does the user access email on a phone?
- Are any applications asking for the old password?

## Basic Troubleshooting Workflow

1. Verify the user's identity.
2. Confirm the account is locked.
3. Unlock the account if approved.
4. Ask the user to stop repeated sign-in attempts.
5. Confirm whether the user recently changed their password.
6. Check common sources of old saved passwords.
7. Ask the user to update credentials on all devices.
8. Reset password if required.
9. Monitor for repeated lockouts.
10. Escalate if lockouts continue.

## Common Sources to Check

- Outlook desktop
- Mobile email app
- Wi-Fi profile
- VPN client
- Remote desktop saved credentials
- Mapped network drives
- Browser saved passwords
- Windows Credential Manager

## Escalation Triggers

- Repeated lockouts after reset
- Lockouts outside normal working hours
- Sign-ins from unusual locations
- Privileged account involved
- Multiple users affected
- Possible brute-force attack

## Example Ticket Note

Unlocked user account after identity verification. User recently changed password and still had old credentials saved on mobile email app. User updated saved password and confirmed account no longer locked.
