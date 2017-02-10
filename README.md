# Viz 的私人证书颁发机构

为了增强私人服务的安全性，部分 Viz 的私人站点改为客户端证书验证。

这个证书颁发机构将为此类私人站点及其用户颁发服务器端和客户端证书，任何不认识（或不信任）Viz 的人不应当把这个证书颁发机构的根证书添加至自己的浏览器或系统。

## 相关信息

* 证书颁发政策／实践声明：http://csp.root-x1.ca.viz.software
* 证书吊销列表地址：http://crl.root-x1.ca.viz.software
* OCSP 服务器地址：http://ocsp.root-x1.ca.viz.software/
* 根证书位置：http://cert.root-x1.ca.viz.software/

## 参考链接

* [OpenSSL Certificate Authority][1]
* [subjectAltName in Environment Variable][2]
* [Key Usage Extensions and Extended Key Usage][3]
* [RFC for X509 PKI][4]

[1]: https://jamielinux.com/docs/openssl-certificate-authority/
[2]: http://security.stackexchange.com/questions/74345/provide-subjectaltname-to-openssl-directly-on-command-line
[3]: https://www.ibm.com/support/knowledgecenter/SSKTMJ_8.0.1/com.ibm.help.domino.admin.doc/DOC/H_KEY_USAGE_EXTENSIONS_FOR_INTERNET_CERTIFICATES_1521_OVER.html
[4]: https://tools.ietf.org/html/rfc5280
