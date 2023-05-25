# TBD-KIOWARE-001

## Description
KioWare for Windows through version 8.33 has an incomplete blacklist filter for blocked dialog boxes on Windows 10. This allows one to open a file dialog box via the javascript function "showDirectoryPicker()" in the KioWare browser. The resulting file dialog can then be used to open an unprivileged command prompt.

## Additional Information
This issue was discovered during KalmarCTF-2023 during the challenge "XScapy" where the goal was to discover CVE-2022-44875.

## Vulnerability Type
Sandbox escape / Incorrect Access Controls

## Vendor of Product
KioWare

## Affected Product Code Base
KioWare for Windows - through version 8.33

## Affected Component
KioWare Kiosk Browser

## Attack Type
Local

## Impact Code Execution
true

## Impact Escalation of Privileges
true

## Attack Vectors
Javascript execution in kiosk web browser leading to execution of unprivileged system commands

## Discoverer
Bitk
