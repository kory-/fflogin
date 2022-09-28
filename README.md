# fflogin
 
```
fflogin
  AWS Session Manager EC2 login
USAGE:
  fflogin [options]
OPTIONS:
  -L <port:host:hostport>  Local Port fowarding
  -R <port:host:hostport>  Remote Port fowarding
  -p <profilename>         Aws Profile name
  -h, --help               Show this help message.
```

# Basic use
`fflogin`

# Remote Port Fowerding
```
fflogin -R 3308:xxxx.database.com:3306
mysql -u admin -h 127.0.0.1 -P 3308 -p
```