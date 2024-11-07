![image](https://github.com/user-attachments/assets/47482dee-a8b3-4732-a864-6c29e4593742)

- ```unxz [filename]``` to extract file contents of .xz file
- download the tool volatility https://github.com/volatilityfoundation/volatility3

![image](https://github.com/user-attachments/assets/153bcfd4-ec72-4c93-8d0c-d5a48c514bf1)
- ![image](https://github.com/user-attachments/assets/d0288ba2-e882-4320-99e3-2881a4ee176d)

Answer: Windows

![image](https://github.com/user-attachments/assets/11475505-cfa4-423f-8eb8-10214ddab6e2)
- ```./vol.py -f ./memdump.mem windows.envars.Envars```
- ![image](https://github.com/user-attachments/assets/44b8d9fc-d536-4dd8-ac11-85124d706716)

Answer: DESKTOP-OT97GG3

![image](https://github.com/user-attachments/assets/f161daca-57ff-4a53-a144-8fe827408e9f)
- ![image](https://github.com/user-attachments/assets/636ee8fc-7905-41ff-b403-6ba2de2614f6)
  
Answer: liber8hacker

![image](https://github.com/user-attachments/assets/5a9492b9-a442-48bf-8104-416f2e434011)
- ```./vol.py -f ./memdump.mem windows.filescan.FileScan```
- extract using ```./vol.py -f ./memdump.mem -o ./dump windows.dumpfiles.DumpFiles --virtaddr [file address]```
- ```./vol.py -f ./memdump.mem -o ./dump windows.dumpfiles.DumpFiles --virtaddr 0xe0003d624b90``` used the memory address not the file path!!
- ![image](https://github.com/user-attachments/assets/3b400b1c-6b55-4d4c-b519-5a161a58255f)

Answer: \Users\liber8hacker\Desktop\black_book.db

![image](https://github.com/user-attachments/assets/d4db63c7-be62-48e7-a571-a261108ac8f3)
- If get this error, create the dump directory: ![image](https://github.com/user-attachments/assets/bcc99e53-c570-4278-ae4c-b8deb255b2ef)
- ![image](https://github.com/user-attachments/assets/a6d67e5e-ba8f-4147-957f-acaf9e30e7a1)
- ![image](https://github.com/user-attachments/assets/90f3e5f3-d406-4d0c-8804-0feb0b6eb261)
- Combine the .dat and .vacb files together: ![image](https://github.com/user-attachments/assets/a110e8db-ed83-432b-bbc0-d2296d986ee5)
- Open in SQLite:
- ![image](https://github.com/user-attachments/assets/f4b94332-bec6-44e0-861e-0bbf6a1329dd)
- ![image](https://github.com/user-attachments/assets/07951bdc-dcab-4b74-9766-68442bf21982)

Answer: gloria hampton

![image](https://github.com/user-attachments/assets/ad81f781-092c-4f20-bfae-c612de5cd3fc)
- ```./vol.py -f ./memdump.mem windows.hashdump.Hashdump```
- ![image](https://github.com/user-attachments/assets/53658775-ddbf-493e-9a7d-e44bfe3068fe)
- ```hashcat -m 1000 -a 0 hash.txt /usr/share/wordlists/rockyou.txt```
- ![image](https://github.com/user-attachments/assets/b627aaeb-29c3-4fc7-874e-c705e25bf51b)

Answer: avatar2
