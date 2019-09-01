# if-don-t-have-connection-turn-on-hotspot
does what the title says



### Install node (optional)

```
$ wget https://nodejs.org/dist/v10.16.3/node-v10.16.3-linux-armv6l.tar.xz
$ sudo mkdir /usr/lib/nodejs
$ sudo tar -xJvf node-v10.16.3-linux-armv6l.tar.xz -C /usr/lib/nodejs 
$ rm -rf node-v10.16.3-linux-armv6l.tar.xz
$ sudo mv /usr/lib/nodejs/node-v10.16.3-linux-armv6l /usr/lib/nodejs/node-v10.16.3
$ echo 'export NODEJS_HOME=/usr/lib/nodejs/node-v10.16.3' >> ~/.profile
$ echo 'export PATH=$NODEJS_HOME/bin:$PATH' >> ~/.profile
$ source ~/.profile
```

