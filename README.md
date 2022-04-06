# Bulk_User_and_Role_Creation

Simple script to bulk create Prisma SDWAN Controller Portal Operators

Requirements
Active CloudGenix Account
Python >= 2.7 or >=3.6
Python modules:
cloudgenix >=4.4.5b2 - https://github.com/CloudGenix/sdk-python
progressbar2 >=3.34.3 - https://github.com/WoLpH/python-progressbar
License
MIT

Usage Example:
bash#python Bulk-User-Role-Creation.py bulk_list_sample.csv

CSV file preparation:
Please input and validate tenant base roles or the custom defined roles on the portal already.

Tenant base roles are:
-tenant_iam_admin,
-tenant_network_admin,
-tenant_security_admin,
-tenant_viewonly,
-tenant_super

Password Requirements: At least 2 uppercase letters and 2 lowercase letters. Maximum 24 characters. Minimum 12 characters. New password should not match any of the last 3 recently used passwords.

Version
Version	Changes
1.0.0	Initial Release.
