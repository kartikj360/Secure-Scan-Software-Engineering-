# Software Engineering Project
#OVERVIEW
 One-step way to make payments, know about an item, and much more work in one scan. The technology of the QR code has
facilitated us. A QR code, an initialism for quick response code, is a type of matrix barcode or two-dimensional barcode that has
become a part of our daily life in numerous ways. When we scan a QR code, it merely displays the link we can follow. However, there
always exists a question mark on the URL source, whether that link is secured enough.


#EXISTING SYSTEM:
 There are numerous applications available for scanning QR Codes. As the QR codes are not inspected or made by a secure
authority, anyone can create a QR code using simple techniques in a matter of seconds, yet this piece of code is incomprehensible to
the naked eye.
The URL data type is the only scenario in which conventional QR codes can carry executable data. Because a reader would
generally send the data to the application associated with the data type utilized by the QR code, these URLs may contain JavaScript
code that can be used to exploit vulnerabilities in applications on the host system, such as the reader, web browser, or image viewer.
Linking to dangerous websites with browser exploits, enabling the microphone/camera/GPS and then streaming those feeds to a
remote server, analysis of sensitive data (passwords, files, contacts, transactions), sending email/SMS/IM messages or packets for
DDoS as part of a botnet, corrupting privacy settings, stealing identity, and even containing malicious logic such as JavaScript or a
virus are all risks. These actions could occur in the background, with the user only seeing the reader open a seemingly innocuous web
page.


#OUR SYSTEM:
Even though QR code scanner is inseparable from our daily life, many users are unaware of the dark sides of using this
technology. One way is to check each and every QR code and its source and authenticity. Scanning all the QR codes around a large
area, maintaining a proper database, and going through it each time while scanning a code is a laborious task. An easier way would be
to automate this task and make it more efficient and feasible by maintaining a middleware database authenticator software. That
software will work as a standard QR code scanner and, on scanning, verifies the code from the database and informs the user whether
the code is secure or not.
