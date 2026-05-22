# KIỂM TRA CUỐI KHÓA CODEBASE - PYTHON

## 📋 Yêu cầu

1. **IDE hoặc notebook:** Google Colab hoặc các local IDE (VSCode,PyCharm,...). Không dùng các IDE online vì bị giới hạn một số tính năng cho bài kiểm tra này
2. **Đã cài Git và đăng nhập Github** 
3. **Tải các thư viện cần thiết:** Nếu chưa cài đặt các thư viện trong file `requirements.txt` thì chạy lệnh sau trong terminal:
```
pip install -r requirements.txt
```
4. **Extension cần thiết:** `
- `vscode-pdf`: để hiển thị file `.pdf` trong IDE
- `Jupyter`
- `Python`

## 📁 Cấu trúc thư mục

```
template_cuoi_khoa_py/
├── README.md                                    
├── c3_input.csv                                # Dữ liệu đầu vào cho câu 3
├── requirements.txt                            # Các thư viện cần thiết
└── Đề_kiểm_tra_cuối_khóa_Python_2026.pdf       # Đề bài kiểm tra chính thức
```

## 📄 Giải thích các file

### README.md
File tài liệu này. Cung cấp thông tin tổng quát về repository và hướng dẫn sử dụng.

### c3_input.csv
- **Loại dữ liệu:** Tệp CSV (Comma-Separated Values)
- **Nội dung:** Dữ liệu mẫu đầu vào cho câu 3 của bài kiểm tra
- **Mục đích:** Để test và thử nghiệm chạy kết quả cho câu 3. Không nhất thiết phải sử dụng
- **Cách sử dụng:** Đọc file này trong code Python để xử lý dữ liệu theo yêu cầu của đề bài

### Đề_kiểm_tra_cuối_khóa_Python_2026.pdf
- **Loại tệp:** Tài liệu PDF
- **Mục đích:** Đề bài kiểm tra chính thức cuối khóa Python 2026
- **Nội dung:** Liệt kê các câu hỏi và yêu cầu cần hoàn thành cho bài kiểm tra
- **Cách sử dụng:** Tham khảo đề bài này để hiểu rõ các yêu cầu từng câu

### requirements.txt
- **Nội dung:** Các thư viện cần cài
- File này chỉ chứa các thư viện cần thiết và được ứng dụng thường xuyên nên có thể cài global luôn, không nhất thiết phải tạo môi trường ảo (`.venv`)

## 🚀 Hướng dẫn sử dụng

1. **Đọc đề bài:** Tải và xem file `Đề_kiểm_tra_cuối_khóa_Python_2026.pdf` để hiểu rõ các yêu cầu
2. **Kiểm tra repository:** Kiểm tra xem có file nào trong repository bị thiếu/lỗi so với mô tả trong file README này không
3. **Viết code:** Tạo file Python (`.py`) hoặc file Jupyter notebook (`.ipynb`) để giải các bài toán theo đề bài. Có thể thực hiện tất cả các bài vào cùng một file hoặc nhiều file tùy ý.
4. **Nháp** (optional): Tạo file `.gitignore` và điền từng dòng chính xác tên các file không muốn push lên Github (giống file `requirements.txt`). Dùng khi muốn tạo một số file để nháp hoặc thử nghiệm nhưng không muốn push lên Github chính thức.
5. **Kiểm tra:** Chắc chắn rằng code của bạn hoạt động đúng
6. **Nộp bài:** Đảm bảo đã push phiên bản commit cuối cùng lên Github. Kiểm tra trên Github xem đã update các file cần nộp phiên bản cuối hay chưa

## 💡 Lưu ý

- Đảm bảo cài đặt các thư viện Python và Extension cần thiết trước khi chạy code.
- **Nghiêm túc tuân thủ quy định kiểm tra**. Mọi vi phạm sẽ được tính là không đủ điều kiện hoàn thành khóa và sẽ không được tham gia các khóa học khác của CLB NITC.
- Người trông thi sẽ ghi lại thời điểm checkout của từng học viên. Mọi commit và thay đổi sau thời điểm checkout đó sẽ không được người chấm thi cập nhật.

## 📞 Liên hệ

Mọi thắc mắc nào khác vui lòng hỏi người trông thi.
