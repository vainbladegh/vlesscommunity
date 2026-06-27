<div align="center">

# 🌐 Community VPN Aggregator

**Общий пул рабочих VPN-серверов, который наполняет само сообщество.**
Каждый делится подписками — каждый получает доступ ко всем проверенным серверам.

[![Service](https://img.shields.io/badge/service-vainblade.duckdns.org-6366f1?style=for-the-badge)](https://vainblade.duckdns.org)
[![License](https://img.shields.io/github/license/vainbladegh/vlesscommunity?style=for-the-badge)](LICENSE)
[![Changelog](https://img.shields.io/badge/changelog-here-818cf8?style=for-the-badge)](CHANGELOG.md)

[![Stars](https://img.shields.io/github/stars/vainbladegh/vlesscommunity?style=social)](https://github.com/vainbladegh/vlesscommunity)
[![Issues](https://img.shields.io/github/issues/vainbladegh/vlesscommunity)](https://github.com/vainbladegh/vlesscommunity/issues)

🇷🇺 [Русский](#-русский) · 🇬🇧 [English](#-english) · 🇨🇳 [中文](#-中文)

> ℹ️ Это **витрина** проекта: что это за сервис и как им пользоваться.
> Исходный код, инфраструктура и источники серверов здесь не публикуются.

</div>

---

## 🇷🇺 Русский

### О сервисе

**Community VPN Aggregator** — один общий, постоянно обновляемый пул рабочих
VPN-серверов. Люди добавляют свои подписки и share-ссылки; сервис в реальном
времени проверяет их на работоспособность и оставляет в пуле только живые.
Ты получаешь **одну ссылку-подписку** — и сразу десятки рабочих серверов прямо
в своём клиенте, без ручной настройки.

🔗 **Сервис:** **https://vainblade.duckdns.org**

### ✨ Возможности

- 🔄 **Авто-формат под клиент** — base64, sing-box JSON или Clash YAML отдаются
  автоматически по твоему клиенту, настраивать ничего не нужно
- ✅ **Только живые серверы** — каждый проходит реальную проверку (xray-knife):
  скорость, задержка, TTFB; мёртвые отсеиваются
- ♻️ **Окно стабильности** — сервер должен стабильно отвечать (правило 2-из-3),
  «моргающие» ноды не засоряют пул
- 🛡️ **Фильтр мусора и спама** — тестовые и пустые ноды удаляются
- 🔗 **Отдельная ссылка на каждую подписку** — свой уникальный URL
- 🚦 **Анти-абуз** — мягкие лимиты на добавление с одного IP
- 📊 **Живая статистика** — число серверов, разбивка по протоколам, задержка/скорость
- 🎨 **Современный UI** — тёмная тема, адаптив под мобильные

### 🚀 Как пользоваться

1. Открой **https://vainblade.duckdns.org**
2. Скопируй ссылку подписки с сайта
3. Вставь её в свой VPN-клиент и обнови подписку — готово

**Клиенты:** v2rayNG · Hiddify · Happ · NekoBox / Throne · Streisand ·
Shadowrocket · Clash Meta (mihomo) · sing-box

### 🤝 Как поделиться серверами

Прямо на сайте вставь ссылку своей подписки **или** сами share-ссылки.
Сервис проверит их и добавит рабочие в общий пул — **анонимно, без регистрации**.

### 🧩 Протоколы и транспорты

| Протоколы | Транспорты | Безопасность |
|---|---|---|
| VLESS, VMess, Trojan, Shadowsocks, Hysteria2, TUIC | TCP, WebSocket, gRPC, xhttp, httpupgrade, h2 | Reality, TLS |

### ❓ FAQ

- **Это бесплатно?** Да, полностью.
- **Нужна регистрация?** Нет, всё анонимно.
- **Какой клиент выбрать?** Любой из списка — сервис сам отдаёт нужный формат.
- **Почему сервер пропал?** В пуле только живые: если нода умерла, её убирают автоматически.

---

## 🇬🇧 English

### About

**Community VPN Aggregator** is one shared, continuously updated pool of working
VPN servers. People add their subscriptions and raw share links; the service
checks them for liveness in real time and keeps only the working ones. You get a
**single subscription link** with dozens of working servers in your client — no
manual setup.

🔗 **Service:** **https://vainblade.duckdns.org**

### ✨ Features

- 🔄 **Auto format per client** — base64, sing-box JSON or Clash YAML served
  automatically based on your client
- ✅ **Live servers only** — each is really tested (xray-knife): speed, latency,
  TTFB; dead ones are dropped
- ♻️ **Stability window** — a server must answer consistently (2-of-3 rule)
- 🛡️ **Spam & junk filtering**
- 🔗 **Per-subscription link** — each gets a unique URL
- 🚦 **Anti-abuse** soft per-IP limits
- 📊 **Live stats** — server count, protocol breakdown, latency/speed
- 🎨 **Modern UI** — dark theme, mobile-friendly

### 🚀 How to use

1. Open **https://vainblade.duckdns.org**
2. Copy the subscription link
3. Paste it into your client and refresh — done

**Clients:** v2rayNG · Hiddify · Happ · NekoBox / Throne · Streisand ·
Shadowrocket · Clash Meta (mihomo) · sing-box

### 🤝 Share servers

On the site, paste your subscription link or raw share links. The service
validates them and adds working ones to the shared pool — **anonymously, no
registration**.

### 🧩 Protocols & transports

| Protocols | Transports | Security |
|---|---|---|
| VLESS, VMess, Trojan, Shadowsocks, Hysteria2, TUIC | TCP, WebSocket, gRPC, xhttp, httpupgrade, h2 | Reality, TLS |

### ❓ FAQ

- **Is it free?** Yes, completely.
- **Registration?** No, fully anonymous.
- **Which client?** Any from the list — the right format is served automatically.

---

## 🇨🇳 中文

### 关于

**Community VPN Aggregator** 是一个共享的、持续更新的可用 VPN 服务器池。用户添加
自己的订阅和分享链接；服务实时检测其可用性，只保留有效的服务器。你只需**一个订阅
链接**，即可在客户端中获得数十个可用服务器，无需手动配置。

🔗 **服务：** **https://vainblade.duckdns.org**

### ✨ 功能

- 🔄 **按客户端自动选择格式** —— base64、sing-box JSON 或 Clash YAML
- ✅ **仅保留可用服务器** —— 通过 xray-knife 进行真实测试（速度、延迟、TTFB）
- ♻️ **稳定性窗口**（2-of-3 规则）
- 🛡️ **垃圾与无效节点过滤**
- 🔗 **每个订阅独立链接**
- 🚦 **防滥用**的按 IP 限制
- 📊 **实时统计**
- 🎨 **现代深色界面**，适配移动端

### 🚀 使用方法

1. 打开 **https://vainblade.duckdns.org**
2. 复制订阅链接
3. 粘贴到客户端并刷新订阅 —— 完成

**客户端：** v2rayNG · Hiddify · Happ · NekoBox / Throne · Streisand ·
Shadowrocket · Clash Meta (mihomo) · sing-box

### 🤝 分享服务器

在网站上粘贴你的订阅链接或分享链接。服务会验证并将可用的加入共享池 ——
**匿名，无需注册**。

### 🧩 协议与传输

VLESS、VMess、Trojan、Shadowsocks、Hysteria2、TUIC ·
TCP / WebSocket / gRPC / xhttp / httpupgrade / h2 · Reality / TLS

---

## 🙏 Built on

- [sing-box](https://github.com/SagerNet/sing-box) — universal proxy platform
- [Xray-core](https://github.com/XTLS/Xray-core) — Xray proxy platform
- [xray-knife](https://github.com/lilendian0x00/xray-knife) — link testing

## 📄 License

[MIT](LICENSE) · See [CHANGELOG.md](CHANGELOG.md) for version history.

<div align="center">

Made with ❤️ for the community · [vainblade.duckdns.org](https://vainblade.duckdns.org)

</div>
