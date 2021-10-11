# git

- git checkout -b 分支 [origin/分支] //修改分支
- git branch //查看分支
- git submodule init //初始化子项目
- git submodule update //更新子项目
- yarn build   //打包 web_client
- 同步代码
  - git log![image-20210715173655104](C:\Users\zhuxiaoyue\AppData\Roaming\Typora\typora-user-images\image-20210715173655104.png)
  - 分支部分：git cherry-pick 上述编码（https://ruanyifeng.com/blog/2020/04/git-cherry-pick.html）
- 强制撤回提交
  - git reset --hard HEAD^
  - git push -f
- 换源
  - yarn config get registry
  - yarn config set registry NewUrl
- tab
  - 查看：git tag
  - 打tag(本地)：git tag -a TagName -m "TagName"
  - 推送本地tag到线上：git push origin TagName
  - 删除本地tag：git tag -d TagName
  - 删除线上：git push origin :refs/tags/TagName

# winscp

- 账号：root

- 密码：screencast

- 192.168.39.47    22222

  

# 分支

- 工控二期：feature/8.5.1.1000_base_8.5.0.1000
- 专用机 - 5期：feature/8.3.4.1000_base_8.3.1.1000
  - 账号：secadm（安全管理）
  - 账号：root（系统管理员）
  - 账号：auditadm
  - 密码：Admin123
- 8.5版本一期：feature/8.5.0.1000_base_8.4.0.2000
- 1200：feature/8.5.0.1200_base_8.5.0.1100
- 1201：hotfix/8.5.0.1201_base_8.5.0.1200
- 2000：feature/8.5.0.2000_base_8.5.0.1201
- 老准入：hotfix/7.0.3.4221_base_7.0.3.4220
  - 打开地址：http://10.91.209.158:8080/
  - 远程连接： win+R, mstsc
    -  连接名称：A023562\administrator
    - 密码：#ipdsms3.0$
    - 连接地址：10.91.209.158:8080
  - ![image-20210811194013965](C:\Users\zhuxiaoyue\AppData\Roaming\Typora\typora-user-images\image-20210811194013965.png)
  - ![image-20210811194338303](C:\Users\zhuxiaoyue\AppData\Roaming\Typora\typora-user-images\image-20210811194338303.png)
- 老准入base：lts/6.7.0.4400_base_version-6.7.0.4300
- base_4500：lts/6.7.0.4500_base_version-6.7.0.4400
- evidence：evidence/8.6.0.1000

# 技术

- echarts





