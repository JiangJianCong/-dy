# dy数据加密算法
***
#### xlog, POST请求

- HOST : 120.24.188.220:9527/aweme/xlog
- body:
  - 字段 type 字段, 1为解密, 2为加密
  - 字段 base64，加密或者解密字节流base64

#### xgorgon

- HOST: 120.24.188.220:9527/aweme/xgorgon
- BODY:
  - timeMillis 时间戳 
  - url 请求url
  - xssstub 空可以传空字符串
  - cookie 示例：install_id=68554875784; ttreq=1$397d54e1ef4087ade374a59c7af7193dcd82872e; qh[360]=1; odin_tt=7c6edfdc31451442fdaeb1b62d8114ec666e60995b40f35b4097306f3b88bb41029645811e02b3808f6e78de82536d6bae64ace0c785eb80374604473efd178c

#### ttencrypt

- HOST : 120.24.188.220:9527/aweme/ttencrypt
- body:
  - 字段 type 字段, 1为解密, 2为加密
  - 字段 base64，加密或者解密字节流base64
  
---

- 破解这个算法仅是个人兴趣爱好，如果你有破解的兴趣，可以联系我~
