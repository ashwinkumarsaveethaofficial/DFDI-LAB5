# EX5: Reviewing-Unallocated-Space-Extracting-Data-with-Tools-Digital-Investigation-Processes
## AIM:
To review unallocated space in a disk image, extract data using forensic tools, and understand the digital investigation process.

## DESIGN STEPS:
```
Name : Praveen V
RegNo: 212222040121
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
![Screenshot 2025-05-02 213937](https://github.com/user-attachments/assets/57cecdb4-cbad-4637-9be1-ce7c6a9b3611)
![Screenshot 2025-05-02 214023](https://github.com/user-attachments/assets/d0f78e62-3452-4436-81e0-9fd0a7fc47c3)
![Screenshot 2025-05-02 214053](https://github.com/user-attachments/assets/d7399b3f-71b2-47d8-87fb-b1ff8d32eb78)
![Screenshot 2025-05-02 214119](https://github.com/user-attachments/assets/52544091-5d64-4761-a372-a99cd6100ace)
![Screenshot 2025-05-02 214205](https://github.com/user-attachments/assets/a12694e1-b46d-4091-a3e9-85a56af0928d)
![Screenshot 2025-05-02 214149](https://github.com/user-attachments/assets/c9f258d0-196d-4b03-9574-d7d80faad081)



## RESULT:
The unallocated space was successfully analyzed, data was extracted, and the digital investigation process was followed effectively.
