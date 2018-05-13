# vagrantFiles

* ホスト側のsyncフォルダ内にソースを配置→ホスト側のパーミッションがゲスト側のパーミッションになる
* ゲスト側でsyncフォルダのパーミッション（再帰でなくて良い）許可しないとapacheからアクセスできない
* virtualboxのバージョンが高いとvagrantと対応してなくて立ち上げできない
https://www.vagrantup.com/docs/virtualbox/

* vagrant ssh key created to each vm by default. in windows, stop it is required.
```
config.ssh.insert_key = false
```
