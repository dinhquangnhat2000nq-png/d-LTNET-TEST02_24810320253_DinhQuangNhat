# BÁO CÁO BÀI TẬP THỰC HÀNH LẬP TRÌNH C# WINFORMS

## I. THÔNG TIN SINH VIÊN
* **Họ và tên:** Đinh Quang Nhật
* **Mã số sinh viên:** 24810320253
* **Lớp học phần:** Lập trình .NET - Mã Lớp: D19QTANM1

* **Link Repository:**

## II. DANH SÁCH BÀI TẬP HOÀN THÀNH & TỰ ĐÁNH GIÁ

| Bài tập | Tiêu đề bài tập | Trạng thái | Mức độ hoàn thành (%) |
| :---: | :--- | :---: | :---: |

| **Bài 1** | Quản lý Dịch vụ Phòng Gym & Hội viên | Hoàn thành | 100% |
| **Bài 2** | Báo cáo & Lưu trữ Tài liệu Nhà sách | Hoàn thành | 100% |
| **Bài 3** | Hệ thống MDI Quản lý Bệnh viện & Async | Hoàn thành | 90% |
| **BÀI 4** | BẢNG ĐIỀU KHIỂN TỔNG HỢP BÁO CÁO KHO HÀNG | Hoàn thành | 100% |

## III. MINH HỌA GIAO DIỆN & KỸ THUẬT NỔI BẬT

### 1. Bài 1: Quản lý Dịch vụ Phòng Gym & Hội viên
* **Kỹ thuật áp dụng:** Cấu hình DataGridView bằng code (`AutoGenerateColumns =
false`), Data Binding 2 chiều với `BindingSource`, Validation với `ErrorProvider`.
* **Hình ảnh minh họa Giao diện:**

<img width="1347" height="920" alt="bai1_main" src="https://github.com/user-attachments/assets/299aabd6-4e53-48dc-8eef-89396bb999ec" />

*Mô tả: Giao diện chính hiển thị DataGridView và đồng bộ dữ liệu 2 chiều lên các
TextBox.*

<img width="1346" height="921" alt="bai1_error" src="https://github.com/user-attachments/assets/753af4f1-aa17-4a55-8ea5-10001a1180ac" />

*Mô tả: Kiểm tra hợp lệ dữ liệu nhập vào bằng ErrorProvider khi nhấn Thêm mới.*
### 2. Bài 2: Quản lý & Xuất Báo cáo Nhà sách
* **Kỹ thuật áp dụng:** `OpenFileDialog` (Tải ảnh bìa), `SaveFileDialog` /
`OpenFileDialog` (Đọc/Ghi file CSV), Cập nhật `StatusStrip` theo thời gian thực.
* **Hình ảnh minh họa Giao diện:**

 <img width="1170" height="792" alt="bai2_main" src="https://github.com/user-attachments/assets/39e23ed5-e11b-487b-b10f-f009944ebb20" />

*Mô tả: Chọn ảnh bìa sách từ đĩa cứng hiển thị lên PictureBox và nạp dữ liệu từ file
CSV.*

<img width="995" height="637" alt="bai2_csv" src="https://github.com/user-attachments/assets/f81b6c7e-602e-4ae3-97bd-7ec17810a00e" />

### 3. Bài 3: Kiến trúc MDI & Xử lý Bất đồng bộ (Async/Await)
* **Kỹ thuật áp dụng:** MDI Container, Quản lý chống mở trùng Form con,
`async/await` chống treo UI, Safe Cross-Thread bằng `this.Invoke()`.
* **Hình ảnh minh họa Giao diện:**

<img width="1352" height="858" alt="bai3_mdi" src="https://github.com/user-attachments/assets/68d3b69e-7620-4474-bec2-37523546f295" />

### 4. BÀI 4: BẢNG ĐIỀU KHIỂN TỔNG HỢP BÁO CÁO KHO HÀNG (ASYNC/AWAIT & KHÔNG KHÓA UI)
* **Kỹ thuật áp dụng:** async/await xử lý tác vụ bất đồng bộ, Task.Run() xử lý dữ liệu nền, ProgressBar hiển thị tiến trình xử lý, Label cập nhật trạng thái theo thời gian thực, DataGridView hiển thị dữ liệu báo cáo tổng hợp.

* **Hình ảnh minh họa Giao diện:**

<img width="881" height="573" alt="bai4_async" src="https://github.com/user-attachments/assets/07b2c2c3-7edb-4c27-8a61-84bd5a8a2a09" />

