# openldaphelm

## helm的chart仓库地址为：https://tjkkking.github.io/openldaphelm/charts/

## 本Chart仓库的使用方法

1、添加chart仓库
```
# helm repo add ldaprepo https://tjkkking.github.io/openldaphelm/charts/
```

2、添加成功
```
# helm repo list
NAME  	URL                                   
```

3、搜索chart包
```
# helm search repo                   	0.1.0        	1.16.0     	A Helm chart for Kubernetes 
```

4、安装chart包
```
# helm install xxx ldaprepo/test
```

xxx为relaese name

