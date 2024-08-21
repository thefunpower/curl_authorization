# CURL请求平台接口 

## 安装 

~~~
composer require thefunpower/curl_authorization
~~~


## 请求

~~~
$url = 'http://127.0.0.1:3001/openapi/company/index';
$bodys = [
    'title' => $this->title
];
$appcode = 'X_uLuUSvHJdiMgGEBwyoB_OVxs1r8X7E';
$out = curl_authorization($url, $bodys, $appcode);
~~~


### 开源协议 

[Apache License 2.0](LICENSE)
