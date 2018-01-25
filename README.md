# Response



- 构造函数
  - [Response()]()
- 属性
  - [body]()
  - ​



构造函数

| 说明                | &nbsp;     | 返回值类型                     |
| ----------------- | ---------- | ------------------------- |
| 返回一个新的Promise示例对象 | Response() | - new Response(body,init) |





|            | 说明                      | 返回值类型 |
| ---------- | ----------------------- | ----- |
| Response() | new Response(body,init) |       |



|           | 说明                      | 返回值类型               |
| --------- | ----------------------- | ------------------- |
| Response( | new Response(body,init) | - 返回一个新的Promise示例对象 |





属性

|      |                   |                       |
| ---- | ----------------- | --------------------- |
| body | 返回响应对象的主体<br>只读属性 | [`ReadableStream`](#) |
|      |                   |                       |
|      |                   |                       |





## 构造函数（Constructor）





## Response()

<br>

```
new Response(body, init)                        Response
```

>  创建一个新的Response 实例对象。

- body :  Object     - 配置参数 。只读
  - [`Blob`](https://developer.mozilla.org/en-US/docs/Web/API/Blob)
  - [`BufferSource`](#)
  - [`FormData`](https://developer.mozilla.org/en-US/docs/Web/API/FormData)
  - [`ReadableStream`](#)
  - [`URLSearchParams`](#)
  - [`USVString`](#)
- init : Object  -
  - `status`: The status code for the reponse, e.g., `200`.
  - `statusText`: The status message associated with the status code, e.g., `OK`.
  - `headers`: Any headers you want to add to your response, contained within a [`Headers`](https://developer.mozilla.org/en-US/docs/Web/API/Headers) object or object literal of [`ByteString`](https://developer.mozilla.org/en-US/docs/Web/API/ByteString) key/value pairs (see [HTTP headers](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers) for a reference).





## Response()
```
new Response(body, init)                        Response
```
创建一个新的Response 实例对象。

<table style='width:100%;'>
  <tr>
    <td>body </td>
    <td> 配置参数对象
      <ul><li>只读</li></ul>
    </td>
     <td> Object
      <ul>
        <li>[`Blob`](#)</li>
        <li>[`BufferSource`](#)</li>
        <li> [`FormData`](#)</li>
        <li>[`ReadableStream`](#)</li>
        <li>[`URLSearchParams`](#)</li>
        <li>[`USVString`](#)<li>
       </ul>
    </td>
     
  </tr>
</table>


