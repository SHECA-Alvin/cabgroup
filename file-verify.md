
The following is the complete process of SHECA verifying the IP address (113.10.156.232) for the above certificate:

Step 1: ihuandu applies to SHECA for an SSL certificate that supports the IP through the operator platform provided by SHECA.

Step 2: ihuandu obtains the file verification path and verification value through the operator platform interface, as shown in the following figure

![image](https://github.com/SHECA-Alvin/cabgroup/assets/163508594/8835a474-8350-4147-88fc-8b7b67c2914d#pic_left)

Step 3: By default, SHECA scans the paths under ports 443 and 80 under the IP to verify whether the expected values ​​are configured.

The domain name verification scan log of the relevant system is as follows:
![image](https://github.com/SHECA-Alvin/cabgroup/assets/163508594/c379289e-90ab-4211-b902-5a9f4e9d431b#pic_left)

From the log, we can see that SHECA scanned the expected value through the 443 port of the IP, and judged that the domain name verification passed. Since this discussion does not involve enterprise information verification, it will not be described in detail here.
