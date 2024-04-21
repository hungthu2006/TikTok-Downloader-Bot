
**Obfuscation Đổi tên biến, hàm và mã định danh để làm cho mã khó đọc hơn.
Mục đích là để che giấu logic và ngăn chặn việc đảo ngược mã nguồn.**
```javascript
function o() { var l = "Hello, World!"; console.log(l); } o();
```


**Minification Loại bỏ khoảng trắng, dòng mới và nhận xét.
Giảm kích thước của mã, giúp tải trang nhanh hơn.**
```javascript
function greet(){console.log("Hello, World!");}greet();
```


**Encoding Chuyển đổi mã thành một định dạng khác, như Base64, để che giấu nội dung thực sự.
Thường được sử dụng để chuyển dữ liệu qua mạng.**
```javascript
eval(atob("ZnVuY3Rpb24gZ3JlZXQoKSB7IGNvbnNvbGUubG9nKCJIZWxsbywgV29ybGQhIik7IH0gZ3JlZXQoKTs="));
```


**Encryption Mã hóa mã nguồn để chỉ có thể giải mã bằng một khóa bí mật.
Đảm bảo an ninh dữ liệu, ngăn chặn truy cập không được phép.**
```javascript
var encrypted = "72f82a..."; 
function decrypt(code) { return atob(code); }
console.log(decrypt(encrypted));
```
 
**Closure Compiler Công cụ của Google để tối ưu hóa và minify JavaScript.
Cải thiện hiệu suất và giảm kích thước của mã.**
```javascript
alert("Hello,World");
```


**Browserify Cho phép sử dụng require('modules') trong trình duyệt.
Cung cấp một số cấp độ mã hóa và quản lý phụ thuộc.**
```
var unique = require('uniq');
var data = [1, 2, 2, 3, 4, 5, 5, 5, 6];
console.log(unique(data));

```


**UglifyJS Công cụ để minify và obfuscate mã JavaScript.
Giúp giảm kích thước và tăng cường bảo mật cho mã JavaScript.**
```javascript
!function(){console.log("Hello, World!")}();
```


