```
telnet 10.0.0.10
cd /boot/config/plugins/dockerMan/templates
git https://github.com/jamesmcallister/unraid-docker.git unraid-docker
cd unraid-docker
rm -rf .git
```

or

To install this plugin, paste the following URL into the Plugins / Install PlugIn section:

```
https://raw.githubusercontent.com/Squidly271/community.applications/master/plugins/community.applications.plg
```


Get into the MariaDB command line utility: `mysql -u root -p`

Type in: `CREATE USER 'kodi' IDENTIFIED BY 'kodi';`
Type in: `GRANT ALL ON *.* TO 'kodi';`
Type in: `flush privileges;`
Close out the command line tool with`\q`