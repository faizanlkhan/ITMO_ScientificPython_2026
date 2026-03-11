# HW1 - Learning Git Branching Progress 👾​



This folder contains Base64 encoded screenshots of completed levels from the Main and Remote sections of Learn Git Branching with instructions to convert the txt file back to png. 



## How to convert text back to image



### Windows (PowerShell)



```powershell

certutil -decode main.txt main.png
certutil -decode remote.txt remote.png

```



### Linux / Mac

```bash

base64 -d main.txt > main.png
base64 -d remote.txt > remote.png

```



