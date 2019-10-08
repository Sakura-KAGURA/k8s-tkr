# Step06 Kubernetes最初の一歩
1. クラスタ構成の確認
```
kubectl get node
```
1. ポッドの実行
```
kubectl run hello-world --image=hello-world -it --restart=Never
```

1. コントローラによるポッドの実行

1. ジョブによるポッドの実行
