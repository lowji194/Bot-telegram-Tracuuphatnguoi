[![🇻🇳 Tiếng Việt](https://img.shields.io/badge/Language-Ti%E1%BA%BFng%20Vi%E1%BB%87t-1e293b?style=flat-square)](README.md)

# Bot-telegram-Tracuuphatnguoi

A Python Telegram bot for checking Vietnamese traffic violations (*phạt nguội*) by license plate, managing tracked plates, and sending automated weekly violation alerts.

## Features

- Register and manage vehicle license plates (`registered_plates.json`)
- Query traffic violation records via external API
- Interactive Telegram inline menu and command shortcuts (`/start`, `/dangky`, `/kiemtra`, `/danhsach`, `/huongdan`, `/lienhe`)
- Automated weekly violation check every Monday with notifications

## Installation & Usage

1. **Clone and install dependencies**
   ```bash
   git clone https://github.com/lowji194/Bot-telegram-Tracuuphatnguoi.git
   cd Bot-telegram-Tracuuphatnguoi
   pip install -r requirements.txt
   ```

2. **Configure your bot token**
   Set the `TELEGRAM_BOT_TOKEN` environment variable (see `.env.example`) or replace the fallback value in `bot.py`.

3. **Run the bot**
   ```bash
   python bot.py
   ```

## License

Released under the [MIT License](LICENSE).

## Contact

- **Website:** [theloi.io.vn](https://theloi.io.vn)
- **Telegram:** [@theloi194](https://t.me/theloi194)
- **Facebook:** [Lowji194](https://facebook.com/Lowji194)
