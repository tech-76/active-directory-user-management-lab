# Ticket: Active Directory Account Lockout

## Ticket Summary

User reported they were unable to sign in because their account was locked.

## User Impact

User could not access workstation, email, and network resources.

## Reported Issue

User stated that after changing their password, they were repeatedly locked out of their account.

## Troubleshooting Steps

1. Verified user identity.
2. Confirmed account was locked in Active Directory.
3. Unlocked the account.
4. Asked user about recent password changes.
5. Confirmed the user had email configured on a mobile phone.
6. User updated the saved password on the mobile email app.
7. Confirmed the user could sign in successfully.
8. Monitored for repeated lockout during the support session.

## Findings

The likely cause was an old saved password on the user's mobile email app.

## Resolution

Unlocked account and guided user to update saved credentials on mobile device. User confirmed account remained unlocked and access was restored.

## Final Ticket Note

Verified identity, unlocked AD account, identified likely old mobile email password as the source of repeated lockouts, and confirmed user access restored.
