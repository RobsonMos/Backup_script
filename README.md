# Backup_script
Shell script que realiza o backup dos diretórios,arquivos etc e manda para um servidor  FTP 
Abra o script com aditor de texto de sua preferencia copie o código e salve com nome backup_dir.sh
e edite as se quintes linhas

DIR_ORIG="/root/"   diretoria onde sera realizado o backup

BKP_NAME="Backup2.tgz" nome de saida do backp

FTP_HOST="192.168.0.1"  IP do servidor FTP 

FTP_USER="USER"        USER do servidor FTP

FTP_PASS="PASSWORD" PASS do servidor FTP

agora abra o terminal e execute o comando

# chmod +x backup_dir.sh && ./backup_dir.sh

Façam bom Uso ;)
