# Surveying and Preserving the Digital Crime Scene

## **Aim:**
Data recovery from unallocated space, using forensic tools(Autospy) to extract and analyze data.

## **Implementation steps:**

### **1. Copy Files to the Virtual Disk**  
- Open **File Explorer** → Go to the new drive (`C: or D:`), where the folder created in the New Virtual Disk
- Create a new folder (`Autospy`) and copy **images or files** into it.  

### **2. Delete the Files**  
- Select any one or two images → Press **Delete**.  
- Empty the **Recycle Bin** to permanently delete them.  

### **3. Recover Deleted Files Using Autopsy**  
### **Open Autopsy & Create a New Case** 

- Launch **Autopsy** and **Run as a administrator**  
- Click **Create New Case**.  

![image](https://github.com/user-attachments/assets/01d85daf-220b-49dc-8829-aab341626297)

- Enter a **Case Name** (e.g., `Autopsy1`).  
- Choose a **Case Folder** location.  
- Click **Next** → Click **Finish**.  

![image](https://github.com/user-attachments/assets/b99ac5f4-5685-4e0b-ba75-8a6bb681e5fc)

### **Add the Virtual Disk as an Evidence Source**  
- Click **Add Data Source**  → **Select Host**

![image](https://github.com/user-attachments/assets/f7064cfb-8d84-4406-b8c5-355e79a6cb42)

- Select **Local Disk** → **next** 

![image](https://github.com/user-attachments/assets/52eb6964-30ff-4a63-bfae-bb781f4e5a4a)

- Select Disk → **Choose the VHD drive (`Drive1`)**

![image](https://github.com/user-attachments/assets/7f141071-6064-4e41-94a9-18fa0ac6ad1a)

- Click **Next** → Keep default settings → Click **Finish**.  
- Wait for Autopsy to process the disk.  

### **Recover Deleted Files**  
- Go to **File Views** (left panel).  

![image](https://github.com/user-attachments/assets/1a436868-e9d0-4cbc-a4a4-de98eb49a565)

![image](https://github.com/user-attachments/assets/b5cbe280-cb3d-4680-9ca4-1a8dfb5effba)

- Click **Deleted Files** → Find your deleted images.  
- Right-click an image → Click **Extract File**.  

![image](https://github.com/user-attachments/assets/65bc8c57-e471-47b1-bf13-a3aecf20cc91)

- Select a folder to see the recovered files (e.g., `C:\forensic`).  
- Image is recovered successfully.


## Output :
### Folder before deleting the files

![image](https://github.com/user-attachments/assets/4a24368d-2d1c-4161-862e-4a7ae74a86f1)

### Folder after deleting the files

![image](https://github.com/user-attachments/assets/d8cc536f-b712-4015-ae94-fe09be25aec5)

### Folder after extracting the deleted images using autopsy

![image](https://github.com/user-attachments/assets/6fdb5725-b8a7-4d92-9f2a-a38d3fdaecdf)

## Result:
Successfully extracted the deleted files from unallocated space using the Autospy tool.
