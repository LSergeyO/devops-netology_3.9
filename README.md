# devops-netology_3.9  
1. 
![img.png](img.png)  

2. 
![img_1.png](img_1.png)  

3. 
![img_2.png](img_2.png)  

![img_3.png](img_3.png)  

4. 
![img_4.png](img_4.png)  

5. 
![img_7.png](img_7.png)  
vagrant@vagrant:~$ ssh vagrant@10.0.2.15  

6. vagrant@vagrant:~/.ssh$ sudo mv ~/.ssh/id_rsa ~/.ssh/id_rsa_1  
vagrant@vagrant:~/.ssh$ sudo vim ~/.ssh/config  
- Host test1
- HostName 10.0.2.15  
- User vagrant  
- Port 22  
- IdentityFile ~/.ssh/id_rsa_1  

7. 
![img_5.png](img_5.png)  
![img_6.png](img_6.png)  