# n

A collection of tools used in development

## Build
```
make
make build-vendor
make clean
```

## Usage
```
./n --help
```

## Child Command

- **cluster:** deploy a new or a component for kubernetes cluster
- **help:** Help about any command
- **kc:** manage your kubeconfig and context
- **run:** run a go project
- **version:** n version

## Remote Create 

```
n cluster new --ip $public_host -p $password --image-repository registry.cn-hangzhou.aliyuncs.com/google_containers remote

```

