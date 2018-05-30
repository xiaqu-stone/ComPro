# ComPro
通用文件

## 上传Jcenter
- install-v1.gradle
- bintray-v1.gradle 
- bintray-v2.gradle
    
    忽略javadoc编译报错，去除文件gpg的校验

## 上传maven私服

- upload-archives-v1.gradle
    
    账户配置在gradle.properties中
- upload-archives-v2.gradle
    
    账户配置在gradle.properties中,并且增加 snapshot 仓库的上传
- upload-archives-v3.gradle
    
    账户配置在local.properties中