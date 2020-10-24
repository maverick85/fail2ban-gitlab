# GitLab Fail2Ban Filter

## Updated for GitLab 13

### Instructions (CentOS 7)

+ Install EPEL-RELEASE repository and the fail2ban packages
```
yum install epel-release
yum install fail2ban fail2ban-systemd
```
+ Copy the contents of the repository to `/etc/fail2ban/`
+ Enable fail2ban at boot and start
```
systemctl enable --now fail2ban
```

[Source](https://gist.github.com/pawilon/238c278d3c6c4669771eb81b03264acd)