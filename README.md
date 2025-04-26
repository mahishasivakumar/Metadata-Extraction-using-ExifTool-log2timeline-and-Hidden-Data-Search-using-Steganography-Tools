# EX 6: Metadata Extraction using ExifTool log2timeline and Hidden Data Search using Steganography Tools
## AIM:
To extract metadata, perform timeline analysis, and search for hidden data using forensic tools like ExifTool, log2timeline, and steganography detection tools.

```
Register Number: 212222040095
Name: Mahisha S
```

## DESIGN STEPS:
### Step 1:
Use exiftool to extract metadata from files such as images, documents, and videos.

### Step 2:
Use log2timeline and plaso to create and analyze event timelines from system logs and file metadata.

### Step 3:
Apply steganography detection tools like steghide, zsteg, or binwalk to uncover hidden data in media files.

## ANALYSING TOOLS
## A.Metadata Extraction using ExifTool
#### Step 1:Install ExifTool (if not already installed):
```
sudo apt update
sudo apt install libimage-exiftool-perl
```
#### Step 2: Navigate to the directory of the file:

![Screenshot 2025-04-26 112642](https://github.com/user-attachments/assets/a237ec4e-5fdb-421f-855a-c882da64d811)

#### Step 3: Run ExifTool on a file (e.g., praveen.jpeg):

![Screenshot 2025-04-26 112844](https://github.com/user-attachments/assets/9171fbc3-37e9-4148-a911-3edad5b05808)

#### Step 4: Export metadata to a text file (optional):

![Screenshot 2025-04-26 113054](https://github.com/user-attachments/assets/ead3f681-d9a8-41b2-86d6-a546f7569b97)

#### Step 5: Look for key details:
• Creation Date

• Modification Date

• Encoding Process

• Permissions




## B.Hidden Data Search using Steganography Tools

### 1. Using steghide
#### Step 1: Install steghide:
```
sudo apt install steghide
```
#### Step 2: Extract hidden data:
![Screenshot 2025-04-26 113258](https://github.com/user-attachments/assets/3d114ef4-9973-4dde-9d07-af02d1ecfa4e)




### 2.Using zsteg(For PNG files)
#### Step 1: Install Ruby + zsteg:
```
sudo apt install ruby
sudo gem install zsteg
```

#### Step 2: Run zsteg on a PNG:
![Screenshot 2025-04-26 114936](https://github.com/user-attachments/assets/a97b8784-02c5-44c3-825c-74772137973f)


### 4.Using strings (for quick hidden text):

#### Step1:  Create a text file to hide
![Screenshot 2025-04-26 115258](https://github.com/user-attachments/assets/224bd5ce-54ef-4229-af5a-57ceceb0f670)


#### Step2: Use cat to append the text file to a JPEG\
![Screenshot 2025-04-26 115635](https://github.com/user-attachments/assets/a651d948-d51a-4232-ad40-b8fd93398489)


#### Step3: Use strings to find the hidden message
![Screenshot 2025-04-26 115737](https://github.com/user-attachments/assets/e8e42c66-d43e-4c48-8347-d6d8a9054b0c)











## RESULT:
Metadata was successfully extracted, timeline analysis was completed, and hidden data was identified using steganography tools.

