
# FASHION STORE MANAGEMENT SYSTEM
# HỆ THỐNG QUẢN LÝ CỬA HÀNG THỜI TRANG

## 1. Giới thiệu dự án

- **Tên đề tài:** Xây dựng hệ thống quản lý cửa hàng thời trang- Fashion Store Management System.
- **Mô tả:** Xây dựng website hỗ trợ quản lý hoạt động kinh doanh cửa hàng thời trang, kết hợp quản lý nội bộ và bán hàng trực tuyến cho khách hàng.
- **Đối tượng sử dụng:** Quản trị viên, nhân viên và khách hàng.
- **Môn học:** Phát triển ứng dụng Web mã nguồn mở.
- **Nhóm thực hiện:** Nguyễn Bùi Thiếu Gia_Hồ Tuấn Hưng_Nguyễn Thành Triệu.

## 🛠️ Technologies Used

### Backend
![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![CodeIgniter](https://img.shields.io/badge/CodeIgniter%204-EF4223?style=for-the-badge&logo=codeigniter&logoColor=white)
![Composer](https://img.shields.io/badge/Composer-885630?style=for-the-badge&logo=composer&logoColor=white)

### Frontend
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Bootstrap](https://img.shields.io/badge/Bootstrap%205-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)

### Database
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

### DevOps & Tools
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)

## 2. Thành viên thực hiện

| STT | Họ và tên | Mã số sinh viên | Mã lớp |
|---|---|---|---|
| 1 | Nguyễn Bùi Thiếu Gia | 110123010 | DA23TTA |
| 2 | Hồ Tuấn Hưng | 110123109 | DA23TTC |
| 3 | Nguyễn Thành Triệu | 110122248 | DA23TTD |

## 3. Phân công công việc

Dự án được thực hiện bởi nhóm gồm 3 thành viên. Công việc được phân chia theo từng nhóm chức năng của hệ thống. Mỗi thành viên đều tham gia phân tích, thiết kế giao diện, lập trình Backend, xử lý cơ sở dữ liệu và kiểm thử chức năng được giao.

### 3.1. Nguyễn Bùi Thiếu Gia – Quản lý sản phẩm và kho hàng

**Các chức năng phụ trách:**
- Quản lý danh mục sản phẩm.
- Thêm, sửa, xóa và xem thông tin sản phẩm.
- Quản lý kích thước (Size), màu sắc và biến thể sản phẩm.
- Quản lý nhà cung cấp.
- Quản lý nhập hàng và tồn kho.
- Cảnh báo sản phẩm sắp hết hàng.

**Công việc thực hiện:**
- Thiết kế giao diện quản lý sản phẩm và kho hàng.
- Xây dựng Controller, Model và xử lý nghiệp vụ liên quan.
- Thiết kế và thao tác các bảng cơ sở dữ liệu về sản phẩm, danh mục, size, màu sắc, nhà cung cấp và nhập kho.
- Kiểm thử các chức năng quản lý sản phẩm và tồn kho.

### 3.2. Hồ Tuấn Hưng – Quản lý khách hàng và bán hàng trực tuyến

**Các chức năng phụ trách:**
- Đăng ký, đăng nhập và đăng xuất.
- Quản lý thông tin tài khoản khách hàng.
- Hiển thị danh sách và chi tiết sản phẩm.
- Tìm kiếm và lọc sản phẩm.
- Quản lý giỏ hàng.
- Đặt hàng và xem lịch sử mua hàng.

**Công việc thực hiện:**
- Thiết kế giao diện trang chủ và các trang mua sắm dành cho khách hàng.
- Xây dựng Controller, Model và xử lý nghiệp vụ tài khoản, giỏ hàng và đặt hàng.
- Thiết kế và thao tác các bảng cơ sở dữ liệu về người dùng, khách hàng, giỏ hàng và địa chỉ.
- Kiểm thử các chức năng đăng nhập, mua hàng và đặt hàng.

### 3.3. Nguyễn Thành Triệu – Quản lý đơn hàng và hoạt động kinh doanh

**Các chức năng phụ trách:**
- Quản lý đơn hàng.
- Xác nhận và cập nhật trạng thái đơn hàng.
- Quản lý thanh toán.
- Quản lý chương trình khuyến mãi.
- Thống kê doanh thu.
- Thống kê sản phẩm bán chạy và tình hình kinh doanh.

**Công việc thực hiện:**
- Thiết kế giao diện quản lý đơn hàng, thanh toán, khuyến mãi và thống kê.
- Xây dựng Controller, Model và xử lý nghiệp vụ liên quan.
- Thiết kế và thao tác các bảng cơ sở dữ liệu về đơn hàng, chi tiết đơn hàng, thanh toán và khuyến mãi.
- Kiểm thử quy trình xử lý đơn hàng, thanh toán và thống kê.

### 3.4. Công việc chung

Ngoài các nhiệm vụ được phân công riêng, các thành viên cùng phối hợp thực hiện:

- Khảo sát và phân tích yêu cầu hệ thống.
- Xây dựng sơ đồ Use Case, sơ đồ ERD và kiến trúc tổng thể.
- Thống nhất cấu trúc dự án và quy tắc thiết kế cơ sở dữ liệu.
- Sử dụng Git và GitHub để quản lý mã nguồn.
- Sử dụng Docker và Docker Compose để xây dựng môi trường triển khai.
- Tích hợp và kiểm thử toàn bộ hệ thống.
- Hoàn thiện báo cáo và chuẩn bị thuyết trình.

### 3.5. Bảng tổng hợp phân công

| Nội dung công việc | Thành viên 1 | Thành viên 2 | Thành viên 3 |
|---|:---:|:---:|:---:|
| Phân tích yêu cầu | ✓ | ✓ | ✓ |
| Thiết kế cơ sở dữ liệu | ✓ | ✓ | ✓ |
| Thiết kế giao diện | ✓ | ✓ | ✓ |
| Lập trình Backend | ✓ | ✓ | ✓ |
| Lập trình Frontend | ✓ | ✓ | ✓ |
| Kiểm thử chức năng | ✓ | ✓ | ✓ |
| Tích hợp hệ thống | ✓ | ✓ | ✓ |
| Viết báo cáo | ✓ | ✓ | ✓ |

**Nguyên tắc phối hợp:** Mỗi thành viên chịu trách nhiệm chính đối với nhóm chức năng được giao, đồng thời phối hợp với các thành viên khác để bảo đảm dữ liệu và quy trình nghiệp vụ được thống nhất trong toàn hệ thống.

## 4. Công nghệ sử dụng

### Backend
- PHP
- CodeIgniter 4
- Composer

### Frontend
- HTML5
- CSS3
- Bootstrap 5
- JavaScript
- jQuery / AJAX

### Database
- MySQL Server

### Công cụ và môi trường
- Visual Studio Code
- Docker
- Docker Compose
- Git
- GitHub

### Thanh toán trực tuyến
- Chưa tích hợp- Tiếp tục phát triển.

## 5. Chức năng chính

### 5.1. Khách hàng
- Đăng ký, đăng nhập, đăng xuất.
- Xem danh sách sản phẩm.
- Tìm kiếm và lọc sản phẩm.
- Xem chi tiết sản phẩm.
- Lựa chọn sản phẩm.
- Quản lý giỏ hàng.
- Đặt hàng trực tuyến.
- Thanh toán trực tuyến(chưa tích hợp/ đang phát triển).
- Theo dõi trạng thái đơn hàng.
- Xem lịch sử mua hàng.

### 5.2. Nhân viên
- Quản lý đơn hàng.
- Quản lý khách hàng.
- Quản lý nhập hàng.
- Quản lý kho hàng.
- Quản lý nhà cung cấp.
- Cập nhật trạng thái đơn hàng.
- Quản lý đơn vị vận chuyển.

### 5.3. Quản trị viên
- Quản lý tài khoản và phân quyền.
- Quản lý sản phẩm.
- Quản lý danh mục sản phẩm.
- Quản lý biến thể sản phẩm.
- Quản lý kho hàng.
- Quản lý nhà cung cấp.
- Quản lý khuyến mãi.
- Quản lý đơn hàng và thanh toán.
- Quản lý đơn vị vận chuyển.
- Thống kê doanh thu.
- Thống kê sản phẩm bán chạy.

## 6. Yêu cầu hệ thống

- Hệ điều hành: Windows / Linux / macOS.
- Docker Desktop hoặc Docker Engine.
- Git.
- Visual Studio Code.
- Trình duyệt web.
- Kết nối Internet khi clone mã nguồn và tải thư viện.

## 7. Hướng dẫn cài đặt và triển khai

### Bước 1: Clone mã nguồn

```bash
git clone https://github.com/ThieuGia975/BC_Website_Quan_Ly_Cua_Hang_Thoi_Trang.git
```

### Bước 2: Di chuyển vào thư mục dự án

```bash
cd fashion-store-management
```

### Bước 3: Cấu hình môi trường

- Sao chép file `env` thành `.env`.
- Cấu hình thông tin kết nối MySQL.
- Cấu hình các biến môi trường cần thiết.
- Không chia sẻ thông tin bí mật trong file `.env`.

### Bước 4: Khởi chạy Docker

```bash
docker compose up -d --build
```

Kiểm tra trạng thái container:

```bash
docker compose ps
```

### Bước 5: Cài đặt thư viện PHP

Thực hiện cài đặt Composer theo cấu hình Docker của dự án.

```bash
[Nhập lệnh Composer]
```

### Bước 6: Khởi tạo cơ sở dữ liệu

- Khởi tạo database MySQL.
- Import file SQL hoặc chạy Migration.
- Chạy Seed dữ liệu mẫu nếu có.
- Kiểm tra kết nối giữa ứng dụng và MySQL.

### Bước 7: Truy cập website

- **Website:** [Địa chỉ URL]
- **Trang quản trị:** [Địa chỉ URL quản trị]

### Bước 8: Đăng nhập hệ thống

- **Tài khoản quản trị:** [Tài khoản quản trị]
- **Mật khẩu:** [Mật khẩu quản trị]

## 8. Cấu trúc thư mục dự án

```text
fashion-store-management/
│
├── src/
├── public/
├── database/
├── docker/php
├── Dockerfile
├── docker-compose.yml
├── env
├── .gitignore
├── Baocao.docx
└── README.md
```

## 9. Cơ sở dữ liệu

- **Tên database:** ql_cuahangthoitrang
- **Hệ quản trị:** MySQL
- **Các nhóm dữ liệu chính:**
  - Tài khoản và phân quyền.
  - Sản phẩm và biến thể sản phẩm.
  - Danh mục, kích thước và màu sắc.
  - Khách hàng và nhân viên.
  - Nhà cung cấp và nhập hàng.
  - Đơn hàng và chi tiết đơn hàng.
  - Thanh toán.
  - Khuyến mãi.
  - Kho hàng và lịch sử tồn kho.
  - Thẻ thành viên

## 10. Repository và quản lý mã nguồn

- **GitHub Repository:** (https://github.com/ThieuGia975/BC_Website_Quan_Ly_Cua_Hang_Thoi_Trang.git)
- **Branch chính:** main
- **Quản lý phiên bản:** Git
- **Quy trình làm việc:** Clone, Branch, Commit, Push, Pull Request.

## 11. Thông tin liên hệ

- **Đại diện nhóm:** Nguyễn Bùi Thiếu Gia
- **Email:** nguyenbuithieugia2005@gmail.com
- **GitHub:** https://github.com/ThieuGia975/BC_Website_Quan_Ly_Cua_Hang_Thoi_Trang.git

---

© Năm 2026-2027 - Nhóm: Nguyễn Bùi Thiếu Gia_Hồ Tuấn Hưng_Nguyễn Thành Triệu

