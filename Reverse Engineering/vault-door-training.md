# vault-door-training
`picoCTF 2019`
`Reverse Engineering`

### Description

Your mission is to enter Dr. Evil's laboratory and retrieve the blueprints for his Doomsday Project. The laboratory is protected by a series of locked vault doors. Each door is controlled by a computer and requires a password to open. Unfortunately, our undercover agents have not been able to obtain the secret passwords for the vault doors, but one of our junior agents obtained the source code for each vault's computer! You will need to read the source code for each level to figure out what the password is for that vault door. As a warmup, we have created a replica vault in our training facility. The source code for the training vault is here: _VaultDoorTraining.java_
<br><br>

## Hint
<p align="center">
  <img src="https://user-images.githubusercontent.com/117136072/227871354-2aeca7e1-3bf4-44c9-b241-ce688c5b6431.png">
</p>

The hint show the flag of this challenge is inside the **Java code**
<br><br>



## Solution
1. Click _VaultDoorTraining.java_ word to download the file
<br>
<p align="center">
  <img src="https://user-images.githubusercontent.com/117136072/227869537-c6a266d3-9874-49d4-bcc1-7c5a69dcafd1.png">
</p>
<br><br>


2.	Use this link https://www.programiz.com/java-programming/online-compiler/ to run the **Java code** 
<br><br>


3. The password is inside the **checkPaasword** method 
<br>
<p align="center">
  <img src="https://user-images.githubusercontent.com/117136072/227869984-218e2107-e136-4394-bb70-06eff9e1a8f4.png">
</p>
<br><br>


4. **Access denied!** showed meaning the password is wrong. Because need to include keyword **‘picoCTF{}’** when entering the password. 
<br>
<p align="center">
  <img src="https://user-images.githubusercontent.com/117136072/227870334-949c50d1-1548-4e4f-91a8-72c4aed3b67a.png">
</p>
<br><br>


5.	The code shows check whether the user input is equal ‘**picoCTF{**_checkPassword_**}**’ or not. If the user input not equal then will shows ‘**Access denied!**’ else shows ‘**Access granted.**’.
<br>
<p align="center">
  <img src="https://user-images.githubusercontent.com/117136072/227870750-162a94be-6154-4623-b899-37a427627f76.png">
</p>
<br><br>


6.	**Access granted.** showed meaning the password is correct.
<br>
<p align="center">
  <img src="https://user-images.githubusercontent.com/117136072/227871029-a91a9149-fe75-4c3d-86f3-dcbcdc4afbb4.png">
</p>
<br><br>



