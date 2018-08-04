<p align="center"><img src="https://laravel.com/assets/img/components/logo-laravel.svg"></p>

<p align="center">
  
  
# Hệ thống quản lý giờ giảng của giảng viên
## Framework 
  Laravel
## Ngôn ngữ
  HTML, CSS, JS, PHP
  
## Hệ quản trị 
  MySQL
## Run
  1. clone repository
  2. import database  file `manage_teaching_time.sql` trong folder vào cơ sở dữ liệu của mình
  3. Set Up Database Connection
    - Sửa cấu hình trong file .env.example và config/database.php
    - DB_DATABASE= tên database
    - DB_USERNAME=tên người dùng đc quyền truy cập database
    - DB_PASSWORD= mật khẩu người dùng được quyền truy cập database
  4. Setup the Key php artisan key:generate
  5. Run The Website php artisan serve
## Chức năng chính
1. Hệ thống quản lý giờ giảng của giảng viên chia thành 3 rules chính là admin, phòng đào tạo, giảng viên
2.Đăng nhập theo tài khoản được cấp trước, do trường đăng kí. Admin có thể đăng kí thêm
3. Chức năng chính gồm: 
    - Admin có toàn bộ quyền: Quản lý danh muc, quản lý dữ liệu, quản lý thống kê, quản lý user và quyền.
    - Phòng đào tạo:  Quản lý danh muc, quản lý dữ liệu, quản lý thống kê
    - Giảng viên: Xem thống kê
4. Đăng nhập  
- Đăng nhập hệ thống bằng tài khoản admin:  `tranvananuet@gmail.com` và mật khẩu: `123456` 
- Đăng nhập hệ thống bằng tài khoản phòng đào tạo `admindemo@gmail.com` va mật khẩu: `123456`
- Đăng nhập hệ thống bằng tài khoản giáo viên : `anhnv@vnu.edu.vn` và mật khẩu là `123456`
## Contacts
- Trong quá trình demo, có thể xảy ra lỗi, mong nhận được sự đóng góp nhiệt tình
- email : `tranvananuet@gmail.com`
