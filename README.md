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
 lsblk
 sudo dd if=/dev/sda of=/home/kali/disk.img bs=512
 mmls ~/disk.img
 sudo ls -lh disk.img
 strings disk.img | less


## OUTPUT:
![image](https://github.com/user-attachments/assets/9b8ae567-d82d-4adc-b729-ffd2e72fc06f)

![image](https://github.com/user-attachments/assets/932429dc-7fd7-4ede-9bac-c48add37ce26)


![image](https://github.com/user-attachments/assets/dce03384-7499-44d9-a2ff-fffe7f35188b)

![image](https://github.com/user-attachments/assets/ee3e5317-f445-4aac-b01a-d08aec5ad6a1)


![image](https://github.com/user-attachments/assets/7391677c-517b-4312-9988-35ba844fe1ea)


## RESULT:
The unallocated space was successfully analyzed, data was extracted, and the digital investigation process was followed effectively.

