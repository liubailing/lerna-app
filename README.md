#version , 当前库的版本
npmClient , 允许指定命令使用的client， 默认是 npm， 可以设置成 yarn
command.publish.ignoreChanges ， 可以指定那些目录或者文件的变更不会被publish
command.bootstrap.ignore ， 指定不受 bootstrap 命令影响的包
command.bootstrap.npmClientArgs ， 指定默认传给 lerna bootstrap 命令的参数
command.bootstrap.scope ， 指定那些包会受 lerna bootstrap 命令影响
packages ， 指定包所在的目录