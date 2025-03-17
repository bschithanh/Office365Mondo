# Kích hoạt Office 365 Mondo
## DOWNLOAD VÀ CÀI ĐẶT OFFICE 365 MONDO
## KÍCH HOẠT OFFICE 365 MONDO 180 ngày.
- Bạn run **cmd** bằng quyền **Run as Administrator** sau đó copy đoạn code sau đây dán vào là xong!

  ```php
  @echo off
  title  Activate Microsoft Office Prolus 2016 for FREE - https://github.com/BsChiThanh 
  cls
  color F4
  mode con cols=98 lines=30
  if exist "%ProgramFiles%\Microsoft Office\Office16\ospp.vbs" cd /d "%ProgramFiles%\Microsoft Office\Office16"
  if exist "%ProgramFiles(x86)%\Microsoft Office\Office16\ospp.vbs" cd /d "%ProgramFiles(x86)%\Microsoft Office\Office16"
  for /f %x in ('dir /b ..\root\Licenses16\MondoVL_MAK-ul-phn.xrm-ms') do cscript ospp.vbs /inslic:"..\root\Licenses16\%x"
  for /f %x in ('dir /b ..\root\Licenses16\MondoVL_MAK-ul-oob.xrm-ms') do cscript ospp.vbs /inslic:"..\root\Licenses16\%x"
  for /f %x in ('dir /b ..\root\Licenses16\MondoVL_MAK-ul-oob.xrm-ms') do cscript ospp.vbs /inslic:"..\root\Licenses16\%x"
  for /f %x in ('dir /b ..\root\Licenses16\MondoVL_MAK-pl.xrm-ms') do cscript ospp.vbs /inslic:"..\root\Licenses16\%x"
  for /f %x in ('dir /b ..\root\Licenses16\MondoVL_KMS_Client-ul.xrm-ms') do cscript ospp.vbs /inslic:"..\root\Licenses16\%x"
  for /f %x in ('dir /b ..\root\Licenses16\MondoVL_KMS_Client-ul-oob.xrm-ms') do cscript ospp.vbs /inslic:"..\root\Licenses16\%x"
  for /f %x in ('dir /b ..\root\Licenses16\MondoVL_KMS_Client-ppd.xrm-ms') do cscript ospp.vbs /inslic:"..\root\Licenses16\%x"
  cscript //nologo ospp.vbs /setprt:1688
  cscript //nologo ospp.vbs /sethst:192.168.2.81.2.7.0
  cscript //nologo ospp.vbs /inpkey:HFTND-W9MK4-8B7MJ-B6C4G-XQBR2
  :end
  :notsupported
  :halt
  pause >nul
  ```

... đang cập nhật
