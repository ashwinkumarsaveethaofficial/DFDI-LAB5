# EX5: Reviewing-Unallocated-Space-Extracting-Data-with-Tools-Digital-Investigation-Processes
## AIM:
To review unallocated space in a disk image, extract data using forensic tools, and understand the digital investigation process.

## DESIGN STEPS:
```
Name : Ashwinkumar S
RegNo: 212222040020
```
### Step 1:
Use tools like Autopsy or Sleuth Kit (blkls, icat) to identify and analyze unallocated space.

### Step 2:
Extract data from unallocated space and examine for hidden or deleted content.

### Step 3:
Document and interpret findings as part of the digital investigation process.

## PROGRAM:
Data Extraction and Investigation Tool Usage
```bash
lsblk
```

```bash
sudo dd if=/dev/sda of=/home/kali/disk.img bs=512
```

```bash
mmls ~/disk.img
```
```bash
sudo ls -lh disk.img
```
```bash
strings disk.img | less

```

## OUTPUT:
![Screenshot 2025-05-05 134612](https://github.com/user-attachments/assets/02a02cce-4434-4a58-9f01-2406976c64f1)

![Screenshot 2025-05-05 135028](https://github.com/user-attachments/assets/428f8f17-38dc-4113-9f80-983f68725e26)

![Screenshot 2025-05-05 135043](https://github.com/user-attachments/assets/e8ccef85-6813-4e2e-a558-1d5d1462a08d)

![Screenshot 2025-05-05 135055](https://github.com/user-attachments/assets/71677b97-0b3c-4461-b42c-54da0a161ce0)

![Screenshot 2025-05-05 135107](https://github.com/user-attachments/assets/2596aac4-dee2-41b8-81a5-8a568dbd3ee7)

![Screenshot 2025-05-05 135129](https://github.com/user-attachments/assets/a0cb2fb1-36dc-400a-aaca-72b358d26d56)




## RESULT:
The unallocated space was successfully analyzed, data was extracted, and the digital investigation process was followed effectively.
