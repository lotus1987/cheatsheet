# cheatsheet
common useful command

 备份linux 

tar cvpzf backup.tgz --exclude=/proc --exclude=/lost+found --exclude=/backup.tgz --exclude=/mnt --exclude=/sys --exclude=/media  /

#使用下面的命令来恢复系统：
tar xvpfz backup.tgz -C /

mkdir (the dirs which exclude)


#Epub reader:

sudo apt-get install calibre


#netease music terminal version:

musicbox


#ssh-keygen

#复制自己的公钥到服务器

ssh-copy-id user@host
