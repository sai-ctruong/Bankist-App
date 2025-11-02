# 💰 Bankist Website

Một ứng dụng **giả lập ngân hàng trực tuyến (Bankist)** được viết bằng **HTML, CSS và JavaScript**, giúp người dùng đăng nhập, chuyển tiền, vay tiền và xem thống kê tài chính theo thời gian thực.  
Đây là bản **tùy chỉnh lại từ dự án gốc của Jonas Schmedtmann**, với **đơn vị tiền tệ VND**
---

## 🚀 Live Demo

Bạn có thể trải nghiệm ứng dụng trực tiếp tại đây:  
**👉 [Xem Demo Ngay!](https://github.com/SaiCTruong/BankistWebsite.git) 👈**

---

## 🧠 Tính năng chính

### 🔐 Login
- Đăng nhập bằng **username** và **PIN**.
- Khi đăng nhập thành công, hệ thống hiển thị lời chào và thông tin tài khoản.

### 💸 Movements
- Hiển thị **toàn bộ danh sách giao dịch** (deposit/withdrawal).
- Có thể **sắp xếp giao dịch tăng dần** bằng nút **SORT**.

### 📊 Summary
- **IN:** Tổng tiền nhận vào.  
- **OUT:** Tổng tiền chi ra.  
- **INTEREST:** Tổng lãi suất sinh ra.  
- Tất cả giá trị được hiển thị theo định dạng **VND** với `Intl.NumberFormat('vi-VN')`.

### 💱 Transfer
- Chuyển tiền giữa các tài khoản hợp lệ.
- Kiểm tra số dư và tài khoản trước khi thực hiện giao dịch.

### 🏦 Loan
- Có thể yêu cầu vay nếu có giao dịch gửi tiền tối thiểu **10%** số tiền vay.

### ❌ Close Account
- Đóng tài khoản bằng cách nhập đúng **username** và **PIN**.

### 🔁 Logout Timer
- Hệ thống tự động **đăng xuất** sau một khoảng thời gian không hoạt động.


---

## 🧩 Cấu trúc dự án

```
/
├── index.html # File HTML chứa cấu trúc trang web
├── style.css # File CSS chứa toàn bộ style
├── script.js # Logic xử lý chính bằng JavaScript
├── logo.png # Logo của ứng dụng
└── icon.png # Biểu tượng trang web

```

---

## 💻 Cách chạy ứng dụng

Đây là một **dự án tĩnh**, không cần server hay framework.

### ✅ 1. Clone hoặc tải dự án
```bash
git clone https://github.com/SaiCTruong/BankistWebsite.git

### ✅ 2. Mở file index.html
**Chạy trực tiếp bằng trình duyệt hoặc dùng VS Code với Live Server.**

### ✅ 3. Đăng nhập với tài khoản mẫu
Dưới đây là danh sách các tài khoản **demo** có sẵn trong hệ thống:

| Chủ tài khoản | Username | PIN  |
|----------------|-----------|------|
| Jonas Schmedtmann | js | 1111 |
| Phạm Công Trường | pct | 1208 |
| Nguyễn Nhật Thiên | nnt | 2105 |
| Lê Quốc Khánh | lqk | 3004 |

Sau khi đăng nhập, bạn có thể:
- Xem danh sách giao dịch (tiền vào/ra)
- Chuyển tiền giữa các tài khoản
- Vay tiền và xem lãi suất
- Đóng tài khoản
- Sắp xếp giao dịch (Sort)

---


## 🧮 Công nghệ sử dụng

- **HTML5:** Cấu trúc trang và bố cục chính.  
- **CSS3:** Thiết kế giao diện, hiệu ứng hover và responsive layout.  
- **JavaScript (ES6+):**
  - Thao tác DOM (DOM Manipulation)
  - Xử lý sự kiện (Event Handling)
  - Phương thức mảng nâng cao (`map`, `filter`, `reduce`, `sort`)
  - Định dạng tiền tệ Việt Nam với `Intl.NumberFormat('vi-VN')`

---

## 🧑‍💻 Tác giả

👤 [Phạm Công Trường](https://github.com/SaiCTruong)

---

## 🏁 Giấy phép

Dự án được sử dụng **phi thương mại** cho **mục đích học tập và nghiên cứu**.  
**Bản gốc** thuộc quyền sở hữu của *Jonas Schmedtmann*.  

