# ECR

## docker login コマンド取得

```
aws ecr get-login
```

## build

```
docker build -t sample ./
```

## tag付与

```
docker tag sample:latest 864031815705.dkr.ecr.ap-northeast-1.amazonaws.com/sample:latest
```

## push

```
docker push 864031815705.dkr.ecr.ap-northeast-1.amazonaws.com/sample:latest
```
