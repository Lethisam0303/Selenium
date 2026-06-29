# Facebook Automation Testing

## 📌 Giới thiệu

Đây là project tự động hóa kiểm thử (Automation Testing) cho các chức năng cơ bản của website Facebook, bao gồm:

* ✅ Đăng nhập (Login)
* ✅ Đăng ký tài khoản (Register)
* ✅ Kiểm tra thông báo lỗi khi nhập sai dữ liệu
* ✅ Kiểm tra điều hướng sau khi đăng nhập
* ✅ Báo cáo kết quả kiểm thử

Project được xây dựng nhằm mục đích học tập và thực hành Automation Testing với Selenium WebDriver.

---

## 🛠 Công nghệ sử dụng

* Java
* Selenium WebDriver
* TestNG
* Maven
* WebDriverManager
* Extent Report (nếu có)

---

## 📂 Cấu trúc Project

```
FacebookAutomation/
│
├── src/
│   ├── main/
│   └── test/
│       ├── testcases/
│       ├── pages/
│       ├── utils/
│       └── data/
│
├── reports/
├── screenshots/
├── pom.xml
└── README.md
```

---

## 🚀 Chức năng kiểm thử

### 1. Login Test

* Đăng nhập với tài khoản hợp lệ
* Đăng nhập sai mật khẩu
* Đăng nhập sai email
* Để trống thông tin đăng nhập
* Kiểm tra thông báo lỗi

---

### 2. Register Test

* Đăng ký với dữ liệu hợp lệ
* Thiếu thông tin bắt buộc
* Email không hợp lệ
* Mật khẩu không hợp lệ
* Kiểm tra thông báo lỗi

---

## ⚙️ Cài đặt

Clone project:

```bash
git clone https://github.com/your-username/facebook-automation.git
```

Cài đặt dependency:

```bash
mvn clean install
```

Chạy test:

```bash
mvn test
```

Hoặc chạy trực tiếp bằng TestNG trong IDE.

---

## 📊 Báo cáo

Sau khi chạy test, báo cáo sẽ được tạo trong thư mục:

```
/reports
```

Nếu project sử dụng Extent Report, mở file:

```
ExtentReport.html
```

để xem kết quả chi tiết.

---

## 🎯 Mục tiêu

* Thực hành Selenium Automation Testing.
* Áp dụng Page Object Model (POM).
* Viết test case rõ ràng và dễ bảo trì.
* Tạo báo cáo kiểm thử tự động.

---

## 📌 Lưu ý

* Project chỉ phục vụ mục đích học tập và nghiên cứu.
* Không sử dụng để spam, thu thập dữ liệu hoặc vi phạm điều khoản sử dụng của Facebook.
* Việc tự động hóa trên Facebook có thể bị giới hạn hoặc thay đổi theo cập nhật của nền tảng.

---

## 👨‍💻 Tác giả

**Your Name**

GitHub: https://github.com/your-username
