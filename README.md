### GET 和 POST 的区别

- ##### <font color="red"> GET 请求在浏览器回退时是无害的，POST 会再次提交请求</font>
- ##### GET 请求产生的 URL 地址可以被收藏，二 POST 不可以
- ##### <font color="red"> GET 请求会被浏览器职业缓存，而 POST 不会，除非手动设置</font>
- ##### GET 请求只能进行 URL 编码，而 POST 支持多种编码方式
- ##### <font color=red>GET 请求参数会被完整的保留在浏览器历史记录里，而 POST 中的参数不会被保留</font>
- ##### <font color=red>GET 请求在 URL 中传参是有长度限制的（不固定，因浏览器决定），而 POST 没有限制</font>
- ##### GET 请求只接受 ASC2 字符，而对参数的数据类型 POST 没有限制
- ##### GET 请求比 POST 请求更不安全，应为参数直接暴露在 URL 上，所以不能用来传递敏感数据
- ##### <font color=red>GET 请求穿赞通过 URL 传递，而 POST 放在 request.body 上</font>
