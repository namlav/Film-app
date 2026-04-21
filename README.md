# Movie Streaming Application

Ứng dụng crawl phim từ nguồn phim và xem phim được phát triển bằng Python, cho phép người dùng xem, quản lý các bộ phim và người dùng.

## Tính năng

- Giao diện người dùng thân thiện với tkinter
- Quản lý người dùng (đăng ký, đăng nhập)
- Phân quyền người dùng (admin/user)
- CRUD (Create, Read tài khoản, phim (user/admin), Update, Delete phim (admin))
- Crawl dữ liệu phim từ Mọt Phim
- Lưu trữ dữ liệu bằng JSON
- Tải và hiển thị poster phim

## Yêu cầu hệ thống

- Python 3.7 trở lên
- Các thư viện Python:
  - tkinter
  - requests
  - beautifulsoup4
  - pillow
  - pyinstaller
  - re
  - os
  - json

## Cài đặt

1. Clone repository:
```bash
git clone https://github.com/namlav/Film-app.git
```

2. Cài đặt các thư viện cần thiết:
```bash
pip install -r requirements.txt
```

## Sử dụng

1. Chạy ứng dụng:
```bash
python main.py
```

2. Đăng ký tài khoản mới hoặc đăng nhập với tài khoản hiện có

3. Sử dụng các chức năng:
   - User/Admin:
     - Xem danh sách phim
     - Tìm kiếm phim
   - Adminitrator only:
     - Thêm phim mới
     - Chỉnh sửa thông tin phim
     - Xóa phim

## Đóng gói ứng dụng

Để tạo file thực thi:
```bash
pyinstaller --onefile --windowed main.py
```

File thực thi sẽ được tạo trong thư mục `dist/`

## Cấu trúc thư mục

```
movie-app/
├── data/
│   ├── movies.json
│   └── users.json
├── images/
│   └── [poster files]
├── main.py
├── movie_crawler.py
├── requirements.txt
└── README.md
```

## Lưu ý

- Đảm bảo có kết nối internet để sử dụng chức năng crawl dữ liệu
- Dữ liệu được lưu trữ cục bộ trong thư mục `data/`
- Hình ảnh poster được lưu trong thư mục `images/`

## 🤝 Đóng góp

Contributions are welcome! Vui lòng:

1. Fork repository
2. Tạo feature branch
3. Commit changes
4. Push và tạo Pull Request

## 📝 License

MIT License

## 👨‍💻 Tác giả

Nam Lav

## 📞 Liên hệ

Nếu có câu hỏi hoặc vấn đề, vui lòng tạo issue trên GitHub.

---

**Happy Coding! 🚀**
