## バージョン固定解除

```
sudo vim /etc/yum.conf
# releasever=latest のコメントを外す
```

## アップデート
sudo yum clean all
sudo yum update -y

## アップデート確認
cat /etc/system-release

## バージョン固定解除を戻す

```
sudo vim /etc/yum.conf
# releasever=latest をコメントアウト
```
