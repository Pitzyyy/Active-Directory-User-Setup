# Active Directory — User Setup

## Description

A basic Active Directory lab showing the new hire onboarding process. It covers setting up a new user account, issuing a temporary password, forcing a password update on first login, and placing the account into the appropriate Organizational Unit (OU).

## Environment Used

- Windows Server 2022
- VMware Workstation

## Lab walk-through

Creating a new user account in Active Directory:

![Create new user](./assets/images/create_user.png)

Assigning a temporary password and enforcing password change at next logon:

![Temporary password](./assets/images/temp_password.png)

Verifying user placement in the correct Organizational Unit (OU):

![Verify OU placement](./assets/images/verify_ou.png)

---

Notes

- Upload your images to `assets/images/` in this repository and name them `create_user.png`, `temp_password.png`, and `verify_ou.png` (or update the paths above to match your filenames).
- If you need to control width/height, use an HTML tag, for example:

  <img src="./assets/images/create_user.png" alt="Create new user" style="max-width:80%;" />

- Use meaningful alt text for accessibility.

<!--
```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
-->
