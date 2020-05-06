# nexus3

## images name

- registry.cn-beijing.aliyuncs.com/meowbite/nexus3:3.23.0

## 启动参考

```bash
$ mkdir /some/dir/nexus-data && chown -R 200 /some/dir/nexus-data
$ docker run -d -p 8081:8081 --name nexus -v /some/dir/nexus-data:/nexus-data sonatype/nexus3
```

## github 地址

- https://github.com/sonatype/docker-nexus3

## hub 官方地址

- https://hub.docker.com/r/sonatype/nexus3/tags
