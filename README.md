# GetDomainsBySSL

### 目前从三个地方获得相关（子）域名：

- [Google Certificate Transparency](https://www.google.com/transparencyreport/https/ct/)
- [crt.sh](https://crt.sh)
- OpenSSL SAN (Subject Alternative Name)

### 依赖：

- [lxml](https://pypi.python.org/pypi/lxml/2.3/)

### 注意：

- 需要能正常访问 Google
- Windows 没有 OpenSSL 命令
