Generate QR-code for current page's url.

try http://baidu.com.qr.ngx.so/

For quick access, add bookmark tool:

```
javascript:void(function(l,d){l.href=l.href.replace(/^https?:\/\/([^\/]+)/,'http://$1.'+d);})(location,'qr.ngx.so');
```
