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
![Screenshot 2025-05-05 135028](https://github.com/user-attachments/assets/07b28245-c899-4ab9-9080-9c6c224f9a43)


![Screenshot 2025-05-05 135043](https://github.com/user-attachments/assets/844e3167-5e45-471b-abc3-97f141f0e875)


![Screenshot 2025-05-05 135055](https://github.com/user-attachments/assets/d3cca5dd-49a0-476e-b868-1d8cc822d32e)


![Screenshot 2025-05-05 135107](https://github.com/user-attachments/assets/2d8de7fa-0223-4d7b-a63c-69d16d79b9e8)


![Screenshot 2025-05-05 135119](https://github.com/user-attachments/assets/e5e865af-c222-46b6-b263-8a541aa80e01)


![Screenshot 2025-05-05 135129](https://github.com/user-attachments/assets/7e89079b-1a1f-45ff-bd3d-52fe8e9bc32c)





## RESULT:
The unallocated space was successfully analyzed, data was extracted, and the digital investigation process was followed effectively.
