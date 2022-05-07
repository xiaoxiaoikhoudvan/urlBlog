# 浅析url

## 一、URL
URL 是 Web 中的一个核心概念。它是浏览器用来检索 web 上公布的任何资源的机制。

例子：http://www.example.com:80/path/to/myfile.html?key1=value1&key2=value2#SomewhereInTheDocument

1. http 是协议。它表明了浏览器必须使用何种协议。它通常都是HTTP协议或是HTTP协议的安全版，即HTTPS。Web需要它们二者之一，但浏览器也知道如何处理其他协议，比如mailto:（打开邮件客户端）或者 ftp:（处理文件传输），所以当你看到这些协议时，不必惊讶。
   
2. www.example.com 是域名。 它表明正在请求哪个Web服务器。或者，可以直接使用IP address, 但是因为它不太方便，所以它不经常在网络上使用。


3. :80 是端口。 它表示用于访问Web服务器上的资源的技术“门”。如果Web服务器使用HTTP协议的标准端口（HTTP为80，HTTPS为443）来授予其资源的访问权限，则通常会被忽略。否则是强制性的。


4. /path/to/myfile.html 是网络服务器上资源的路径。在Web的早期阶段，像这样的路径表示Web服务器上的物理文件位置。如今，它主要是由没有任何物理现实的Web服务器处理的抽象。


5. ?key1=value1&key2=value2 是提供给网络服务器的额外参数。 这些参数是用 & 符号分隔的键/值对列表。在返回资源之前，Web服务器可以使用这些参数来执行额外的操作。


6. #SomewhereInTheDocument 是资源本身的另一部分的锚点. 锚点表示资源中的一种“书签”，给浏览器显示位于该“加书签”位置的内容的方向。

## 二、DNS

DNS (Domain Name System) 域名系统，是一个层次化、分散化的Internet连接资源命名系统。DNS维护着一个包含域名与对应资源例如IP地址的列表。

DNS最突出的功能是将易于记忆的域名(例如mozilla.org)翻译成为数字化的IP地址(例如151.106.5.172)。这一从域名到IP地址的映射过程被称为DNS查询(DNS lookup)，与之对应，DNS反向查询(rDNS)用来找到与IP地址对应的域名。

## 三、IP

IP地址是分配给连接到使用Internet协议的网络的每个设备的一串数字

## 四、nslookup和ping

* nslookup + ip或者域名

* ping + ip或者域名

## 五、域名
域名是在 互联网 的网站的地址。域名被用于 URL 识别一个服务器属于哪个特定的网站。域名包含由句号点（”.“）分隔的名称（标签）的分级序列并以 扩展名 (en-US) 作为结尾。
