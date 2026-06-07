# W11 THM Pishing Analysis Fundamentals

## Task 2: The Email Address
### Identify the domain used in the following email address:
### hatsalesman@tryhatme.com

The email address hatsalesman@tryhatme.com was examined. The domain portion of an email address is located after the @ symbol. Therefore, tryhatme.com was identified as the domain.

```bash
tryhatme.com
```

## Task 3: Email Delivery
### (i) Which protocol is responsible for sending an email from a client to a mail server?

The room material explaining email delivery protocols was reviewed. SMTP (Simple Mail Transfer Protocol) was identified as the protocol responsible for sending emails from a client to a mail server

```bash
SMTP
```

### (ii) Which service is used to look up the recipient domain’s mail server?

The lesson content describing email routing was examined. DNS is used to look up the mail server associated with a recipient's domain name.

```bash
DNS
```

### (iii) Bob wants to access his email from multiple devices, including his phone and laptop.
### Which protocol should he use?

The scenario stated that Bob wanted to access his emails from multiple devices. IMAP was identified as the correct protocol because it synchronizes emails across multiple devices while keeping messages on the mail server.

```bash
IMAP
```

## Task 4: Email Headers
### (i) What is the full subject line of email1.eml?

The email1.eml file was opened using Thunderbird. The email header information was examined, and the Subject field was located. The value displayed in the Subject field was recorded as the answer.

```bash
Help protect your budget by protecting your home
```
<img width="895" height="800" alt="image" src="https://github.com/user-attachments/assets/31d11d98-e634-4798-be6c-e34ec9fbd019" />


### (ii)  View the message source of email1.eml using Thunderbird in your VM.
### What the IP address listed as the X-Originating-Ip?

The message source of email1.eml was viewed in Thunderbird. The email headers were inspected until the X-Originating-IP field was found, and the associated IP address was recorded.

```bash
43.255.56.161
```
<img width="860" height="792" alt="image" src="https://github.com/user-attachments/assets/b6b57e52-9f9a-4f23-9774-c62f4416dc89" />

## Task 5: Email Body
### (ii) Open up the email2.txt file to view the source of an attachment.
### What is the Content-Type of the attachment?

The source code of email2.txt was inspected. The Content-Type header associated with the attachment was located and showed the value application/pdf.

```bash
application/pdf
```
<img width="713" height="612" alt="image" src="https://github.com/user-attachments/assets/0d9ec44f-3bd3-4197-b2a6-1e353e62147f" />

### (ii)  What is the name of the attachment from the previous question?

While examining the attachment section of the email source, the filename parameter was identified. The attachment name was listed as zmqpalgh.pdf.

```bash
zmqpalgh.pdf
```
<img width="725" height="592" alt="image" src="https://github.com/user-attachments/assets/7cf24de4-2ee3-47de-bf94-5d35251fbeed" />

### (iii) Decode the base64 string using either a PDF converter (opens in new tab) or CyberChef (opens in new tab).
### What is the hidden flag value?

The Base64-encoded content from the attachment was copied and decoded using PDF converter. After decoding the content into a PDF file and opening it, the hidden flag was revealed and recorded.

```bash
THM{BENIGN_PDF_ATTACHMENT}
```
<img width="1446" height="792" alt="image" src="https://github.com/user-attachments/assets/77f4e344-89d9-40df-89ea-7a6f66da44ae" />
<img width="1263" height="625" alt="image" src="https://github.com/user-attachments/assets/39c083d6-1f36-4945-9c1c-e1921d144e58" />


## Task 6: Type of Phishing

### (i) Which reputable organization is being spoofed in this phishing attempt?

The email content was analyzed to determine which organization was being impersonated. The branding, message content, and references within the email indicated that the attacker was spoofing Home Depot.

```bash
Home Depot
```
<img width="733" height="112" alt="image" src="https://github.com/user-attachments/assets/c1fa6f30-152f-4167-9cd7-3456a464f9b0" />

### (ii) What is the sender's email address?

The sender information was reviewed from the email header. The email address displayed in the sender field was recorded as support@teckbe.com.

```bash
support@teckbe.com
```
<img width="830" height="270" alt="image" src="https://github.com/user-attachments/assets/89f3a447-3db1-427b-a161-9aa8baae9c2e" />

### (iii) Inspect the email message source.
### What is the defanged (opens in new tab) X-Originating-IP?

The email source was inspected and the X-Originating-IP header was located. The IP address was then defanged using CyberChef by replacing periods with [.] .

```bash
103[.]234[.]236[.]83
```
<img width="580" height="145" alt="image" src="https://github.com/user-attachments/assets/accbe682-07b2-4aa0-93b7-e62ed9d830a8" />
<img width="1201" height="597" alt="image" src="https://github.com/user-attachments/assets/06cb40de-6aef-4138-b15f-a90b33ecc027" />

### (iv) Continue analyzing the email message source.
### Which mail server generated the Authentication-Results header?

The email headers were examined further to locate the Authentication-Results field. The mail server that generated this header was identified and recorded.

```bash
atlas102.free.mail.gq1.yahoo.com
```
<img width="693" height="192" alt="image" src="https://github.com/user-attachments/assets/cca8f8ee-126b-4a46-af4f-d43dcdef5d4a" />

## Task 7: Conclusion

### What attack, signified by the acronym BEC, uses a compromised email to trick employees into fraud?

The room content discussing phishing attack types was reviewed. BEC was identified as the acronym for Business Email Compromise, a fraud technique that exploits compromised email accounts to deceive victims.

```bash
Business Email Compromise
```





