<div align="center">

# ⚡ V-Tool Beta

### Ultimate Utility Script for Web Enhancement

[![Version](https://img.shields.io/badge/version-beta-blue.svg)](https://github.com/vyvegroup/vyvegroup)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)
[![Platform](https://img.shields.io/badge/platform-Web-orange.svg)](https://github.com/vyvegroup/vyvegroup)
[![Made with](https://img.shields.io/badge/made%20with-JavaScript-yellow.svg)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

<p align="center">
  <strong>🚀 Một công cụ tiện ích mạnh mẽ | A powerful utility tool</strong>
</p>

[📖 Hướng dẫn sử dụng](#-hướng-dẫn-sử-dụng--usage-guide) •
[✨ Tính năng](#-tính-năng--features) •
[🔧 Cài đặt](#-cài-đặt--installation) •
[📜 Giấy phép](#-giấy-phép--license)

</div>

---

## 🌐 Ngôn ngữ | Languages

- [🇻🇳 Tiếng Việt](#tiếng-việt)
- [🇺🇸 English](#english)

---

<a name="tiếng-việt"></a>
# 🇻🇳 Tiếng Việt

## 📋 Giới thiệu

**V-Tool Beta** là một script tiện ích cao cấp được thiết kế để nâng cao trải nghiệm duyệt web của bạn. Với khả năng tích hợp trực tiếp vào trình duyệt, công cụ này cung cấp nhiều tính năng hữu ích chỉ với một cú click chuột.

## ✨ Tính năng

- ⚡ **Kích hoạt nhanh** - Khởi động công cụ chỉ trong vài giây
- 📱 **Hỗ trợ Mobile** - Tương thích hoàn hảo với Chrome và Safari trên điện thoại
- 🔒 **Bảo mật cao** - Hoạt động an toàn với cơ chế Direct Injection
- 🎯 **Dễ sử dụng** - Giao diện thân thiện, không cần cài đặt phức tạp
- 🔄 **Cập nhật tự động** - Luôn có phiên bản mới nhất qua CDN

## 🚀 Hướng dẫn sử dụng

### Phương thức kích hoạt (Direct Injection)

Để đảm bảo bảo mật và hoạt động chính xác trên trình duyệt Mobile (Chrome/Safari), vui lòng thực hiện chính xác theo quy trình **4 bước** dưới đây:

#### Bước 1: Sao chép lõi lệnh (Payload)

```javascript
(function(){
  var s = document.createElement('script');
  s.src = 'https://cdn.jsdelivr.net/gh/vyvegroup/VenStorage@main/vtoolbeta.js?t=' + Date.now();
  document.body.appendChild(s);
})();
```

> ⚠️ **Lưu ý quan trọng:** Không bao gồm tiền tố `javascript:` khi sao chép

#### Bước 2: Tạo Bookmark (Trên Mobile)

1. Mở trang web bất kỳ
2. Thêm trang vào bookmark/favorites
3. Đặt tên: **"V-Tool"**

#### Bước 3: Chỉnh sửa Bookmark

1. Vào danh sách bookmark đã lưu
2. Chỉnh sửa URL của bookmark "V-Tool"
3. Dán đoạn mã đã sao chép ở Bước 1 vào trường URL
4. Thêm tiền tố `javascript:` vào **đầu** đoạn mã

#### Bước 4: Kích hoạt

1. Truy cập trang web bạn muốn sử dụng công cụ
2. Mở bookmark "V-Tool"
3. Công cụ sẽ tự động tải và kích hoạt

## 🔧 Cài đặt trên Desktop

### Cách 1: Bookmarklet (Khuyến nghị)

1. Tạo bookmark mới với URL sau:

```
javascript:(function(){var s=document.createElement('script');s.src='https://cdn.jsdelivr.net/gh/vyvegroup/VenStorage@main/vtoolbeta.js?t='+Date.now();document.body.appendChild(s);})();
```

2. Click vào bookmark khi cần sử dụng

### Cách 2: Console DevTools

1. Nhấn `F12` hoặc `Ctrl+Shift+J` để mở DevTools
2. Chuyển sang tab Console
3. Dán và chạy đoạn mã từ [Bước 1](#bước-1-sao-chép-lõi-lệnh-payload)

## ⚙️ Yêu cầu hệ thống

| Trình duyệt | Phiên bản | Trạng thái |
|-------------|-----------|------------|
| Chrome | 80+ | ✅ Được hỗ trợ |
| Safari | 13+ | ✅ Được hỗ trợ |
| Firefox | 75+ | ✅ Được hỗ trợ |
| Edge | 80+ | ✅ Được hỗ trợ |

## 🛡️ Bảo mật

- ✅ Mã nguồn mở và minh bạch
- ✅ Không lưu trữ dữ liệu cá nhân
- ✅ Hoạt động cục bộ trên trình duyệt
- ✅ Không gửi dữ liệu ra bên ngoài

---

<a name="english"></a>
# 🇺🇸 English

## 📋 Introduction

**V-Tool Beta** is a premium utility script designed to enhance your web browsing experience. With direct browser integration capabilities, this tool provides multiple useful features with just one click.

## ✨ Features

- ⚡ **Quick Activation** - Launch the tool in seconds
- 📱 **Mobile Support** - Perfect compatibility with Chrome and Safari on mobile devices
- 🔒 **High Security** - Operates safely with Direct Injection mechanism
- 🎯 **Easy to Use** - User-friendly interface, no complex installation required
- 🔄 **Auto Updates** - Always get the latest version via CDN

## 🚀 Usage Guide

### Activation Method (Direct Injection)

To ensure security and accurate operation on Mobile browsers (Chrome/Safari), please follow the **4-step** process below:

#### Step 1: Copy the Payload

```javascript
(function(){
  var s = document.createElement('script');
  s.src = 'https://cdn.jsdelivr.net/gh/vyvegroup/VenStorage@main/vtoolbeta.js?t=' + Date.now();
  document.body.appendChild(s);
})();
```

> ⚠️ **Important Note:** Do not include the `javascript:` prefix when copying

#### Step 2: Create Bookmark (On Mobile)

1. Open any webpage
2. Add the page to bookmarks/favorites
3. Name it: **"V-Tool"**

#### Step 3: Edit Bookmark

1. Go to your saved bookmarks list
2. Edit the "V-Tool" bookmark URL
3. Paste the code copied in Step 1 into the URL field
4. Add the `javascript:` prefix at the **beginning** of the code

#### Step 4: Activate

1. Visit the webpage where you want to use the tool
2. Open the "V-Tool" bookmark
3. The tool will automatically load and activate

## 🔧 Desktop Installation

### Method 1: Bookmarklet (Recommended)

1. Create a new bookmark with the following URL:

```
javascript:(function(){var s=document.createElement('script');s.src='https://cdn.jsdelivr.net/gh/vyvegroup/VenStorage@main/vtoolbeta.js?t='+Date.now();document.body.appendChild(s);})();
```

2. Click the bookmark when needed

### Method 2: DevTools Console

1. Press `F12` or `Ctrl+Shift+J` to open DevTools
2. Switch to the Console tab
3. Paste and run the code from [Step 1](#step-1-copy-the-payload)

## ⚙️ System Requirements

| Browser | Version | Status |
|---------|---------|--------|
| Chrome | 80+ | ✅ Supported |
| Safari | 13+ | ✅ Supported |
| Firefox | 75+ | ✅ Supported |
| Edge | 80+ | ✅ Supported |

## 🛡️ Security

- ✅ Open and transparent source code
- ✅ No personal data storage
- ✅ Works locally in your browser
- ✅ No external data transmission

---

## 🤝 Đóng góp | Contributing

Chúng tôi hoan nghênh mọi đóng góp! Vui lòng:

1. Fork repository này
2. Tạo branch mới (`git checkout -b feature/AmazingFeature`)
3. Commit thay đổi (`git commit -m 'Add some AmazingFeature'`)
4. Push lên branch (`git push origin feature/AmazingFeature`)
5. Mở Pull Request

We welcome all contributions! Please:

1. Fork this repository
2. Create a new branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📜 Giấy phép | License

Dự án này được cấp phép theo giấy phép MIT - xem file [LICENSE](LICENSE) để biết thêm chi tiết.

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📞 Liên hệ | Contact

- 🌐 Website: [vyvegroup.github.io](https://vyvegroup.github.io)
- 📧 Email: contact@vyvegroup.com
- 🐦 Twitter: [@vyvegroup](https://twitter.com/vyvegroup)

---

<div align="center">

**⭐ Nếu bạn thấy dự án này hữu ích, hãy để lại một star! | If you find this project useful, please leave a star! ⭐**

Made with ❤️ by [Vyve Group](https://github.com/vyvegroup)

</div>
