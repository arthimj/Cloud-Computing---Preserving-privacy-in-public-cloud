# Cloud-Computing---Preserving-privacy-in-public-cloud
1) AMAZON WEB SERVICE <br>
            Amazon Web Services (AWS) delivers a secure, scalable cloud computing platform with high availability, offering the flexibility for you to build a wide range of applications.We control the encryption method and the entire KMI.We use our own KMI to generate, store, and manage access to keys as well as control all encryption methods in our applications. AWS has no access to our keys and cannot perform encryption or decryption on our behalf. We are responsible for the proper storage, management, and use of keys to ensure the confidentiality, integrity, and availability of our data.<br>

2) Connecting to Your  Linux  Instance  from  Windows Using PuTTY<br>
The generated private key is converted into a format usable by Putty by using Puttygen.In Putty session ,hostname is given as the user_name@public_dns_name. The converted private key is loaded. Verify that the fingerprint in the security alert dialog box matches the fingerprint that we previously  by choosing YES. We are connected to the instances.<br>

3) Transferring Files to Your Linux Instance Using the WinSCP<br>
Start WinSCP.At the WinSCP login screen, for Host name, enter the public DNS hostname or public IPv4 address for our instance. Specify the private key for our instance. Choose Login to connect, and choose Yes to add the host fingerprint to the host cache. After the connection is established, in the connection window your Linux instance is on the right and your local machine is on the left. You can drag and drop files directly into the remote file system from your local machine.<br>
<br>
IMPLEMENTATION<br>
A.	REGISTERATION PHASE <br>

The user initially creates an account on CSP. Following which the CSP stores the user's account information. Next the  CSP allows the user to generate K(P) and K(R), using an RSA algorithm after a successful. Finally, CSP stores K(P) on DSP, and CSP sends K(R) to the client.<br>

B.	KEY GENERATION:<br>

Is used for the generation of public and private keys for encryption and decryption using Euler’s function<br>

C.	ENCRYPTION:<br>

 Encryption takes place when the plain text is converted into the ciphertext with the numbers, alphabets, and symbols.<br>
 
 D.	DECRYPTION PHASE:<br>

Decryption takes place when the ciphertext is converted into the plain text.<br>


 
 



