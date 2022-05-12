# BAE14-repo

Let me see if this triggers a build now I've fixed the config
 and the webhook and the security group

credcheck


Set Ubuntu 18.04 mysql-server to allow root login using localhost not auth_socket

```
sudo mysql -u root -p mysql  -e "UPDATE user SET plugin='mysql_native_password',authentication_string=PASSWORD('password') WHERE user = 'root'; flush privileges;"
```

