# jenkins

项目地址/clone 代码   
shell 调用 ruby
### 前置条件
* java + tomcat + jenkins
* git/svn常用命令, 工具类
   
.jenkins

* jenkins user
* jenkins plugin
* jenkins job

```
➜  .jenkins tree
.
├── Connection\ Activity\ monitoring\ to\ slaves.log
├── com.dabsquared.gitlabjenkins.GitLabPushTrigger.xml
├── com.dabsquared.gitlabjenkins.connection.GitLabConnectionConfig.xml
├── config.xml
├── hudson.model.UpdateCenter.xml
├── hudson.plugins.git.GitTool.xml
├── hudson.tasks.Mailer.xml
├── identity.key.enc
├── jenkins.CLI.xml
├── jenkins.install.InstallUtil.lastExecVersion
├── jenkins.model.DownloadSettings.xml
├── jenkins.security.QueueItemAuthenticatorConfiguration.xml
├── jenkins.security.UpdateSiteWarningsConfiguration.xml
├── jobs                                                            构建任务     
│   ├── aries
│   │   └── builds
│   ├── dev_sync_update
│   │   └── builds
│   └── dev_unity_build
│       └── builds
├── logs
│   └── tasks
│       └── Connection\ Activity\ monitoring\ to\ agents.log
├── nodeMonitors.xml
├── nodes
├── plugins                                                         插件
├── queue.xml.bak
├── scriptApproval.xml
├── secret.key
├── secret.key.not-so-secret
├── secrets
├── updates
├── userContent
├── users                                                           用户
│   ├── admin
│   │   └── config.xml
│   └── dev
│       └── config.xml
└── war                                                             .war


```

### 配置备份

目前: 复制全部, 删减job, users

### 进阶
* Jenkins pipeline
* Jenkins + docker

### 参考资料

* [Jenkins入门系列之——00答疑解惑](http://www.cnblogs.com/zz0412/p/jenkins00.html)
* [jenkins](http://www.cnblogs.com/zz0412/tag/jenkins/)
* [使用Jenkins构建持续集成平台的资料](http://request.uml.com.cn/chengzhang/mobile/oneSubject.asp?wID=157&utype=gg&from=timeline&isappinstalled=0)
* [Jenkins 的输出日志也可以变得色色的](https://zhuanlan.zhihu.com/p/22032462?refer=debugtalk)
* [持续集成平台Jenkins的书籍或是学习资料？](https://www.zhihu.com/question/29163932/answer/138366614)
