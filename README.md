# Surveying-and-Preserving-the-Digital-Crime-Scene
### Name: Mohan S
### Reg NO: 212223240094
## Aim:
<p>Data recovery from unallocated space, using forensic tools(Autospy) to extract and analyze data.</p>

## Implementation Steps:
### 1.Copy Files to the Virtual Disk
<ul>Open File Explorer → Go to the new drive (C: or D:), where the folder created in the New Virtual Disk</ul>
<ul>Create a new folder (Autospy) and copy images or files into it.</ul>

### 2.Delete the Files
<ul>Select any one or two images → Press Delete.</ul>
<ul>Empty the Recycle Bin to permanently delete them.</ul>

### 3.Recover Deleted Files Using Autopsy
### Open Autopsy & Create a New Case
<ul>Launch Autopsy and Run as a administrator</ul>
<ul>Click Create New Case.</ul>

![IMG-06](https://github.com/user-attachments/assets/d8006cf1-1e96-41ca-b6a2-2e8e9d2fa191)


<ul>Enter a Case Name (e.g., Autopsy1).</ul>
<ul>Choose a Case Folder location.</ul>
<ul>Click Next → Click Finish.</ul>

![IMG-03](https://github.com/user-attachments/assets/765ea471-fe38-4c02-9376-59b1c3ba260f)



### Add the Virtual Disk as an Evidence Source
<ul>Click Add Data Source → Select Host</ul>

![IMG-08](https://github.com/user-attachments/assets/f4e6e2b9-c854-4900-bc51-a200e4ca48e4)



<ul>Select Local Disk → next</ul>

![IMG-01](https://github.com/user-attachments/assets/77df1147-5147-40ab-b08b-c47e2cd49e9b)


<ul>Select Disk → Choose the VHD drive (Drive1)</ul>
![IMG-05](https://github.com/user-attachments/assets/3ca64daf-aa71-4fc3-bfc6-f5156dc6a318)



<ul>Click Next → Keep default settings → Click Finish.</ul>
<ul>Wait for Autopsy to process the disk.</ul>

### Recover Deleted Files
<ul>Go to File Views (left panel).</ul>

![IMG-07](https://github.com/user-attachments/assets/e7e92867-e880-4a44-be5f-48ad779e987e)
![IMG-04](https://github.com/user-attachments/assets/f0240b6a-4853-4b7f-969b-2d005d9d96d6)



<ul>Click Deleted Files → Find your deleted images.</ul>
<ul>Right-click an image → Click Extract File.</ul>

![IMG-02](https://github.com/user-attachments/assets/97a4b413-6f0c-474b-9629-c2d2fb0c1490)


## Output:
### Folder before deleting the files

<ul>Folder after deleting the files</ul>

![IMG-09](https://github.com/user-attachments/assets/d0379357-53b1-49bd-9da3-bff9c6ddac99)


<ul>Folder after deleting the files</ul>

![IMG-10](https://github.com/user-attachments/assets/d0970785-dab5-430b-9ea9-390c8d7d4365)



<ul>Folder after extracting the deleted images using autopsy</ul>

![IMG-11](https://github.com/user-attachments/assets/eadd9817-b6f9-4e45-bb61-18175fc9daba)



## Result:
<p>Successfully extracted the deleted files from unallocated space using the Autospy tool.</p>
