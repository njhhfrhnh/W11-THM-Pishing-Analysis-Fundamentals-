# W11 THM Pishing Analysis Fundamentals

## Task 2: The Email Address
### Identify the domain used in the following email address:
### hatsalesman@tryhatme.com

```bash
tryhatme.com
```

## Task 3: Email Delivery
### (i) Which protocol is responsible for sending an email from a client to a mail server?
```bash
SMTP
```

### (ii) Which service is used to look up the recipient domain’s mail server?
```bash
DNS
```

### (iii) Bob wants to access his email from multiple devices, including his phone and laptop.
Which protocol should he use?
```bash
IMAP
```
## Task 4: Email Headers
### (i) What is the full subject line of email1.eml?
```bash
Help protect your budget by protecting your home
```
<img width="895" height="800" alt="image" src="https://github.com/user-attachments/assets/31d11d98-e634-4798-be6c-e34ec9fbd019" />


### (ii)  View the message source of email1.eml using Thunderbird in your VM.
### What the IP address listed as the X-Originating-Ip?
```bash
43.255.56.161
```
<img width="860" height="792" alt="image" src="https://github.com/user-attachments/assets/b6b57e52-9f9a-4f23-9774-c62f4416dc89" />

## Task 5: Email Body
### (ii) Open up the email2.txt file to view the source of an attachment.
### What is the Content-Type of the attachment?
```bash
application/pdf
```
<img width="713" height="612" alt="image" src="https://github.com/user-attachments/assets/0d9ec44f-3bd3-4197-b2a6-1e353e62147f" />

### (ii)  What is the name of the attachment from the previous question?
```bash
zmqpalgh.pdf
```
<img width="725" height="592" alt="image" src="https://github.com/user-attachments/assets/7cf24de4-2ee3-47de-bf94-5d35251fbeed" />

### (iii) Decode the base64 string using either a PDF converter (opens in new tab) or CyberChef (opens in new tab).
### What is the hidden flag value?
```bash
THM{BENIGN_PDF_ATTACHMENT}
```
<img width="1446" height="792" alt="image" src="https://github.com/user-attachments/assets/77f4e344-89d9-40df-89ea-7a6f66da44ae" />
<img width="1263" height="625" alt="image" src="https://github.com/user-attachments/assets/39c083d6-1f36-4945-9c1c-e1921d144e58" />

## Task 6: Type of Phishing

### (i) Which reputable organization is being spoofed in this phishing attempt?
```bash
Home Depot
```
<img width="733" height="112" alt="image" src="https://github.com/user-attachments/assets/c1fa6f30-152f-4167-9cd7-3456a464f9b0" />

### (ii) What is the sender's email address?
```bash
support@teckbe.com
```
<img width="830" height="270" alt="image" src="https://github.com/user-attachments/assets/89f3a447-3db1-427b-a161-9aa8baae9c2e" />

### (iii) Inspect the email message source.
### What is the defanged (opens in new tab) X-Originating-IP?
```bash
103[.]234[.]236[.]83
```
<img width="580" height="145" alt="image" src="https://github.com/user-attachments/assets/accbe682-07b2-4aa0-93b7-e62ed9d830a8" />
<img width="1201" height="597" alt="image" src="https://github.com/user-attachments/assets/06cb40de-6aef-4138-b15f-a90b33ecc027" />

### (iv) Continue analyzing the email message source.
### Which mail server generated the Authentication-Results header?
```bash
atlas102.free.mail.gq1.yahoo.com
```
<img width="693" height="192" alt="image" src="https://github.com/user-attachments/assets/cca8f8ee-126b-4a46-af4f-d43dcdef5d4a" />

## Task 7: Conclusion

### What attack, signified by the acronym BEC, uses a compromised email to trick employees into fraud?
```bash
Business Email Compromise
```





