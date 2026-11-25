[![🇺🇸 English](https://img.shields.io/badge/Language-English-1e293b?style=flat-square)](README-EN.md)

# Bot-telegram-Tracuuphatnguoi

Bot Telegram để kiểm tra phạt nguội dựa trên biển số xe.

## ✨ Tính năng

- 🚗 Đăng ký biển số xe để theo dõi vi phạm
- 🔍 Kiểm tra vi phạm giao thông qua API bên ngoài
- 📋 Xem danh sách biển số đã đăng ký
- 📅 Kiểm tra vi phạm định kỳ hàng tuần
- 📲 Menu tương tác với các tùy chọn đăng ký, kiểm tra và xem biển số

## 📦 Cài đặt

1. Clone repository:
    ```bash
    git clone https://github.com/lowji194/Bot-telegram-Tracuuphatnguoi.git
    cd Bot-telegram-Tracuuphatnguoi
    ```

2. Cài đặt các thư viện phụ thuộc:
    ```bash
    pip install -r requirements.txt
    ```

3. Thiết lập token của bot Telegram qua biến môi trường `TELEGRAM_BOT_TOKEN` (xem `.env.example`) hoặc gán trực tiếp trong `bot.py`:
    ```python
    TELEGRAM_BOT_TOKEN = os.getenv("TELEGRAM_BOT_TOKEN", "YOUR_TELEGRAM_BOT_TOKEN")
    ```

## 🚀 Sử dụng

1. Chạy bot:
    ```bash
    python bot.py
    ```

2. Tương tác với bot trên Telegram:
    - `/start` - Hiển thị menu
    - `/dangky` - Đăng ký biển số cần theo dõi
    - `/kiemtra` - Kiểm tra các biển số đã đăng ký
    - `/danhsach` - Xem danh sách biển số đã đăng ký
    - `/huongdan` - Hiển thị hướng dẫn sử dụng
    - `/lienhe` - Hiển thị thông tin liên hệ

## 📅 Kiểm tra định kỳ

Bot sẽ thực hiện kiểm tra vi phạm giao thông vào mỗi thứ Hai hàng tuần. Nếu phát hiện vi phạm, bot sẽ gửi thông báo đến người dùng đã đăng ký biển số.

---

## 📫 Liên hệ

- 🌐 **Website:** [theloi.io.vn](https://theloi.io.vn)
- 💬 **Telegram:** [@theloi194](https://t.me/theloi194)
- 📌 **Facebook:** [Lowji194](https://facebook.com/Lowji194)

---

## ☕ Nếu bạn thấy dự án này hữu ích, một ly cà phê từ bạn sẽ là động lực tuyệt vời để mình tiếp tục phát triển thêm!

<p align="center">
  <img src="https://raw.githubusercontent.com/lowji194/lowji194/main/assets/donate-qr.svg" alt="Mời cà phê" width="240" />
</p>
