# Web安全学习笔记

![](https://img.shields.io/github/stars/lylemi/learn-web-hacking.svg)
![](https://img.shields.io/github/forks/lylemi/learn-web-hacking.svg)
![](https://img.shields.io/github/issues/lylemi/learn-web-hacking.svg)

在学习Web安全的过程中，深感相关知识浩如烟海，而且很多知识点较为零散，没有比较清晰的脉络来参考和学习，于是尝试把一些知识、想法整理总结下来，最后形成了这份笔记。

所学浅薄、精力有限，这份笔记会有一些错误或者还没完成的部分，会逐渐补充或修正。如果存在错误欢迎各位读者以Issue或者PR的方式批评指正。

在编写笔记的过程中参考了很多资料，都在文末留下了相应的链接，感谢文章作者的分享。

笔记的在线版本可以点击[这里](https://websec.readthedocs.io)查看。

### 笔记大纲

1. 基础知识
    - Web发展简史
    - 计算机网络
    - 域名系统
    - HTTP标准
    - 代码审计
    - WAF
2. 信息收集
    - 域名信息
    - 站点信息
    - 端口信息
3. 内网渗透
    - Windows信息收集
    - Windows持久化
    - Linux信息收集
    - 痕迹清理
4. 常见漏洞
    - SQL注入
    - XSS
    - CSRF
    - SSRF
    - 命令注入
    - 文件读取
    - 文件上传
    - 文件包含
    - XXE
    - 模版注入
    - Xpath注入
    - 逻辑漏洞 / 业务漏洞
    - 配置安全
    - 中间件
    - Web Cache欺骗攻击
5. 语言与框架
    - PHP
    - Python
    - Java
    - JavaScript
    - Ruby
6. 防御技术
    - 总体思路
    - 团队建设
    - 威胁情报
    - 风险控制
    - 加固检查
    - 蜜罐技术
    - 入侵检测
    - 应急响应
    - 溯源分析
7. 工具与资源
    - 工具列表
    - 推荐资源
    - 爆破工具
    - 下载工具
    - 流量相关
    - 嗅探工具
    - SQLMap
8. 其他
    - 认证方式
    - 拒绝服务攻击
    - Docker

### 本地生成 HTML 格式的文档

```bash
git clone https://github.com/LyleMi/Learn-Web-Hacking.git
cd Learn-Web-Hacking
pip install sphinx sphinx-rtd-theme
make html
```

### 注

该笔记仅供学习和交流使用，请读者遵守《[中华人民共和国网络安全法](http://www.npc.gov.cn/npc/xinwen/2016-11/07/content_2001605.htm)》，勿进行非授权的测试。

本笔记内容可以任意转载，但请注明来源并提供链接。
