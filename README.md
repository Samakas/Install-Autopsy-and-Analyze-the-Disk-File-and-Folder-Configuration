# EXP 3 : INSTALL AUTOPSY AND ANALYSIS THE DISK, FILE AND FOLDER CONFIGURATION

### Name: Samakash R S
### Reg NO: 212223230182

## AIM:
To install Autopsy software on windows operating system and analyse the file and folder configuration.

## EQUIPMENT REQUIRED:
● Hardware: Personal Computer (PC)

## DESIGN STEPS:
### Step 1:
Install Autopsy using the terminal with the command:

### Step 2:
Launch Autopsy from the terminal or application menu and create a new case.

### Step 3:
Add a disk image or file to the case and analyze the contents such as deleted files, metadata, and folder structure.

## INSTALLATION PROCEDURE:
### Step1:Download Autopsy
• Visit Autopsy Official Website and download the latest version.

• Double-click the downloaded file and follow the on-screen instructions.
![Screenshot 2025-04-22 112556](https://github.com/user-attachments/assets/30fc778c-4685-4d3d-83a8-82f836dd2d55)


## **Implementation steps:**

### **1. Copy Files to the Virtual Disk**  
- Open **File Explorer** → Go to the new drive (`D:`), where the folder created in the New Virtual Disk
- Create a new folder or use the entire disk and then copy **images or files** into it.  

### **2. Delete the Files**  
- Select any one or two images → Press **Delete**.  
- Empty the **Recycle Bin** to permanently delete them.  

### **3. Recover Deleted Files Using Autopsy**  
### **Open Autopsy & Create a New Case** 

- Launch **Autopsy** and **Run as a administrator**  
- Click **Create New Case**.  
![Screenshot 2025-04-22 112903](https://github.com/user-attachments/assets/4db8a848-91f5-4b97-856d-8226df41b6c0)


- Enter a **Case Name** (e.g., `Autopsy-1`).  
- Choose a **Case Folder** location.  
- Click **Next** → Click **Finish**.  

![Screenshot 2025-04-22 112917](https://github.com/user-attachments/assets/c3a8975e-4bd3-4783-80d5-e482c3ab5e11)


### **Add the Virtual Disk as an Evidence Source**  
- Click **Add Data Source**  → **Select Host**
![Screenshot 2025-04-22 112946](https://github.com/user-attachments/assets/c74f240c-002a-4754-bd6f-7ce5e381282e)


- Select **Local Disk** → **next** 

![Screenshot 2025-04-22 112953](https://github.com/user-attachments/assets/763dd65b-07ab-47fa-8fa8-b091e86aca00)



- Select Disk → **Choose the VHD drive (`New Volume(E:`)**

![Screenshot (1)](https://github.com/user-attachments/assets/7d8e838f-0d9f-4ff5-9c40-49871aba673d)



- Click **Next** → Keep default settings → Click **Finish**.  
- Wait for Autopsy to process the disk.  

### **Recover Deleted Files**  


- Click **Deleted Files** → Find your deleted images.  
- Right-click an image → Click **Extract File**.  


![Screenshot (4)](https://github.com/user-attachments/assets/c86fd234-0f50-44d8-9a42-5bc324b1c277)



## Result:
Successfully extracted the deleted files from unallocated space using the Autospy tool.
