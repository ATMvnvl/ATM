Giới thiệu
> Tài liệu được viết tay bởi [ATM] (https://github.com/ATMvnvl/ATM), để giúp bạn có thêm hiểu biết và làm chủ về Markdown.

## I. Git
### 1. Đăng ký tài khoản Github (https://github.com/) 
Điền thông tin cơ bản 
- Email Address
- Password
- Username 
- Verify Account 

Xác minh qua email 

### 2. Tạo repository 
Đăng nhập bằng tài khoản mới tạo link: https://github.com/

Thông tin đăng ký repository

![alt text](code1.png)


### 3. Sử dụng git - github
Link download Git: https://git-scm.com/downloads

Tải xong và chạy lên 

Kiểm tra version mở CMD windows nhập: git --version 

![alt text](<code 2.png>)

Một số lệnh cơ bản dùng git 

- git --v: Kiểm tra phiên bản
- git config: Cấu hình các biến chung
- git help: Hướng dẫn sử dụng git
- git mkdir: Tạo repository trong hệ thống local
- git remote: Liên kết đến remote repository (local & github)
- git init: Khởi tạo git trong thư mục 
- git status: Kiểm tra trạng thái của kho lưu trữ
- git add: Những thay đổi để chuẩn bị commit 
- git commit: Ghi lại các các thay đổi vào kho lưu trữ
- git push: Đẩy lên repository 
- git branch: Kiểm tra các nhánh hiện tại
- git checkout: Lệnh di chuyển không gian làm việc 

## II. Markdown 
Đã có ai dùng `GitHub` bao lâu nay vẫn không biết các tệp với đuôi mở rộng .md là gì không?

`Markdown` là ngôn ngữ đánh dấu có cú pháp khá đơn giản và dễ hiểu, tạo thuận tiện cho việc chuyển đổi từ văn bản thuần sang `HTML`.

Thay vì dựa vào `HTML`, `Markdown` cho phép bạn định dạng văn bản mà trực quan hơn nhiều so với `HTML`.

Cách sử dụng Markdown

### 1. Văn bản thuần
#### 1.1 Tiêu đề - Heading

Bạn có thể viết loại tiêu đề `<h1>, <h2>,... <h6>` bằng cách thêm các dấu # tương ứng vào đầu dòng.

Một dấu # tương đương với `<h1>`, hai dấu # tương đương với `<h2>` ...

Cú pháp:
```
# Vina 1
## Vina 2
### Vina 3
...
```
Kết quả:

# Vina 1
## Vina 2
### Vina 3


#### 1.2 Đoạn văn - Paragraph

Để xuống dòng giữa các văn bản `<p>`, sử dụng một dòng trống để tách các dòng văn bản.

Cú pháp:
```
Đây là Vina 1

Đây là Vina 2

Đây là Vina 3

```
Kết quả:

Đây là Vina 1

Đây là Vina 2

Đây là Vina 3


#### 1.3 Chữ in nghiêng - Italic

Để in nghiêng văn bản `<i>`, thêm một dấu * hoặc dấu _ trước và sau từ cần in nghiêng.

Cú pháp:
```
*Từ cần in nghiêng Vina 1*

```
Kết quả:

*Từ cần in nghiêng Vina 1*


#### 1.4 Chữ in đậm - Bold

Để in đậm văn bản `<b>`, thêm hai dấu * hoặc dấu _ trước và sau từ cần in đậm.

Cú pháp:
```
**Từ cần in đậm Vina 1**

```
Kết quả:

**Từ cần in đậm Vina 1**


#### 1.5 Chữ gạch giữa - Strikethrough

Để tạo chữ gạch giữa, thêm 2 dấu ~ trước và sau từ đó.

Cú pháp:
```
~~Vina~~
```
Kết quả:

~~Vina~~

#### 1.6 Chữ gạch giữa - Strikethrough

### 2. Các khối
#### 2.1 Trích dẫn - Blockquote

Để tạo một `<blockquote>`, thêm dấu > vào trước mỗi dòng trích dẫn.

Cú pháp:
```
> Trích dẫn dòng Vina 1
```
Kết quả:

> Trích dẫn dòng Vina 1

#### 2.2 Danh sách có thứ tự - Ordered List

Để tạo danh sách `<ol><li>`, bạn chỉ cần thêm các số, dấu chấm trước nội dung (dùng tab để phân cấp)

Cú pháp:
```
1. Vina 1
2. Vina 2
```
Kết quả:

1. Vina 1
2. Vina 2

#### 2.3 Danh sách không có thứ tự - Unordered List

Để tạo danh sách `<ul><li>`, bạn chỉ cần thêm dấu * hoặc - hoặc + trước nội dung (dùng tab để phân cấp)

Cú pháp:
```
- Vina 1
- Vina 2
```
Kết quả:

- Vina 1
- Vina 2

#### 2.4 Khối lệnh - Block Code

Để viết 1 đoạn `<code>`, bạn dùng 3 dấu ` ở trước và sau đoạn đó (có thể thêm format ngôn ngữ đó).

Cú pháp:

![alt text](code.png)

Kết quả:

```python
print("Hello Vina ATM")
```

#### 2.5 Bảng - Table

Để tạo bảng `<table><tbody><tr><th><th>`, bạn chỉ cần ngăn cách bởi dấu | và cách đầu bảng với thân bảng bằng :--- (số dấu - tuỳ ý)

Cú pháp:
```
| Cột 1 | Cột 2 | Cột 3 | Cột 4 |
| :--- | :--- | :--- | :--- |
| V | I | N | A |
| 2 | 0 | 0 | 8 |
| 2 | 0 | 2 | 4 |
```
Kết quả

| Cột 1 | Cột 2 | Cột 3 | Cột 4 |
| :--- | :--- | :--- | :--- |
| V | I | N | A |
| 2 | 0 | 0 | 8 |
| 2 | 0 | 2 | 4 |


### 3. Khác 
#### 3.1 Đường kẻ ngang - Horizonal rules

Để tạo đường kẻ ngang, sử dụng ba dấu * hoặc - hoặc _ trên một dòng.

Cú pháp:
```
---
***
___
```
Kết quả:

---
***
___


#### 3.2 Liên kết - Link

Để chèn trực tiếp, có thể paste thẳng nó như bình thường.

Để dẫn liên kết `<a href="https://github.com">Github</a>`, ATM`[text](link)`.

Cú pháp:
```
Trực tiếp: https://github.com/ATMvnvl/ATM

Gián tiếp: [Github](https://github.com/ATMvnvl/ATM)
```
Kết quả:

Trực tiếp: https://github.com/ATMvnvl/ATM

Gián tiếp: [Github](https://github.com/ATMvnvl/ATM)

#### 3.3 Hình ảnh - Image

Để chèn trực tiếp, có thể paste thẳng nó như bình thường.

Để đường dẫn ảnh `<img src="Path ảnh alt="Github">`, đến `![text](link ảnh)`.

Hoặc `![](link ảnh)` nếu không cần chữ khi hover.

Cú pháp:
```
![](https://media.licdn.com/dms/image/D5612AQG9kfU-VRRa1w/article-cover_image-shrink_720_1280/0/1720517893883?e=2147483647&v=beta&t=Yc5XPIAuZcomD5GL5iqofnWKhr4cZ2ROFzExA9VdoBo1)
```
Kết quả:

![](https://media.licdn.com/dms/image/D5612AQG9kfU-VRRa1w/article-cover_image-shrink_720_1280/0/1720517893883?e=2147483647&v=beta&t=Yc5XPIAuZcomD5GL5iqofnWKhr4cZ2ROFzExA9VdoBo)


#### 3.4 Biểu tượng cảm xúc - Icon

Phần này tuỳ vào nền tảng (Github, Discord, ...) có icon đó không ghi dấu : và tên icon.



Cú pháp:

![alt text](image-2.png)

Kết quả:

🏧


#### 3.5 Checkbox

Để chèn `checkbox/checked` (thường dùng cho to do list trên github) thì ta đánh dấu như list và thêm 1 cặp ngoặc vuông.

Cú pháp:

```
- [ ] Checkbox Vina
- [x] Checked Vina
```

Kết quả:

- [ ] Checkbox Vina 
- [x] Checked Vina


#### 3.6 Escape markdown

Đôi khi những kí hiệu trùng với cú pháp của markdown. Để phân biệt, bạn chỉ cần thêm dấu \ trước những kí hiệu đó là được.

Cú pháp:
```
\`hai dấu nháy Vina\`

\*\*\*ba dấu sao hai bên Vina\*\*\*
``` 
Kết quả:

\`hai dấu nháy Vina\`

\*\*\*ba dấu sao hai bên Vina \*\*\*

<p style="text-align:center; color:green; font-weight:bold; text-decoration:underline;">
  💪Hacking Fun ATM 2024💪
</p>

