### cookie、localStorage、sessionStorage 的区别

- #### cookie : 一般由服务器端生成，可设置失效时间，如果在浏览器端生成 cookie，则默认关闭浏览器后失效。cookie 大小为 4KB 左右。cookie 每次都会携带在 HTTP 头中，如果 cookie 保存过多会带来性能问题。cookie 原生接口不友好。
- #### localStrong : 永久保存，除非被清除，storage 一般为 5MB，storage 仅在客户端保存，不参与和服务器的通信，storage 原生接口友好，也可自行封装
