* 适用于通过 dockerhub 上已有的镜像或 Dockerfile 来建实例的平台
* 在平台上部署
* 解锁 ChatGPT
* 在浏览器查看系统各项信息，方便直观
* 使用隧道
* 回落分流

## 部署:
### 镜像 `fscarmen/argo-x:latest`

### PaaS 平台用到的变量:
 
* 在 `server.js` 文件的第1、2行修改查询网页的用户名和密码
  | 变量名        | 是否必须 | 默认值 | 备注 |
  | ------------ | ------ | ------ | ------ |
  | WEB_USERNAME | 是 | admin | 网页的用户名 |
  | WEB_PASSWORD | 是 | password | 网页的密码 |
