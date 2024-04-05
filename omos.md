# Online Medicine Ordering System - Delete any file in the background

- **Exploit Title:** Online Medicine Ordering System - Delete any file in the background
- **Date:** 2024-4-05
- **Exploit Author:** shuo sheng；jixin zhang
- **Vendor Homepage:** https://www.sourcecodester.com/php/15359/online-medicine-ordering-system-phpoop-free-source-code.html
- **Software Link:** https://www.sourcecodester.com/download-code?nid=15359&title=Online+Medicine+Ordering+System+in+PHP%2FOOP+Free+Source+Code
- **Version:** 1.0
- **CVE:** Reported, waiting for CVE number

## Description:

Online Medicine Ordering System backend settings have the function of deleting pictures to delete any files.



## Proof of Concept:

Create a test file 1.php in the root directory

![image-20240405205451734](C:\Users\28162\AppData\Roaming\Typora\typora-user-images\image-20240405205451734.png)

Log in to the backend and find the location shown in the picture below

![image-20240405205617551](C:\Users\28162\AppData\Roaming\Typora\typora-user-images\image-20240405205617551.png)



Use burpsuite to capture packets

Modify the path, click send, and return to the status success

![image-20240405205707567](C:\Users\28162\AppData\Roaming\Typora\typora-user-images\image-20240405205707567.png)