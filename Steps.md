# Creazione VPN Site-to-Site e sincronizzazione tra NAS Synology :computer:
L'obiettivo finale sarà quello di creare una sincronizzazione tra cartelle di due NAS remoti.<br>
<br>

Per la creazione del seguente progetto avremo bisogno di:
>            due router Mikrotik
>            due NAS Synology
>            permessi di amministratore
>            buona connessione ad internet
>            relativi cavi ethernet

[CREAZIONE VPN SITE TO SITE](#CREAZIONE-VPN-SITE-TO-SITE)<br><br>
[SINCRONIZZAZIONE NAS](#SINCRONIZZAZIONE-NAS)<br><br>

# CREAZIONE VPN SITE TO SITE
L'esempio di infrastruttura che utilizzeremo per il nostro progetto sarà:

### SITO A
>            ip privato locale: 192.168.20.0/24
>            ip pubblico locale 82.85.93.37

### SITO B
>            ip privato remoto: 192.168.100.0/24
>            ip pubblico remoto: 95.249.68.86

### Le impostazioni seguenti si riferiscono al Mikrotik del SITO A
![](/Immagini/1.PNG)
![](/Immagini/2.PNG)
![](/Immagini/3.PNG)
![](/Immagini/4.PNG)
![](/Immagini/5.PNG)

### checkpoint :white_check_mark: <br>
![](/Immagini/6.PNG)
![](/Immagini/7.PNG)

# SINCRONIZZAZIONE NAS
![](/Immagini/a.PNG)
![](/Immagini/b.PNG)
![](/Immagini/c.PNG)
