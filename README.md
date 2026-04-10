<img width="2560" height="251" alt="image" src="https://github.com/user-attachments/assets/d30e6850-6ee3-4593-95a4-3008b0b9716f" />
我要学习Ajax启动<br>
想要使用axios函数库需要先使用<script src="https://cdn.jsdelivr.net/npm/axios/dist/axios.min.js"></script>来进行导入<br>
后面使用.then(result =>{<br>
})<br>
ajax浏览器和服务器之间通信连接，动态数据交互<br>
<h3>认识url</h3><br>
url叫统一资源定位符<br>
http协议：超文本传输协议，规定浏览器和服务器之间传输数据的格式<br>
域名：标记服务器在互联网中的方向<br>
资源路径：标记资源在服务器下的具体位置<br>
<h3>查询参数</h3><br>
定义浏览器提供给服务器的额外信息,让服务器返回浏览器想要数据<br>
语法:http://域名//xx//xx?参数名1=值1&参数名2=值2<br>
axios语法axios提供的params选项<br>
axios在运行时候把参数名和值,会拼接到url>参数名=值<br>
 <h3>常见请求方法</h3><br>
 get获取数据<br>
 post提交数据<br>
 put修改数据(全部)<br>
 delete删除数据<br>
 patch修改数据<br>
 method:请求的方法,get可以省略<br>
 data:提交数据<br>
 <img width="905" height="816" alt="image" src="https://github.com/user-attachments/assets/2694c624-6201-4c75-bcc2-c98e02859002" /><br>
 <h3>axios核心配置</h3><br>
 url:请求URL网址<br>
 method：请求方法，get可以省略（不区分大小写）//method:`方法`<br>
 params：查询参数<br>
 date：查询参数<br>
 <h3>http协议请求报文</h3><br>
 http协议规定了服务器发送以及服务器返回的格式<br>
 请求报文:浏览器按照http协议要求格式,发送给服务器内容<br>
 <img width="1758" height="857" alt="image" src="https://github.com/user-attachments/assets/4fc2f740-bb85-4e5b-831d-8b7781f0b3cf" /><br>
 <h3>http状态响应码</h3><br>
 2成功，4开头客户端错误，5服务端错误<br>
 相应行（）：协议http响应状态码，状态信息<br>
 相应头：以键值对的格式携带的附加信息，比如content-type<br>
 空行：分隔响应头，空行之后的是返回浏览器的资源<br>
 响应体，返回的资源<br>
<h3>接口文档</h3><br>
接口文档：描述接口的文章<br>
接口：使用Ajax和服务器通讯时候，使用的url，请求方法，以及参数<br>
bootstrap的modal弹框:添加modal类名（默认隐藏）


