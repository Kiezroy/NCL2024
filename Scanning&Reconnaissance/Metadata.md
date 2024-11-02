![image](https://github.com/user-attachments/assets/ca459357-a273-4b25-becc-c7d0a6531e94)

- Navigate to the web server of ```metadata.services.cityinthe.cloud:1338```
- The returned text may indicate a potential path to follow
![image](https://github.com/user-attachments/assets/1246033e-a230-45a2-a2f5-21d409d7c18a)

- Following the ```latest``` path, we get more paths to follow
![image](https://github.com/user-attachments/assets/90055453-5c0a-46d7-9461-fdf84a5929dc)

- From there we continue until we get to this path: ```http://metadata.services.cityinthe.cloud:1338/latest/meta-data/placement/availability-zone```
![image](https://github.com/user-attachments/assets/1654eb9a-c73b-42c4-b6d6-23d3af153d5e)

![image](https://github.com/user-attachments/assets/0214f469-c53f-405e-abe0-b8b8dd23b034)
Answer: us-west-2a

![image](https://github.com/user-attachments/assets/50d7f99a-5623-4a28-9bd6-3d39b025c121)

- Navigate to this path for the answer: ```http://metadata.services.cityinthe.cloud:1338/latest/meta-data/iam/security-credentials```
![image](https://github.com/user-attachments/assets/18f4d31e-5862-4120-ab63-70643b7f1c30)
Answer: liber8-role

![image](https://github.com/user-attachments/assets/f767177a-597d-479a-8bb5-5965f492b94d)
- Navigate to ```http://metadata.services.cityinthe.cloud:1338/latest/meta-data/instance-type```
![image](https://github.com/user-attachments/assets/102d99c8-0819-48b1-96f2-d686cb750c86)
Answer: c6g.16xlarge

![image](https://github.com/user-attachments/assets/1f637866-5cea-4fe9-894e-c9f25935ebfe)
- Navigate to ```http://metadata.services.cityinthe.cloud:1338/latest/meta-data/ami-id```
- AMI ID is an Amazaon Machine Image
![image](https://github.com/user-attachments/assets/a5f88148-7b44-4405-ad98-4b68851acec8)
![image](https://github.com/user-attachments/assets/5f12d70b-712a-464a-9de3-aaaa5c3f0c2f)
Answer: Xenial Xerus 16.04 LTS

![image](https://github.com/user-attachments/assets/0ecb6b8e-0bde-4465-bd80-1fdc75be3e10)
- Enumerate all possible endpoints
- Find ```network/interfaces/macs``` endpoint that strangely has a ```/``` meaning there is a path within that MAC address
![image](https://github.com/user-attachments/assets/6da76067-ca03-4a79-b4ef-20c85711d133)
- Keep enumerating until find the flag
![image](https://github.com/user-attachments/assets/2011215a-819d-4845-8015-322224a9e2ed)
Answer: SKY-AWSM-1570

