
First of all, it should be made clear that 113.10.156.232 only applied for two certificates in SHECA

The first certificate was issued at 10:29 on April 22, 2024, and the corresponding CT pre-certificate is https://crt.sh/?id=12806661692

The certificate was re-issued at 11:26 on April 22, 2024. The corresponding CT pre-certificate is https://crt.sh/?id=12807160321, and the re-issue reused the validation information of https://crt.sh/?id=12806661692

https://crt.sh/?id=12813257892 is the leaf certificate corresponding to https://crt.sh/?id=12807160321, which may have been uploaded to CT by the user

The following is the complete process of IP address verification for this certificate https://crt.sh/?id=12806661692：

Step 1:  ihuandu   applies to SHECA for SSL application supporting IP through the operator platform provided by SHECA.

Step 2:  ihuandu  obtains the file verification path and verification value through the operator platform interface, as shown in the following figure 
![image](https://github.com/SHECA-Alvin/cabgroup/assets/163508594/c637902a-9d49-49d3-b2b3-39b6d7d17a7e#pic_left)

Step 3: By default, SHECA will scan the paths under ports 443 and 80 under the IP to verify whether the expected values ​​are configured.

The domain name verification scan logs of the relevant systems are as follows: 
![image](https://github.com/SHECA-Alvin/cabgroup/assets/163508594/c379289e-90ab-4211-b902-5a9f4e9d431b#pic_left)


From the log, we can see that SHECA scanned the expected value through port 443 of the IP and judged that the domain name verification passed. Since this discussion does not involve enterprise information verification, we will not give more details.






