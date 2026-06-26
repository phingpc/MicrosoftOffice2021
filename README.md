## MS-Office-2021
 
To install MS Office Follow these steps:
- Step 1: Download Office 2021 file from this repo.
- Step 2: Extract the file.
- Step 3: Open folder.
- Step 4: Click to open Install-x64.bat with Administrator.


### For Activation
- *Run cmd as Administrator*
- Copy all below commands, **right click to paste into cmd window** at once then hit Enter.

```
if exist "C:\Program Files\Microsoft Office\root\Office16\OSPP.VBS" cd /d "C:\Program Files\Microsoft Office\root\Office16"
if exist "C:\Program Files (x86)\Microsoft Office\root\Office16\OSPP.VBS" cd /d "C:\Program Files (x86)\Microsoft Office\root\Office16"
for /f %x in ('dir /b ..\Licenses16\ProPlus2021VL_KMS*.xrm-ms') do cscript OSPP.VBS /inslic:"..\Licenses16\%x"
cscript OSPP.VBS /inpkey:FXYTK-NJJ8C-GB6DW-3DYQT-6F7TH
cscript OSPP.VBS /sethst:kms.msgang.com
cscript OSPP.VBS /act
pause
```
