<h1>CyberMart</h1>

CyberMart là một ứng dụng thương mại điện tử được xây dựng trên nền tảng Android, với phần backend sử dụng Firebase. Ứng dụng cung cấp tính năng quản lý sản phẩm, giỏ hàng, và xử lý người dùng.

<h3>Tính năng chính</h3>

- **Đăng ký/Đăng nhập:** Sử dụng Firebase Authentication để quản lý tài khoản người dùng.

- **Quản lý sản phẩm:**

  - Hiển thị danh sách sản phẩm.

  - Tìm kiếm sản phẩm.

  - Thêm sản phẩm mới (chỉ dành cho admin).

  - Chỉnh sửa và xoá sản phẩm (chỉ dành cho admin).

- **Giỏ hàng:**

  - Thêm sản phẩm vào giỏ hàng.

  - Xoá sản phẩm khỏi giỏ hàng.

  - Hiển thị tổng giá trị giỏ hàng.

**Thanh toán:** Hiển thị tổng giá và chi tiết đơn hàng trước khi xác nhận thanh toán.

<h2>Công nghệ sử dụng</h2>

<h3>Frontend (Android)</h3>

- **Ngôn ngữ:** Java.

- **Giao diện:** Sử dụng ConstraintLayout, RecyclerView, và BottomNavigationView để tạo giao diện người dùng.

- **Xử lý dữ liệu:** Kết nối với Firebase Realtime Database và Firebase Firestore để lấy và lưu trữ dữ liệu.

<h3>Backend</h3>

- **Firebase Authentication:** Quản lý xác thực và thông tin người dùng.

- **Firebase Firestore:** Lưu trữ dữ liệu về sản phẩm, giỏ hàng, và thông tin đơn hàng.

- **Firebase Storage:** Lưu trữ hình ảnh sản phẩm.

<h2>Cài đặt</h2>

<h3>Yêu cầu hệ thống</h3>

- Android Studio (phiên bản mới nhất).

- Thiết bị Android (hoặc giả lập) chạy Android 6.0 (API 23) trở lên.

- Tài khoản Firebase để kết nối backend.

<h3>Cách cài đặt</h3>

1. Clone dự án từ GitHub:

- git clone https://github.com/chaolaolo/CyberMart.git

2. Mở dự án trong Android Studio.

3. Cấu hình Firebase:

- Tạo một dự án Firebase tại Firebase Console.

- Thêm file google-services.json vào thư mục app trong dự án.

- Bật Firebase Authentication và Firestore Database trong Firebase Console.

4. Đồng bộ hoá Gradle trong Android Studio.

5. Chạy ứng dụng trên thiết bị hoặc trình giả lập.

<h2>Sử dụng</h2>

1. **Đăng ký/Đăng nhập:**

- Người dùng cần đăng ký tài khoản hoặc đăng nhập để sử dụng ứng dụng.

2. **Duyệt sản phẩm:**

- Người dùng có thể xem danh sách sản phẩm và tìm kiếm sản phẩm theo tên.

3. **Quản lý giỏ hàng:**

- Thêm sản phẩm vào giỏ hàng bằng cách nhấn vào nút "Thêm vào giỏ".

- Xoá sản phẩm khỏi giỏ hàng bằng cách nhấn vào biểu tượng xoá.

4. **Quản trị (Admin):**

- Admin có thể thêm, sửa hoặc xoá sản phẩm từ danh sách sản phẩm.

<h2>Cấu trúc dự án</h2>
CyberMart/
├── app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/com/cybermart/
│   │   │   │   ├── adapters/       # Adapter cho RecyclerView
│   │   │   │   ├── models/         # Các model dữ liệu
│   │   │   │   ├── ui/             # Các activity và fragment
│   │   │   │   ├── utils/          # Các tiện ích
│   │   │   ├── res/
│   │   │   │   ├── layout/         # Layout XML
│   │   │   │   ├── drawable/       # Tài nguyên đồ hoạ
│   │   │   │   ├── values/         # Tài nguyên giá trị (strings, styles,...)
│   ├── build.gradle                # Cấu hình Gradle
├── google-services.json            # Cấu hình Firebase (thêm vào thủ công)
<h2>Liên hệ</h2>

**Tác giả:** Chảo Láo Lở - Trần Đình Vũ - Đặng Văn Sĩ - Lâm Tùng Dương

**Email:** chaolaolo290604@gmail.com

