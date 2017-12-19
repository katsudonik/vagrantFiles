* https://app.vagrantup.com/kikeda/boxes/openam
* http://blog.nikuniku.me/entry/%3Fp%3D686
* https://www.ogis-ri.co.jp/otc/hiroba/technical/openid-connect/chap2.html
* https://qiita.com/nanazero/items/56d6bc70b7348dce1aca
* https://www.slideshare.net/kura_lab/openid-connect-id?next_slideshow=1
* https://qiita.com/gzock/items/a64940833dbaae9802db
* https://qiita.com/nanazero/items/10a593c6b0ac770ee92e

```
vagrant add ...
vagrant up
vagrant reload
vagrant ssh

vi /etc/hosts
# set "127.0.0.1 openam.example.com"

vi /etc/tomcat/tomcat.conf
# set "LANG="en_US""

sudo systemctl start tomcat
```

access to:
http://openam.example.com:8081/openam/config/options.htm

select custom install
