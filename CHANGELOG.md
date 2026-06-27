# Changelog

All notable changes to **Community VPN Aggregator** are documented here.

Format based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/);
project follows [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

🇷🇺 [Русский](#-русский) · 🇬🇧 [English](#-english) · 🇨🇳 [中文](#-中文)

---

## 🇬🇧 English

### [1.0.0] — 2026-06-17

#### Added
- 🎉 Initial release
- 🔄 Multi-format subscriptions: sing-box JSON, Base64 links, plain text — with
  automatic format detection and conversion
- 🌐 Output auto-selected per client: Clash YAML (Clash/Clash Meta), JSON
  (Happ/Throne/NekoBox), Base64 (v2rayN/Shadowrocket)
- 📊 Protocols: VLESS (Reality/TLS), VMess, Shadowsocks, Trojan, Hysteria2 —
  transports TCP, WebSocket, gRPC, xhttp/splithttp, httpupgrade, h2/http
- 🔍 Real liveness testing (xray-knife): connectivity, speed (Mbps), latency
  (ms), TTFB, stability window (2-of-3), auto-prune of dead links
- 🛡️ Spam filtering: test/empty servers removed, name URL-decoding
- 🚦 Per-IP rate limiting (configurable)
- 🔗 Individual subscription endpoints (unique per-subscription URL)
- 📈 Live stats dashboard: totals, protocol breakdown, latency & speed
- 🎨 Modern dark UI: glassmorphism, animated background, responsive mobile
- 🔒 Security: SSRF protection (DNS pinning), port whitelist (80/443), public-IP
  validation, redirect validation, request size limit

#### Changed
- Multi-outbound support: protocol-based outbound filtering
- Global deduplication across the whole pool

#### Fixed
- xhttp/splithttp links now include path, host, mode and extra parameters
- VMess conversion to v2rayN base64 JSON format
- Server-name URL decoding for international characters

#### Security
- SSRF protection with DNS pinning (anti DNS-rebinding)
- Request body size limit
- Rate limiting against abuse

---

## 🇷🇺 Русский

### [1.0.0] — 2026-06-17

#### Добавлено
- 🎉 Первый релиз
- 🔄 Мульти-формат подписок: sing-box JSON, Base64-ссылки, plain text — с
  автоопределением формата и конвертацией
- 🌐 Формат вывода подбирается под клиент: Clash YAML (Clash/Clash Meta), JSON
  (Happ/Throne/NekoBox), Base64 (v2rayN/Shadowrocket)
- 📊 Протоколы: VLESS (Reality/TLS), VMess, Shadowsocks, Trojan, Hysteria2 —
  транспорты TCP, WebSocket, gRPC, xhttp/splithttp, httpupgrade, h2/http
- 🔍 Реальная проверка работоспособности (xray-knife): подключение, скорость
  (Mbps), задержка (ms), TTFB, окно стабильности (2-из-3), авто-удаление мёртвых
- 🛡️ Фильтр спама: тестовые/пустые ноды удаляются, URL-декодирование имён
- 🚦 Лимит добавления с одного IP (настраивается)
- 🔗 Отдельные endpoint'ы подписок (уникальный URL на каждую)
- 📈 Дашборд статистики: всего, разбивка по протоколам, задержка и скорость
- 🎨 Современный тёмный UI: glassmorphism, анимированный фон, адаптив
- 🔒 Безопасность: SSRF-защита (DNS pinning), белый список портов (80/443),
  валидация публичных IP, валидация редиректов, лимит размера запроса

#### Изменено
- Поддержка мульти-outbound: фильтрация аутбаундов по протоколу
- Глобальная дедупликация по всему пулу

#### Исправлено
- xhttp/splithttp ссылки теперь включают path, host, mode и extra
- Конвертация VMess в формат v2rayN base64 JSON
- URL-декодирование имён серверов для международных символов

#### Безопасность
- SSRF-защита с DNS pinning (анти DNS-rebinding)
- Лимит размера тела запроса
- Rate limiting против злоупотреблений

---

## 🇨🇳 中文

### [1.0.0] — 2026-06-17

#### 新增
- 🎉 首次发布
- 🔄 多格式订阅：sing-box JSON、Base64 链接、纯文本 —— 自动检测格式并转换
- 🌐 按客户端自动选择输出：Clash YAML（Clash/Clash Meta）、JSON
  （Happ/Throne/NekoBox）、Base64（v2rayN/Shadowrocket）
- 📊 协议：VLESS（Reality/TLS）、VMess、Shadowsocks、Trojan、Hysteria2 ——
  传输 TCP、WebSocket、gRPC、xhttp/splithttp、httpupgrade、h2/http
- 🔍 真实可用性测试（xray-knife）：连接、速度（Mbps）、延迟（ms）、TTFB、
  稳定性窗口（2-of-3）、自动清除死链接
- 🛡️ 垃圾过滤：删除测试/空节点，名称 URL 解码
- 🚦 按 IP 限速（可配置）
- 🔗 每个订阅独立端点（唯一 URL）
- 📈 实时统计面板：总数、协议细分、延迟与速度
- 🎨 现代深色界面：玻璃拟态、动画背景、响应式
- 🔒 安全：SSRF 保护（DNS 固定）、端口白名单（80/443）、公共 IP 验证、
  重定向验证、请求大小限制

#### 更改
- 多出站支持：基于协议的出站过滤
- 全局去重（覆盖整个池）

#### 修复
- xhttp/splithttp 链接现包含 path、host、mode 和 extra
- VMess 转换为 v2rayN base64 JSON 格式
- 国际字符的服务器名称 URL 解码

#### 安全
- 带 DNS 固定的 SSRF 保护（防 DNS 重绑定）
- 请求体大小限制
- 防滥用限速

---

## Version format

`MAJOR.MINOR.PATCH` — incompatible changes / new features / bug fixes.
