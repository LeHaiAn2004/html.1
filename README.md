# SmartSell - Ứng dụng mua sắm trực tuyến

## Giới thiệu

**SmartSell** là một ứng dụng web cho phép:

- Xem sản phẩm
- Tìm kiếm và lọc theo danh mục
- Đăng ký / Đăng nhập
- Đặt hàng
- Quản lý sản phẩm (dành cho admin)

**Công nghệ sử dụng:**

- **Frontend:** HTML, CSS, JavaScript  
- **Backend:** Node.js (giả lập tương tác với cơ sở dữ liệu MySQL)

## Yêu cầu hệ thống

- **Node.js:** Phiên bản 14.x hoặc cao hơn  
- **MySQL:** Phiên bản 5.7 hoặc cao hơn  
- **Trình duyệt:** Chrome, Firefox, Safari, hoặc Edge

## Hướng dẫn chạy ứng dụng trên PC

1. **Khởi tạo cơ sở dữ liệu:**

   Mở MySQL Workbench, chạy file `db.sql` để tạo database và các bảng dữ liệu cần thiết.

2. **Cấu hình kết nối MySQL:**

   Mở file `server.js` và thay đổi các thông tin kết nối phù hợp với:
   - Tên database của bạn
   - Tên người dùng và mật khẩu MySQL

   Ví dụ:
   ```javascript
   const connection = mysql.createConnection({
       host: 'localhost',
       user: 'root',
       password: 'your_mysql_password',
       database: 'your_database_name'
   });
3. **Chạy server Node.js:**
   - Mở Terminal
   - Di chuyển đến thư mục chứa project
   - Gõ lệnh: node server.js
4. **Truy cập ứng dụng**
   - Mở trình duyệt bất kỳ
   - Truy cập địa chỉ: http://localhost:3000
