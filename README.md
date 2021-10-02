# send-gmail-curl

```
curl --connect-timeout 15 -v --insecure "smtp://smtp.gmail.com:587" -u "<gmail>@gmail.com:app-password"  --mail-from "<gmail>@gmail.com" --mail-rcpt "<gmail>@gmail.com" --ssl -T mail.txt
```

mail.txt content:

```
From: "KANG" <[mail]@gmail.com>
To: "[SOME ONE]" <[mail address]>
Subject: [Subject]

[Content]
```
