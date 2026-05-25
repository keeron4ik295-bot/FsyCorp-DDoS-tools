# @FsyCorp DDoS Tools | MRVALENTE

![Telegram (https://img.shields.io/badge/Telegram-@FsyCorp-blue)](https://t.me/FsyCorp)
![License (https://img.shields.io/badge/License-MIT-green)](LICENSE)
![Python (https://img.shields.io/badge/Python-3.10+-yellow)](https://python.org)

> Инструменты для нагрузочного тестирования своих серверов.
> Только для образовательных целей! Автор ответственности не несет.

---

## 📦 Инструменты

| Название | Описание | Статус |
|----------|----------|--------|
| Proxy Manager | Скачивание и проверка прокси (HTTP/SOCKS4/SOCKS5) | ✅ Stable |
| DDoS Tester | Стресс-тест своих серверов (GET/POST/MIX) | ✅ Stable |

---

## 🚀 Быстрый старт

`bash
# 1. Клонируй репозиторий
git clone https://github.com/ТВОЙ_НИК/FsyCorp-DDoS-Tools.git
cd FsyCorp-DDoS-Tools

# 2. Установи зависимости
pip install -r requirements.txt

# 3. Запусти Proxy Manager
python proxy_manager/proxy_manager.py

# 4. После скачивания прокси — запусти DDoS Tester
python ddos/ddos.py
