# 🔍 TBFPUMBA // Recon & Enumeration Hub (`recon-hub`)

![License: GPLv3](https://img.shields.io/badge/License-GPLv3-blue.svg)
![Maintained BY](https://img.shields.io/badge/Maintained%20by-TBFPUMBA-002b49)
![Platform](https://img.shields.io/badge/Platform-GitHub%20Pages-green)
![Suite Component](https://img.shields.io/badge/Suite-TBFPUMBA%20Pentest%20Tools-orange)

Автономный веб-генератор команд для проведения разведки (Reconnaissance), сканирования портов, фаззинга веб-директорий и поддоменов для аудита безопасности и прохождения машин на **Hack The Box / TryHackMe**.

🌐 **Онлайн-версия генератора:** https://cocofembo-glitch.github.io/recon-hub/

---

## 🛠 Часть экосистемы (TBFPUMBA Pentest Suite)

Этот инструмент входит в единую линейку утилит для проведения аудитов и пентэста. В сочетании с прошлым инструментом вы получаете полный цикл работы с целевой машиной:

1. 🔍 **`recon-hub`** *(Текущий инструмент)* — Разведка, сканирование портов (`nmap`), фаззинг директорий и VHOST (`ffuf`, `gobuster`), брутфорс (`hydra`).
2. ⚡ [**`field-payloads`**](https://github.com/cocofembo-glitch/field-payloads) — Генерация обратных шеллов (Reverse Shells), подъем слушателей, стабилизация TTY-терминалов и WAF Bypass.

---

## 🚀 Основные возможности

- 🔄 **Динамическая подстановка:** Введи IP-адрес цели, домен (`VHOST`) и путь к словарю — все команды автоматических утилит обновятся мгновенно.
- 📡 **Nmap Scanning:** Шаблоны быстрых сканов, детального анализа сервисов (`-sCV`) и UDP-портов.
- 🔎 **Web Directory & Subdomain Fuzzing:** Готовые пресеты для `ffuf` (рекурсивный поиск и поиск поддоменов) и `gobuster`.
- 🔑 **Bruteforce & Enum:** Быстрые команды для `hydra` (SSH), `wpscan` (WordPress) и `smbclient`.
- ⚡ **Копирование в один клик:** Быстрое копирование готовых команд прямо в консоль.
- 📱 **Полный Офлайн:** Работает локально в браузере без использования внешних API и бэкенда.

---

## 🛠 Быстрый запуск

### 1. Просмотр через браузер
Просто перейди по ссылке на опубликованный [GitHub Pages](https://cocofembo-glitch.github.io/recon-hub/).

### 2. Локальное клонирование
```bash
git clone [https://github.com/cocofembo-glitch/recon-hub.git](https://github.com/cocofembo-glitch/recon-hub.git)
cd recon-hub
start index.html   # На Windows
xdg-open index.html # На Linux
