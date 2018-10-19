# drone 更新 rancher workload 插件

### Usage
```yml
pipeline:
  update-rancher:
    api: https://rancher.youdomain.com/v3/project/c-27tt1:p-wqtk3/workloads/default:default:nginx
    access_key: token-dfi8s
    secret_key: mhgb9w2csrvs6h9nm4fldl4z8f7h4sznx4m6ggvv4p54sffhjlkwvx
    data: [{"name":"nginx","image":"nginx:alpine"}]
```

### Parameter Reference
- `api` workload api url
- `access_key` rancher user api keys
- `secret_key` rancher user api keys
- `data` api result's containers field