# Little-SSH-problem
##查看自己的SSH，ssh存储在.ssh文件夹下面的id_rsa.pub文件中
     命令行    `cat id_rsa.pub`
##如果需要修改git中的邮箱，需要手动修改，并保存。
##重新生成SSH，执行命令
`sh-keygen -t rsa -C "mltian@thoughtworks.com"`
##在id_rsa.pub中查看新的ssh，并添加到github上即可。
