Crackme_1 

![c1 1](https://github.com/user-attachments/assets/66bfcc34-037a-4ec5-9806-67822d5d5cc2)

First of all we need to run to test the program. Find the serial key
![c1 2](https://github.com/user-attachments/assets/56686f07-3381-4428-81b4-255c0fcf0301)

The serial key is cr4ckingL3ssons
![c1 3](https://github.com/user-attachments/assets/e520b939-c2f7-462e-ade0-b36aa1ade0b0)

First is the `jump` remove it and change the value at the `eax` register from `1` to `0` because ifthe value in `eax` prog I just change will corrupted the instructio will be overwrite to another instruction cause is nnot enough byte for that instruction here.
![c1 4](https://github.com/user-attachments/assets/dacc640a-01b8-4e1b-b103-239c9fd55a1e)
![c1 5](https://github.com/user-attachments/assets/86d3617f-98cd-49d5-9afc-2d63347858d4)

Delete the `jump` command to get space for the `mov` command. The `jump` take 4 bytes and the `mov al, 0` take 3 bytes so that is the reason.

Then patch the file and we got the result.
