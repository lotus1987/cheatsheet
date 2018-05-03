# cheatsheet
common useful command

备份linux 

# tar cvpzf backup.tgz --directory=/ --exclude=/proc --exclude=/lost+found --exclude=/backup.tgz --exclude=/mnt --exclude=/sys --exclude=/media --exclude=/vmlinuz*

使用下面的命令来恢复系统：
 # tar xvpfz backup.tgz -C /
 # mkdir (the dirs which exclude)
