---
created: 2024-10-23T11:34
updated: 2024-10-24T17:02
---
__Get everything in place so that Lukas can enable us
- [x] Apply Terraform to create Database Stream
- [x] Apply Terraform of Data Lake Sync Service (enable-flag false)
- [x] Deploy Code of Data Lake Sync Service (review?)

__Data Platform Team
- [x] Wait for Data Platform Team to add the newly created role to their allow-list

__Deploy code__
- [ ] Deploy Code Changes of API Lambda (removes sending to datalake)
- [ ] Apply Terraform of Data Lake Sync Service (enable-flag true) **in parallel** to keep the gap as small as possible
- [ ] __Immediately__: Quick test, if 
- [ ] __Then__: Apply removal of permissions for old Lambda


__Further Steps
- [ ] Set up PagerDuty
- [ ] Terraform Documentation?

# Nachricht an Phillip

Hallo Phillip,
es hat sich alles etwas verzögert, weil noch ein Frontend-Thema dazwischen gekommen ist.
Ich bin jetzt soweit, dass ich den neuen Service auf Production deployed habe.

Das hier ist meine Checkliste für das Prod-Deployment:

Siehst Du noch weitere Schritte, die notwendig sind, bevor/nachdem ich den data lake sync umgestellt habe?