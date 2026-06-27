# 🌐 Community VPN Aggregator

Бесплатный сервис, где сообщество складывает рабочие VPN-серверы в общий пул:
**каждый делится своими подписками — каждый получает доступ ко всем проверенным серверам.**

🔗 **Сервис:** https://vlesscommunity.online

> ℹ️ Это витрина проекта — что это и как пользоваться. Исходный код и внутренняя
> инфраструктура здесь не публикуются.

---

## 🇷🇺 Русский

### Что это

Один общий, постоянно обновляемый пул рабочих серверов. Люди добавляют свои
подписки и share-ссылки, сервис проверяет их на работоспособность и оставляет в
пуле только живые. Ты получаешь одну ссылку-подписку — и сразу десятки рабочих
серверов в своём клиенте.

### Как пользоваться (получить серверы)

1. Открой **https://vlesscommunity.online**
2. Скопируй ссылку подписки с сайта
3. Вставь её в свой VPN-клиент и обнови подписку

Формат сервис подбирает под твой клиент автоматически (base64 / sing-box / Clash) —
настраивать ничего не нужно.

**Поддерживаемые клиенты:** v2rayNG, Hiddify, Happ, NekoBox / Throne, Streisand,
Shadowrocket, Clash Meta (mihomo), sing-box.

### Как поделиться серверами

Прямо на сайте вставь ссылку своей подписки **или** сами share-ссылки
(`vless://`, `vmess://`, `trojan://`, `ss://`, `hysteria2://`, `tuic://`).
Сервис проверит их и добавит рабочие в общий пул — анонимно, без регистрации.

### Что в пуле

- **Протоколы:** VLESS, VMess, Trojan, Shadowsocks, Hysteria2, TUIC
- **Только живые серверы** — каждый проходит реальную проверку работоспособности,
  мёртвые отсеиваются
- **Фильтр мусора и спама**
- **Автообновление** пула

### FAQ

- **Это бесплатно?** Да.
- **Нужна регистрация?** Нет, всё анонимно.
- **Какой клиент выбрать?** Любой из списка выше — сервис сам отдаёт подходящий формат.

---

## 🇬🇧 English

**Community VPN Aggregator** is a free service with one shared, continuously
updated pool of working VPN servers. People add their subscriptions, the service
checks them and keeps only the live ones — you get a single subscription link with
dozens of working servers in your client.

🔗 **Service:** https://vlesscommunity.online

**How to use:** open the site → copy the subscription link → paste it into your
client and refresh. The right format (base64 / sing-box / Clash) is served
automatically — no setup needed.

**Supported clients:** v2rayNG, Hiddify, Happ, NekoBox / Throne, Streisand,
Shadowrocket, Clash Meta (mihomo), sing-box.

**Share servers:** on the site, paste your subscription link or raw share links
(`vless://`, `vmess://`, `trojan://`, `ss://`, `hysteria2://`, `tuic://`). The
service validates them and adds the working ones to the shared pool — anonymously,
no registration.

**Protocols:** VLESS, VMess, Trojan, Shadowsocks, Hysteria2, TUIC. Only live,
validated servers; spam filtered; pool auto-refreshed.

---

## 🙏 Built on

- [sing-box](https://github.com/SagerNet/sing-box)
- [Xray-core](https://github.com/XTLS/Xray-core)

## 📄 License

MIT — see [LICENSE](LICENSE).

---

Made with ❤️ for the community
