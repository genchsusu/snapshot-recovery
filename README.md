
## 1.Modify makefile and values.yaml as you need

Usually `install` part in values.yaml doesn't need to change

## 2.Run command

```
Usage: ./run <command> [options]

Commands:
  install
  snapshot
  restore

Options:
  -n, --name      Specify the name (Default: default_name)
  -s, --snapshot  Specify the snapshot name (Default: default_snapshot)
  -h, --help      Display this help message
```

Require jq

## References

https://cloud.google.com/kubernetes-engine/docs/how-to/persistent-volumes/preexisting-pd

https://aws.amazon.com/blogs/containers/using-ebs-snapshots-for-persistent-storage-with-your-eks-cluster/

Managing the Amazon EBS CSI driver as an Amazon EKS add-on (https://docs.aws.amazon.com/eks/latest/userguide/managing-ebs-csi.html)

Creating the Amazon EBS CSI driver IAM role for service accounts (https://docs.aws.amazon.com/eks/latest/userguide/csi-iam-role.html)

CSI Snapshotter (https://github.com/kubernetes-csi/external-snapshotter)

Deploy a sample application and verify that the CSI driver is working (https://docs.aws.amazon.com/eks/latest/userguide/ebs-sample-app.html)

Installing CSI driver and creating an admin user to access the cluster (https://github.com/parjun8840/ekscsidriver/blob/main/README.md)

How do I troubleshoot issues with my EBS volume mounts in Amazon EKS? (https://aws.amazon.com/premiumsupport/knowledge-center/eks-troubleshoot-ebs-volume-mounts/)

K8s — Using AWS EBS as Persistent Volume (https://blog.devgenius.io/k8s-using-aws-ebs-as-persistent-volume-dcf4e50fb755)