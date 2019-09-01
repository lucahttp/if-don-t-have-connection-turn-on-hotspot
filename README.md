# if-don-t-have-connection-turn-on-hotspot
does what the title says



### Install node js

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

Requirements


The NodeJS modules required are pretty much just `underscore`, `async`, and `express`.

The web application requires `angular` and `font-awesome` to render correctly. To make the deployment of this easy, one of the other requirements is `bower`.

If you do not have bower installed already, you can install it globally by running: sudo npm install bower -g.



`npm install underscore`
`npm install async`
`npm install express`

`npm install angular`
`npm install font-awesome`


`npm install bower`
