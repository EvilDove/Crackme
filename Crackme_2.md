Crackme_2 

![c2 1](https://github.com/user-attachments/assets/11a408de-e724-4560-8559-375a3a4ee225)

I found the code that triggers the message, and a useful command is `CreateFileA`, a Windows API function. This function either creates a file or searches for an existing file by name, returning a value to indicate whether the file exists. In this case, it checks for the presence of a file named `keyfile.txt`.

Create 'keyfile.txt' with blank

![c2 2](https://github.com/user-attachments/assets/41bca937-514d-4501-b7f9-832522c2de2b)

And it's show us blank

![c2 3](https://github.com/user-attachments/assets/e274d375-c2d4-445d-9f78-2b8cf47f6ba3)

So i analysis the program by xAnalyzer that I found the program read content of file and take that as the resgister name.
![c2 4](https://github.com/user-attachments/assets/a423aeaf-ab8a-4b3d-8123-22f71af8b7ea)

Then i add my name in the file 'keyfile.txt'

![c2 5](https://github.com/user-attachments/assets/4149f390-2c86-4c1d-a66b-1072be7119b3)
![c2 6](https://github.com/user-attachments/assets/0b33f62b-6358-4de8-b599-b30649d60310)
