
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

## Ref

https://cloud.google.com/kubernetes-engine/docs/how-to/persistent-volumes/preexisting-pd

https://aws.amazon.com/blogs/containers/using-ebs-snapshots-for-persistent-storage-with-your-eks-cluster/