# alist-proxy-cf-pages

Use another machine/cf-pages to proxy alist's traffic. 使用cf-pages代理，加了点功能

_worker.js 中添加了 PATH_PREFIX 功能 例如设置为 "/proxy/" 那么alist里就可以填 https://you.pr.com/proxy/ 配合 _routes.json 使用，可以防止被刷请求。


### 环境变量
|名称|作用|
|-|-|
|ADDRESS||
|TOKEN||
|WORKER_ADDRESS||
|PATH_PREFIX|PATH_PREFIX 功能|
