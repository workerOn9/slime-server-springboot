# SlimeGo

## Info

本项目使用`SpringBoot 3.4.3`+`Java21`，以及使用`Gradle`作为构建工具

端口`18080`

## Build - 构建

一般命令: 在gradle执行的加`-Pprofiles=${env}`，其中env是`['dev', 'prod']`其中一个；默认是`dev`

intelliJ: 直接选对应环境dev或者prod，实际他的命令是`-Pspring.active.profiels=${env}`，最后会因为`build.gradle`的配置使得成立

### env

> 文件路径: `src/resources`

* `application-dev.properties`: 对应开发配置
* `application-prod.properties`: 对应发行配置