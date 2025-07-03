👨‍💻 Tác giả
Họ tên: Phạm Văn Bảo An

Ngành: Công nghệ Thông tin

Định hướng: Kỹ sư phần mềm

Trình độ: Sinh viên năm 2

# 🛍️ Hệ Thống Quản Lý Nhập và Bán - Cửa Hàng Văn Phòng Phẩm

> Một phần mềm quản lý toàn diện quy trình kinh doanh của cửa hàng văn phòng phẩm, từ nhập hàng, lưu kho, đến bán hàng, thống kê doanh thu, sử dụng **C# WinForms** kết hợp với **SQL Server**.

---

## 🚀 Giới thiệu

Hệ thống được xây dựng với mục tiêu giúp các cửa hàng văn phòng phẩm quản lý dữ liệu một cách hiệu quả, chính xác và dễ sử dụng. Giao diện thân thiện, thao tác mượt mà, phù hợp với nhân viên văn phòng hoặc người không chuyên IT.

Phần mềm bao gồm đầy đủ các chức năng quản lý như: **sản phẩm**, **khách hàng**, **nhà cung cấp**, **kho hàng**, **hóa đơn bán**, **hóa đơn nhập**, **thống kê**, **giảm giá**,…

---

## 💻 Công nghệ sử dụng

- 🧩 **Ngôn ngữ**: C#
- 🖥️ **Giao diện**: Windows Forms (WinForms)
- 🛢️ **Cơ sở dữ liệu**: SQL Server
- 🔗 **Kết nối**: ADO.NET

---

## 🧠 Chức năng chi tiết

### 🗂️ Quản lý sản phẩm
- Thêm, sửa, xóa sản phẩm
- Tìm kiếm theo mã, tên, danh mục
- Cập nhật tồn kho và trạng thái sản phẩm

### 🏢 Quản lý nhà cung cấp
- Thêm/sửa/xóa nhà cung cấp
- Lưu thông tin: tên công ty, địa chỉ, số điện thoại, email
- Liên kết với hóa đơn nhập

### 🧑‍💼 Quản lý khách hàng
- Thêm/sửa/xóa khách hàng
- Lưu thông tin: họ tên, số điện thoại, địa chỉ
- Lưu lịch sử mua hàng của từng khách

### 🧾 Quản lý hóa đơn
#### 🔸 Hóa đơn nhập
- Tạo hóa đơn nhập từ nhà cung cấp
- Ghi nhận số lượng, giá nhập, ngày nhập
- Cập nhật kho tự động

#### 🔹 Hóa đơn bán
- Tạo đơn hàng cho khách
- Áp dụng giảm giá nếu có
- Cập nhật số lượng tồn kho
- Tính tổng tiền tự động

### 🏬 Quản lý kho
- Theo dõi số lượng tồn kho
- Cảnh báo sản phẩm sắp hết hàng
- Lịch sử xuất/nhập của từng sản phẩm

### 📊 Thống kê - báo cáo
- Doanh thu theo ngày/tháng/năm
- Top sản phẩm bán chạy
- Lọc theo khách hàng, thời gian hoặc loại sản phẩm

### 💸 Quản lý giảm giá
- Thiết lập khuyến mãi theo sản phẩm, theo thời gian
- Áp dụng khi tạo hóa đơn bán

---

## 📂 Cấu trúc dự án
QuanLiCuaHangVPPham/
├── Database/
│ └── Scripts.sql # Các câu lệnh SQL tạo bảng, trigger, stored procedure
├── QuanLiCuaHangVPPham.sln # File solution C#
├── Forms/ # Giao diện người dùng (WinForms)
│ ├── frmSanPham.cs # Quản lý sản phẩm
│ ├── frmKhachHang.cs # Quản lý khách hàng
│ ├── frmNhaCungCap.cs # Quản lý nhà cung cấp
│ ├── frmHoaDonBan.cs # Quản lý hóa đơn bán
│ ├── frmHoaDonNhap.cs # Quản lý hóa đơn nhập
│ └── frmThongKe.cs # Thống kê và báo cáo
├── Models/ # Các lớp dữ liệu (Sản phẩm, Hóa đơn, v.v.)
├── Helpers/ # Lớp hỗ trợ kết nối CSDL, xử lý logic
└── README.md # File mô tả dự án
---

## 🖼️ Giao diện (Screenshot)

> (Chèn ảnh vào đây nếu có)

---

## ⚙️ Hướng dẫn sử dụng

1. **Clone dự án:**

   ```bash
   git clone https://github.com/Phâmn-0301/QLVP_DB.git
Mở bằng Visual Studio

Cấu hình CSDL:

Mở Scripts.sql trong thư mục Database

Chạy toàn bộ trong SQL Server để tạo database

Mở file Common.cs hoặc Connection.cs và cập nhật chuỗi kết nối (connection string) nếu cần

Chạy chương trình:

Bấm Start để sử dụng hệ thống

