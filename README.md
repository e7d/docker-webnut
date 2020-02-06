# docker-webNUT

webNUT (UPS network monitoring web ui) dockerized.

More infos on webNUT:  https://github.com/rshipp/webNUT

Set the following environment variables:  
**UPS_HOST** with NUT server host IP *(default: 127.0.0.1)*  
**UPS_PORT** with NUT server port *(default: 3493)*  
**UPS_USER** with NUT server username *(default: user)*  
**UPS_PASSWORD** with NUT server password *(default: secret)*

Run with:  
```shell
$ docker run -e UPS_HOST="10.11.12.13" -e UPS_PORT="3493" -e UPS_USER="user" -e UPS_PASSWORD="secret" -p 6543:6543 -e  e7db/webnut:latest
```
