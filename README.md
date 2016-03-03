### js文件上传下载

说明:

readAsDataURL方法会使用base-64进行编码，编码的资料由data字串开始，后面跟随的是MIME type，然后再加上base64字串，逗号之后就是编码过的图像文件的内容。

大文件采用切割读取。

### 参考:

 * [使用FileReader对象的readAsDataURL方法来读取图像文件](http://blog.okbase.net/jquery2000/archive/1296.html)
 