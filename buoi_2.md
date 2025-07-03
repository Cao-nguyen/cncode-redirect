<h1>BUỔI 2: CÁC THẺ CƠ BẢN CỦA HTML</h1>

**1. Vấn đề giấy chứng nhận**
- Giấy chứng nhận được cấp bởi **CNcode** và được ký tên bởi **Founder Lý Cao Nguyên**.
- Người học có thể thêm giấy chứng nhận vào CV để xin việc tại các doanh nghiệp.
- Giấy chứng nhận sẽ có **mã QR** để tra cứu thông tin về giấy chứng nhận và khoá đào tạo _(doanh nghiệp sẽ dựa vào đây để đánh giá năng lực của bạn)_.

**2. Những gì bạn có thể làm sau khoá học**
- Làm một **website cơ bản cho cá nhân**.
- Học nâng cao và có thể **làm đồ án thuê cho các bạn sinh viên**.
- Có thêm kỹ năng mới sẽ giúp **người khác nhìn nhận bạn khác đi**.

**3. HTML là gì?**
- HTML (HyperText Markup Language) là ngôn ngữ đánh dấu siêu văn bản, được sử dụng để tạo cấu trúc và nội dung cho các trang web và ứng dụng web.
- **Lưu ý:** HTML không phải là một ngôn ngữ lập trình.

**4. Các thẻ trong HTML**

**_a. Cấu trúc file HTML_**
- Trong Visual Studio Code các bạn chỉ cần gõ dấu `!` và `Enter` đoạn code bên dưới sẽ tự động hiện ra.
- Một file HTML có cấu trúc như sau:
```HTML
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
</head>
<body>
  
</body>
</html>
```

**_b. Cài extendsion cần thiết_**
Các bạn lên mạng và gõ `Cách cài extendsion Live Server` để xem hướng dẫn có thể chạy được một file HTML trên Visual Studio Code nhé!

**_c. Thẻ html_**
- Thẻ html là thẻ lớn nhất bao bộc các thẻ con.
```HTML
<html> </html>
```

**d. Thẻ head & thẻ body**
- Thẻ head là thẻ để định dạng một số thuộc tính cho trang websie, gắn đường dẫn tới file CSS hoặc JS _(trong thực tế người ta thường đặt file JS ở cuối thẻ body)_
```HTML
<head>
  <!-- Thẻ title bên dưới dùng để hiển thị tiêu đề website nằm ở trên tab của trình duyệt website -->
  <title>Lý Cao Nguyên</title>
</head>
```

- Thẻ body là thẻ bao các phần hiển thị trên website của chúng ta. Mọi code tạo ra các thành phần của website đều nằm trong body.
```HTML
<body></body>
```

**_e. Thẻ h & thẻ p và thẻ span_**
- Thẻ h sẽ bao gồm từ h1 đến h1, dùng làm tiêu đề. h1 là lớn nhất và nhỏ dần nhất đến h6.
```HTML
<h1>Lý Cao Nguyên</h1>
<h2>Lý Cao Nguyên</h2>
<h3>Lý Cao Nguyên</h3>
<h4>Lý Cao Nguyên</h4>
<h5>Lý Cao Nguyên</h5>
<h6>Lý Cao Nguyên</h6>
```
- Kết quả hiển thị: 
<h1>Lý Cao Nguyên</h1>
<h2>Lý Cao Nguyên</h2>
<h3>Lý Cao Nguyên</h3>
<h4>Lý Cao Nguyên</h4>
<h5>Lý Cao Nguyên</h5>
<h6>Lý Cao Nguyên</h6>

- Thẻ p và thẻ span sẽ là những thẻ dùng để hiển thị nội dung nào đó dưới dạng đoạn.
```HTML
<p>“Gia Đình Haha” được thực hiện dựa trên sự kế thừa những dấu ấn tuyệt đẹp từ 'Gia Tộc Toàn Năng Anh Tài - Chị Đẹp'. Bởi vậy, YeaH1 cam kết sẽ mang tới cho khán giả một chương trình tích cực,  một lời tri ân sâu sắc, những kết nối có giá trị tới vùng đất chương trình đi qua. Đây cũng là cách YeaH1 đáp đền những tình cảm yêu thương mà quý khán giả đã dành tặng cho mình trong thời gian qua.</p>

<span>“Gia Đình Haha” được thực hiện dựa trên sự kế thừa những dấu ấn tuyệt đẹp từ 'Gia Tộc Toàn Năng Anh Tài - Chị Đẹp'. Bởi vậy, YeaH1 cam kết sẽ mang tới cho khán giả một chương trình tích cực,  một lời tri ân sâu sắc, những kết nối có giá trị tới vùng đất chương trình đi qua. Đây cũng là cách YeaH1 đáp đền những tình cảm yêu thương mà quý khán giả đã dành tặng cho mình trong thời gian qua.</span>
```
- Kết quả hiển thị:
<p>“Gia Đình Haha” được thực hiện dựa trên sự kế thừa những dấu ấn tuyệt đẹp từ 'Gia Tộc Toàn Năng Anh Tài - Chị Đẹp'. Bởi vậy, YeaH1 cam kết sẽ mang tới cho khán giả một chương trình tích cực,  một lời tri ân sâu sắc, những kết nối có giá trị tới vùng đất chương trình đi qua. Đây cũng là cách YeaH1 đáp đền những tình cảm yêu thương mà quý khán giả đã dành tặng cho mình trong thời gian qua.</p>

<span>“Gia Đình Haha” được thực hiện dựa trên sự kế thừa những dấu ấn tuyệt đẹp từ 'Gia Tộc Toàn Năng Anh Tài - Chị Đẹp'. Bởi vậy, YeaH1 cam kết sẽ mang tới cho khán giả một chương trình tích cực,  một lời tri ân sâu sắc, những kết nối có giá trị tới vùng đất chương trình đi qua. Đây cũng là cách YeaH1 đáp đền những tình cảm yêu thương mà quý khán giả đã dành tặng cho mình trong thời gian qua.</span>

**_f. Thẻ div_**
Thẻ div là thẻ có chiều rộng theo nội dung nó chứa, chiều ngang từ trái qua phải chiếm hết chiều ngang màn hình
```HTML
<div></div>
```

**_g. Thẻ img, thẻ a_**
- Thẻ img là thẻ dùng hiển thị hình ảnh
- Cú pháp:
```HTML
<img src="đường dẫn của ảnh"></img>
```
- Ví dụ:
```HTML
<img src="https://media.discordapp.net/attachments/1387301331227902104/1389816861805252639/CNgroup.png?ex=686750d1&is=6865ff51&hm=899ec1867d0585ddba063b7b62263a048b443578a7ab2220a2b43e613477fe96&=&format=webp&quality=lossless&width=625&height=625"></img>
```
- Kết quả hiển thị:
<img src="https://media.discordapp.net/attachments/1387301331227902104/1389816861805252639/CNgroup.png?ex=686750d1&is=6865ff51&hm=899ec1867d0585ddba063b7b62263a048b443578a7ab2220a2b43e613477fe96&=&format=webp&quality=lossless&width=625&height=625"></img>

- Thẻ a là thẻ link dùng để chuyển hướng người dùng đến nơi khác.
- Cú pháp:
```HTML
<a href="<đường link>" target="_blank">Nội dung muốn hiện</a>
```
- Ví dụ:
```HTML
<a href="https://zalo.me/0394217863" target="_blank">Zalo Lý Cao Nguyên</a>
```
- Kết quả:
<a href="https://zalo.me/0394217863" target="_blank">Zalo Lý Cao Nguyên</a>

> Bạn hãy thử xem điểm khác nhau của việc có `target="_blank"` và không có nhé!
>
> Có: <a href="https://zalo.me/0394217863" target="_blank">Zalo Lý Cao Nguyên</a>
>
> Không: <a href="https://zalo.me/0394217863">Zalo Lý Cao Nguyên</a>
