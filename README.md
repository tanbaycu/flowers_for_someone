# Hướng dẫn Cài đặt và Sử dụng Dự án trên 💜🌼
Author: tanbaycu⭕
## Mục lục
- [1. Cài đặt Công cụ Cần thiết](#1-cài-đặt-công-cụ-cần-thiết)
- [2. Tải và Cài đặt Dự án](#2-tải-và-cài-đặt-dự-án)
- [3. Mở và Chạy Dự án trong VSCode](#3-mở-và-chạy-dự-án-trong-vscode)
- [4. Cấu trúc Dự án](#4-cấu-trúc-dự-án)

## 1. Cài đặt Công cụ Cần thiết

### 1.1 Cài đặt Git - [Hướng dẫn ở đây ạ](https://funix.edu.vn/chia-se-kien-thuc/cai-dat-git-va-git-bash-windows/)
1. Truy cập [https://git-scm.com/download/win](https://git-scm.com/download/win)
2. Tải bản cài đặt Git cho Windows
3. Vào phần Tệp đã tải xuống Click chọn vào Git vừa tải về -> Allow để cài đặt 
4. Chạy file cài đặt và làm theo hướng dẫn (để mặc định các tùy chọn nếu bạn không chắc chắn)
5. Sau khi cài đặt, sử dụng tổ hợp phím Window + X ấn chọn Terminal và gõ `git --version` để kiểm tra

### 1.2 Cài đặt VSCode
1. Truy cập [https://code.visualstudio.com/](https://code.visualstudio.com/)
2. Tải phiên bản dành cho Windows
3. Chạy file cài đặt và làm theo hướng dẫn
4. Khởi động VSCode sau khi cài đặt hoàn tất

### 1.3 Cài đặt Extensions cho VSCode
1. Mở VSCode
2. Nhấn Ctrl+Shift+X để mở Extensions
3. Tìm và cài đặt các extensions sau:
   - Live Server
   - HTML CSS Support

## 2. Tải và Cài đặt Dự án

1. Sử dụng tổ hợp phím Window + X tiếp tục chọn Terminal và làm theo bước thứ 2
2. Clone dự án bằng lệnh:

```python
git clone https://github.com/tanbaycu/flowers_for_someone.git
```
3. Đợi quá trình clone hoàn tất

## 3. Mở và Chạy Dự án trong VSCode

1. Mở VSCode
2. Chọn File > Open Folder
3. Tìm và chọn thư mục 'flowers_for_someone' vừa clone
4. Trong VSCode, mở file 'index.html'
5. Click chuột phải vào file 'index.html' trong VSCode
6. Chọn 'Open with Live Server'
7. Trình duyệt sẽ tự động mở và hiển thị trang web

## 4. Cấu trúc Dự án
```
flowers_for_someone/
├── README.md
├── css/
│   ├── index.css
│   └── style.css
├── flower.html
├── images/
│   └── gift.png
├── index.html
├── js/
│   ├── index.js
│   └── main.js
├── scss/
│   └── style.scss
└── style.css.map
```

### Mô tả các thành phần chính
- `index.html`: Trang chủ của dự án
- `flower.html`: Trang hiển thị hoa
- `css/`: Thư mục chứa các file CSS để định dạng trang web
- `js/`: Thư mục chứa các file JavaScript để xử lý logic
- `images/`: Thư mục chứa hình ảnh sử dụng trong dự án
- `scss/`: Thư mục chứa file SCSS (Sass) để tạo style

## Chỉnh sửa Dự án
- Để chỉnh sửa nội dung, mở các file .html trong VSCode
- Để thay đổi style, chỉnh sửa các file trong thư mục css/
- Để thêm chức năng, làm việc với các file trong thư mục js/

## Hỗ trợ 


tanbaycu luôn luôn sẵn sàng đồng hành cùng bạn, có thắc mắc cứ nhắn cho tui nhé😺


