# htop

<!-- toc -->

`官网` http://htop.sourceforge.net/

## 与top相比，htop有以下优点：

- 可以横向或纵向滚动浏览进程列表，以便看到所有的进程和完整的命令行。
- 在启动上，比top 更快。
- 杀进程时不需要输入进程号。
- htop 支持鼠标操作。
- top 已经很老了。


## RHEL/CentOS 安装

```bash
rpm -ivh http://download.fedoraproject.org/pub/epel/6/x86_64/epel-release-6-8.noarch.rpm

## 导入key
rpm --import /etc/pki/rpm-gpg/RPM-GPG-KEY-EPEL-6

yum install htop
```


## Debian/Ubuntu 安装

```bash
sudo apt-get install htop
```
