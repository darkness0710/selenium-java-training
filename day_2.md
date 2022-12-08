# Selenium Locators
## What is Locator?
- Locator giúp phân biệt và tìm được các thẻ trong DOM của html. 
- Vậy DOM là gì? HTML là gì?
## What is HTML?
- HTML viết tắt của Hypertext Markup Language là ngôn ngữ lập trình dùng để xây dựng và cấu trúc lại các thành phần có trong Website.
## What is HTML DOM?
 ![image](https://user-images.githubusercontent.com/25264763/206472866-be5f8db8-c33b-4bc8-8cd2-e79ea8b411e7.png)

 HTML DOM là một chuẩn mô hình object và programming interface cho HTML. nó định nghĩa:
- HTML elements như là objects
- Properties của tất cả HTML elements
- Methods để truy cập đến tất cả HTML elements
- Events cho tất cả HTML elements
- HTML DOM là một tiêu chuẩn cho phép bạn thực hiện những công việc thao tác với bất kì một trang web: get, change, add, or delete các thành phần của HTML.

# Struct DOM
## Node
- Đối với HTML DOM, cấu trúc dạng cây gọi là DOM Tree có nghĩa là mọi thành phần đều được xem là 1 nút (node), được biểu diễn trên 1 cây. 
- Các phần tử khác nhau sẽ được phân loại nút khác nhau nhưng quan trọng nhất là 3 loại: nút gốc (document node), nút phần tử (element node), nút văn bản (text node).
- Node gốc: thường được biểu diễn bởi thẻ <html> là thành phần của HTML.
- Node phần tử: biểu thị cho 1 phần tử HTML.
- Node văn bản: mỗi đoạn kí tự trong tài liệu HTML, bên trong 1 thẻ HTML đều là 1 nút văn bản. Đó có thể là tên trang web trong thẻ <title>, tên đề mục trong thẻ <h1>
![image](https://user-images.githubusercontent.com/25264763/206475020-73568f4a-273a-4687-a111-890c2c2b0227.png)

## How To Access Elements in the DOM?
Giả sử chúng ta có một input như sau:
```
<input name="email" id="account-email" value="i_love_u@gmai.com" />
```
Chúng ta có thể sử dụng javascript để truy cập vào các nút của DOM theo các cách.

Cách 1:
```
document.getElementById('account-email');
```
Cách 2:
```
document.getElementsByName('email');
```
# 
