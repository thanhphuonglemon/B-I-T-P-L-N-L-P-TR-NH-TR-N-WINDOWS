# LẬP TRÌNH TRÊN WINDOWS
## PHẦN MỀM QUẢN LÝ THƯ VIỆN C#

### Thông tin thực hiện
* **Trường:** Đại học Văn Hiến - Khoa Công nghệ Thông tin
* **Môn học:** Lập trình trên Windows
* **Sinh viên thực hiện:**
  * Phan Thùy Vy - MSSV: 231A290028
  * Hứa Khắc Thanh Phương - MSSV: 231A010626

### Giới thiệu dự án
Ứng dụng Quản lý Thư viện được xây dựng theo mô hình 3 lớp (GUI - BUS - DAL - DTO), sử dụng Entity Framework và giao diện C# WinForms (kết hợp thư viện giao diện Siticone UI).

### Yêu cầu môi trường
* Visual Studio 2022
* .NET Framework 4.7.2
* Entity Framework 6.4.4
* Microsoft SQL Server
* Siticone UI/UX Framework

### Hướng dẫn cài đặt và chạy chương trình
1. **Khởi tạo Database:**
   * Mở Microsoft SQL Server Management Studio (SSMS).
   * Mở và thực thi file `QLTV.sql` để tạo cơ sở dữ liệu và dữ liệu mẫu.
   * Cập nhật chuỗi kết nối (`connectionStrings`) trong file `GUI/App.config` cho phù hợp với máy của bạn.
2. **Chạy ứng dụng:**
   * Mở solution `QLTV.sln` trong Visual Studio 2022.
   * Restore NuGet packages (Entity Framework, Siticone UI,...).
   * Nhấn **F5** hoặc **Start** để build và chạy chương trình.

### Tài liệu báo cáo
* File báo cáo chi tiết đính kèm trong thư mục: `BaoCao_QLTV.docx` và `BaoCao_QLTV.pdf`.
