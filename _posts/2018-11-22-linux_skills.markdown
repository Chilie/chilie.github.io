# Linux系统命令中的坑

## cron定时任务
为啥指定的定时任务，系统不执行呢？主要的原因是`cron`的环境变量与我们直接在`bash`中执行的环境变量不同，为了让`cron`采用同样的环境变量，可以使用
> * * * * * source $HOME/.bash_profile; source $HOME/.bashrc; 

网页上说`cron`的运行环境变量定义在`/ect/environment`，不加载`bash`定义的环境变量，其它解决方案，如添加绝对路径的解决方案，与这种根本的解决方案来说还是前者较优。


