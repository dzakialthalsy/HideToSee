# HideToSee
atbash encrypted chiper

## Description 
How about some hide and seek heh?
Look at this image here.

![atbash](https://github.com/user-attachments/assets/70000b9e-e157-41f9-9b90-9ca5c9c646aa)

## Solution
Get the file:
wget https://artifacts.picoctf.net/c/235/atbash.jpg

if we see the code inside of the file with cat command, we will get nothing.

So, let's see is there any hidden data inside of it using steghide.


we're gonna extract it with command:
steghide extract -sf atbash.jpg

after that, we're gonna get a extracted file named encrypted.txt

<img width="447" alt="Screenshot 2025-01-28 135529" src="https://github.com/user-attachments/assets/5f993141-f5bb-4972-b395-37eb3adb6188" />


There's an encrypted atbash chiper inside of the file, let's decode it using cyberchef.
finally, you'll get the flag.
