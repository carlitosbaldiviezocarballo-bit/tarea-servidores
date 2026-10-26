# Configuración de servidores: correo, TELNET y SSH

Asignatura: Tecnología Web I
Servidor: Ubuntu Server 26.04.1 LTS (VMware) - mail.baldiviezo.local - 192.168.52.10

| Archivo | Descripción |
|---|---|
| main.cf | Postfix (SMTP) |
| dovecot.conf | Configuración efectiva de Dovecot 2.4 (`doveconf -n`) |
| 99-lab.conf | Ajustes propios de Dovecot (Maildir, IMAP/POP3) |
| sshd_config | OpenSSH: puerto 2222, sin root, solo llaves |
| 50-cloud-init.conf | Override de sshd con PasswordAuthentication no |
| ssh.socket-override.conf | Puerto 2222 en ssh.socket |

Telnet se instaló solo para la demostración con Wireshark y luego se desinstaló.
No se incluyen llaves privadas ni contraseñas.
