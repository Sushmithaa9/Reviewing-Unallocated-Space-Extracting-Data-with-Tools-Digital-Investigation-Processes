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
```bash
lsblk
```

```bash
sudo dd if=/dev/sda of=/home/kali/a.png bs=512
```

```bash
mmls ~/a.png  (sleuth-kit)
sudo fdisk -l ~/a.png (GNU)

```
```bash
sudo ls -lh a.png
```
```bash
strings a.png | less

```

## OUTPUT:
![Screenshot 2025-04-24 055444](https://github.com/user-attachments/assets/1426b540-eb76-46b2-8b86-fe767ded8d28)

![image](https://github.com/user-attachments/assets/1653fc5c-cc6f-4f08-8378-d47fb395385d)

![image](https://github.com/user-attachments/assets/af614f34-4324-413f-8beb-08bc05642345)

![image](https://github.com/user-attachments/assets/b4c2f27f-23c0-4fe7-8cc7-65fd2ff0276c)


![image](https://github.com/user-attachments/assets/8faeb55f-bf38-43da-aa20-1c7457289ef9)





## RESULT:
The unallocated space was successfully analyzed, data was extracted, and the digital investigation process was followed effectively.

