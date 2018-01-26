# Response



- [构造函数]()
  - [Response()]()
- [属性]()
  - [body]()
  - bodyUsed

<br>


## 构造函数（Constructor）


### Response()
```
new Response(body, init)                                                        Response
```
创建一个新的Response 实例对象。
<table style='width:100%;'>
  <tr>
    <td >body </td>
    <td > 配置参数对象
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
  <tr>
    <td style='width:10%;'>init </td>
    <td style='width:60%;'> 配置参数对象
      <ul><li>只读</li></ul>
    </td>
     <td style='width:30%;'> Object
      <ul>
        <li><a href='#'>status</a>: number  -  The status code for the reponse, e.g., `200`.</li>
        <li><a href='#'>statusText</a>: string  - The status message associated with the status code, e.g., `OK`.</li>
       </ul>
    </td>
  </tr>
  
</table>


