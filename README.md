<div align="center">

# docker-mirror

[![Auth](https://img.shields.io/badge/Auth-gebangfeng-ff69b4)](https://github.com/gebangfeng)
[![GitHub contributors](https://img.shields.io/github/contributors/gebangfeng/docker-mirror)](https://github.com/gebangfeng/docker-mirror/graphs/contributors)
[![GitHub Issues](https://img.shields.io/github/issues/gebangfeng/docker-mirror.svg)](https://github.com/gebangfeng/docker-mirror/issues)
[![GitHub Pull Requests](https://img.shields.io/github/issues-pr/gebangfeng/docker-mirror)](https://github.com/gebangfeng/docker-mirror/pulls)
[![GitHub Pull Requests](https://img.shields.io/github/stars/gebangfeng/docker-mirror)](https://github.com/gebangfeng/docker-mirror/stargazers)
[![HitCount](https://views.whatilearened.today/views/github/gebangfeng/docker-mirror.svg)](https://github.com/gebangfeng/docker-mirror)
[![GitHub license](https://img.shields.io/github/license/gebangfeng/docker-mirror)](https://github.com/gebangfeng/docker-mirror/blob/main/LICENSE)
[![](https://img.shields.io/badge/Awesome-MyStarList-c780fa?logo=Awesome-Lists)](https://github.com/gebangfeng/awesome-stars-gebangfeng#readme)

<p> 多平台容器镜像代理服务,支持 Docker Hub, GitHub, Google, k8s, Quay, Microsoft 等镜像仓库. </p>

<img src="https://cdn.jsdelivr.net/gh/gebangfeng/tu@main/img/image_20240420_214408.gif" width="800"  height="3">
</div><br>

本项目灵感来自：[Thanks-Mirro](https://github.com/eryajf/Thanks-Mirro)，该项目分享的是docker镜像直接可用，质量好，速度快的镜像

在此，对那些提供公共仓库镜像的企业或组织，致以感谢🫡！

<table border="1">
  <tr>
    <th>仓库地址</th>
    <th>镜像地址</th>
    <th>备注</th>
  </tr>
  <tr>
    <td rowspan="2">gcr.io</td>
    <td>gcr.nju.edu.cn</td>
    <td>南京大学开源镜像站, nexus3</td>
  </tr>
  <tr>
    <td style="color: red;">gcr.tencentcloudcr.com</td>
    <td>仅腾讯云vpc内部访问，registry2 proxy</td>
  </tr>
  <tr>
    <td rowspan="2" >registry.k8s.io</td>
    <td>registry-k8s-io.mirrors.sjtug.sjtu.edu.cn</td>
    <td>上海交通大学, registry2 proxy</td>
  </tr>
  <tr>
    <td>k8s.nju.edu.cn</td>
    <td>南京大学开源镜像站, nexus3</td>
  </tr>
  <tr>
   <td rowspan="2">k8s.gcr.io</td>
    <td>gcr.nju.edu.cn</td>
    <td>南京大学开源镜像站, nexus3</td>
  </tr>
  <tr>
    <td style="color: red;">k8s.tencentclouacr.com</td>
    <td>仅腾讯, 云vpc内部访问, registry2 proxy</td>
  </tr>
  <tr>
    <td rowspan="2">quay.io</td>
    <td>quay.nju.edu.cn</td>
    <td>南京大学开源镜像站, nexus3</td>
  </tr>
  <tr>
    <td style="color: red;">quay.tencentcloudcr.com</td>
    <td>仅腾讯云vpc内部访问, registry2 proxy</td>
  </tr>
  <tr>
  <td rowspan="2">nvcr.io</td>
    <td>nver.nju.edu.cn</td>
    <td>南京大学开源镜像站, nexus3</td>
  </tr>
  <tr>
    <td style="color: red;">nvcr.tencentcloudcr.com</td>
    <td>仅腾讯云vpc内部访问, registry2 proxy</td>
  </tr>
  <tr>
  <td rowspan="6">docker.io</td>
   <td style="color: red;">mirror.ccs.tencentyun.com</td>
    <td>仅腾讯云vpc内部访问, registry2 proxy</td>
  </tr>
  <tr>
    <td>docker.nju.edu.cn</td>
    <td>南京大学开源镜像站, nexus3</td>
  </tr>
  <tr>
    <td>docker.mirrors.situg.situ.edu.cn</td>  
    <td>上海交通大学, registry2 proxy</td>
  </tr>
  <tr>
    <td>docker.m.daocloud.io</td>
    <td>国内可用, 带宽低</td>
  </tr>
  <tr>
    <td>hub-mirror.c.163.com</td>
    <td>国内可用，更新慢</td>
  </tr>
  <tr>
    <td>*****.mirror.aliyuncs.com</td>
    <td>国内可用，更新慢</td>
  </tr>
</table>