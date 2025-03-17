# Kích hoạt Office 365 Mondo
## DOWNLOAD VÀ CÀI ĐẶT OFFICE 365 MONDO
- Cách 1:
  - Download Office Tool Plus từ [trang chủ](https://otp.landian.vip/en-us/download.html) hoặc bấm vào đây để download [32bit](https://objects.githubusercontent.com/github-production-release-asset-2e65be/156369540/1e88a217-e1d9-4d5c-a733-c092f3b35dd1?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=releaseassetproduction%2F20250317%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20250317T033702Z&X-Amz-Expires=300&X-Amz-Signature=c8c2692529293814399538092bc04d9917d9014d3cad9115b3fdbe28a7e641cd&X-Amz-SignedHeaders=host&response-content-disposition=attachment%3B%20filename%3DOffice_Tool_with_runtime_v10.21.25.0_x86.zip&response-content-type=application%2Foctet-stream); [64bit](https://objects.githubusercontent.com/github-production-release-asset-2e65be/156369540/0f16223c-7832-4c8b-8aaf-fdc98420dace?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=releaseassetproduction%2F20250317%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20250317T033506Z&X-Amz-Expires=300&X-Amz-Signature=277d53d7d2b4e6ddf252c979586150c6f855577d99d32d503e202794c41719c7&X-Amz-SignedHeaders=host&response-content-disposition=attachment%3B%20filename%3DOffice_Tool_with_runtime_v10.21.25.0_x64.zip&response-content-type=application%2Foctet-stream) xong, run Office Tool Plus
  - ![image](https://github.com/user-attachments/assets/f1fb9c85-3ade-45ff-8813-2ef7ef67f5c1)
  - Vô **triển khai** và **Add products**.
  - ![image](https://github.com/user-attachments/assets/831b541a-d7ca-47a8-be56-264bf366ed4b)
  - ![image](https://github.com/user-attachments/assets/d8c5be96-79e7-4964-a74d-8312fe9c6819)
  - Bạn cũng có thể tùy chọn cài đặt.
  - Bấm **Bắt đầu triển khai** là sẽ bắt đầu quá trình cài đặt online.
  - ![image](https://github.com/user-attachments/assets/736f938d-fc0c-4137-8e93-bac5f38ffe46)
  - Chờ tí là xong!
- Cách 2:
  - Bạn có thể download và cài đặt một **Office 16 prolus** bất kì, sau đó **Active** như bên dưới là được.
  - **Office 16** tức: Office 2016, 2019, 2021, 2024, 365.

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
