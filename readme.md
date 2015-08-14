```
telnet 10.0.0.10
cd /boot/config
git clone git@github.com:youbiteme/unraid-docker.git unraid-docker
cd unraid-docker
rm -rf .git
git init
git add remote git@github.com:youbiteme/unraid-docker.git
```

or

To install this plugin, paste the following URL into the Plugins / Install PlugIn section:

```
https://raw.githubusercontent.com/Squidly271/community.applications/master/plugins/community.applications.plg
```