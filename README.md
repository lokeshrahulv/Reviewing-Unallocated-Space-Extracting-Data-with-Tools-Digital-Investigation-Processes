# Reviewing-Unallocated-Space-Extracting-Data-with-Tools-Digital-Investigation-Processes
## AIM:
To review unallocated space in a disk image, extract data using forensic tools, and understand the digital investigation process.

## DESIGN STEPS:
### Step 1:
Use tools like Autopsy or Sleuth Kit (blkls, icat) to identify and analyze unallocated space.

### Step 2:
Extract data from unallocated space and examine for hidden or deleted content.

### Step 3:
Document and interpret findings as part of the digital investigation process.

## PROGRAM:
Data Extraction and Investigation Tool Usage
```
lsblk
```
```
sudo dd if=/dev/sda of=/home/kali/disk.img bs=512
```
```
mmls ~/disk.img
```
```
sudo ls -lh disk.img
```
```
strings disk.img | less
```
## OUTPUT:
![image](https://github.com/user-attachments/assets/c60ebac1-fc97-4ae8-bceb-a5d4cc7a3493)
![WhatsApp Image 2025-05-22 at 19 06 07_4dd1bb18](https://github.com/user-attachments/assets/eb4d6223-09a0-43b6-8e8c-7efd4e4c911a)
![WhatsApp Image 2025-05-22 at 19 06 06_f5807b7e](https://github.com/user-attachments/assets/35f6778b-8228-4124-8397-4e73820a9acc)
![WhatsApp Image 2025-05-22 at 19 06 06_d61f3cdb](https://github.com/user-attachments/assets/469ebdc5-f803-4ea0-9dd8-044a21081409)
![WhatsApp Image 2025-05-22 at 19 06 07_764c37a9](https://github.com/user-attachments/assets/76db16a2-276a-4d37-9175-92f362024844)

## RESULT:
The unallocated space was successfully analyzed, data was extracted, and the digital investigation process was followed effectively.

