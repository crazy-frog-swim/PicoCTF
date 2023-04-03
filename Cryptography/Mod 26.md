# Mod 26
`picoCTF 2021`
`Cryptography`

### Description

Cryptography can be easy, do you know what ROT13 is? _cvpbPGS{arkg_gvzr_V'yy_gel_2_ebhaqf_bs_ebg13_jdJBFOXJ}_
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





