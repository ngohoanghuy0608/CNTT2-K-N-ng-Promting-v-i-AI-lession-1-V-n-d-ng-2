### Bước 1: Chỉ ra thông tin nhạy cảm

Có 2 biến chứa thông tin mật:

-   `db_password`: Mật khẩu cơ sở dữ liệu.
    
-   `api_key`: Khóa API của Google Gemini.
    

### Bước 2: Làm sạch code

Thay thông tin thật bằng các giá trị tượng trưng:

```
def connect_database():    db_password = '[YOUR_DATABASE_PASSWORD]'    api_key = '[YOUR_API_KEY]'    print('Đang kết nối...')
```

### Bước 3: Viết prompt an toàn gửi AI

```
Tôi đang viết chương trình Python kết nối cơ sở dữ liệu.
Hãy kiểm tra và tối ưu đoạn code dưới đây.
Giải thích những lỗi có thể xảy ra và cách khắc phục.
Lưu ý: Không sử dụng hoặc yêu cầu thông tin mật như mật khẩu và API Key.
```


