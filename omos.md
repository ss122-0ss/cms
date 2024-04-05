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

![图片](https://github.com/ss122-0ss/cms/assets/131983607/fa855506-8561-4280-bfd1-6ad3e99c75d9)


Log in to the backend and find the location shown in the picture below

![图片](https://github.com/ss122-0ss/cms/assets/131983607/c24a40c6-d6ba-4216-9d92-9d327b8ac526)



Use burpsuite to capture packets

Modify the path, click send, and return to the status success
![图片](https://github.com/ss122-0ss/cms/assets/131983607/f0f611bb-c314-4bed-9ab3-5aaa5e431e8f)
