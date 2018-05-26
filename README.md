# nodeStd
tiny nodejs static web server 

### k8s 命令

查看已部署应用

- kubectl get deploy -n uaes-iot-dev

删除已部署应用

- kubectl delete deploy/hap-cloud-front -n uaes-iot-dev

检查部署是否成功

- kubectl get pods -n uaes-iot-dev
