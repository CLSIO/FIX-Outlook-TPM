# FIX-Outlook-TPM-Error
Fixes Errors with TPM and Outlook / Azure. When moving-imaging

Use this powershell command as administrator if you have the following errors

"Keyset does not exist Keyset does not exist"
"Something went wrong, TPM error"
"TPM is 'malfunctioned'"
Error Code: 80090030
"The device that is required by this cryptographic provider is not ready for use. The device that is required by this cyprographic provider is not ready for use"

Alternate solution for some was to login as another admin user and rename the following folder:
C:\users\$dir\AppData\Local\Packages\Microsoft.AAD.BrokerPlugin_cw5n1h2txyewy
