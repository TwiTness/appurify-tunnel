Appurify Tunnel
===============

An easy way to create a “tunnel” between your machine and Appurify’s devices when running automated tests. Allows your application to access internal web services as if you were running tests in your local environment.

```
$ ./appurify-tunnel.py -h
usage: appurify-tunnel.py [-h] [--api-key API_KEY] [--api-secret API_SECRET]
                          [--username USERNAME] [--password PASSWORD]
                          [--pid-file PID_FILE] [--daemon] [--pid PID]
                          [--terminate]

Appurify developer tunnel client v0.5.1

optional arguments:
  -h, --help            show this help message and exit
  --api-key API_KEY     Appurify developer key
  --api-secret API_SECRET
                        Appurify developer secret
  --username USERNAME   Appurify username
  --password PASSWORD   Appurify password
  --pid-file PID_FILE   Save pid to file
  --daemon              Run in background (supported only on *nix systems)
  --pid PID             Tunnel session pid to terminate
  --terminate           Terminate process identified by --pid-file or --pid
                        and shutdown

Email us at support@appurify.com for further information
```

More information: https://appurify.atlassian.net/wiki/display/APD/Tunneling
