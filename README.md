#Introduction

This is mirror source code released by securityarchitects.com, the one that provide ASLR for Windows NT5 (beside Wehntrust). This consist driver only (agent/client not included) but will read .policy files like the one provided by Ozone installer.  

#Issues (in my experience)

- As with XP SP3 with recent updates, Ozone will nag you for some normal explorer.exe operation
- Ozone use process name only to identify, thus one could impersonate easily by just renaming executable