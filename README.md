<div align="center">

# سلام، من کیان 👋

### سازندهٔ ابزارهای متن‌باز برای دسترسی آزاد به اینترنت

<br>

![Focus](https://img.shields.io/badge/Focus-Anti--Censorship-2ee6a6?style=for-the-badge)
![Open Source](https://img.shields.io/badge/100%25-Open_Source-22d3ee?style=for-the-badge)
![Made for](https://img.shields.io/badge/Made_for-Free_Internet-f5b945?style=for-the-badge)

<br>

`VLESS Reality` · `WARP` · `Shadowsocks` · `CDN Fronting` · `Tunneling` · `Telegram Bots` · `Apps Script`

</div>

---

## 🎯 چه کار می‌کنم؟

ابزارهای **متن‌باز، رایگان و قانونی** می‌سازم که به مردم کمک می‌کنند بدون محدودیت به اینترنت آزاد دسترسی داشته باشند — همه روی **سرور خودِ کاربر**، بدون نقطهٔ شکست مرکزی. تمرکزم روی سادگی (حتی برای کاربر غیرفنی)، پایداری، و امنیت است.

---

## 🚀 پروژه‌های اصلی

<table>
<tr>
<td width="50%" valign="top">

### ⭐ [kian_v2ray](https://github.com/kian-irani/kian_v2ray)
سازندهٔ کانفیگ **V2Ray روی سرور خودت** — VLESS Reality + WARP + Shadowsocks.
آی‌پی سرور را می‌زنی، یک دستور می‌گیری، و **لینک Subscription** آماده تحویل می‌گیری.

- 🔐 کلیدها در مرورگر خودت ساخته می‌شوند (هیچ‌چیز به ما نمی‌رسد)
- 🧷 نصب تک‌دستوری، مقاوم به قطع SSH، با نمایش زندهٔ مراحل
- 🔗 لینک Subscription برای هر کاربر (همهٔ کانفیگ‌ها خودکار و همیشه به‌روز)
- 🩹 WARP پایدار (WireGuard/MASQUE + بازگشت خودکار) + بهینه‌سازی سرعت BBR
- 🛠 نصب/حذف/آپدیت امن با rollback + خودتشخیصی مشکلات
- 👥 مدیریت کاربر و حجم از صفحه یا نرم‌افزار Kv2m

**[▶ صفحهٔ زنده](https://kian-irani.github.io/kian_v2ray/)**

</td>
<td width="50%" valign="top">

### 🌐 [MHRV — Full Tunnel](https://github.com/KIAN-IRANI/mhrv-setup-full-tunell)
راهنمای تعاملی راه‌اندازی **تونل کامل** از طریق Google Apps Script — بدون Root، استتارشده با TLS.

- تمام ترافیک دستگاه از تونل رد می‌شود
- معماری per-user، اشتراکی، با ربات تلگرام
- هزاران کاربر فعال

**[▶ صفحهٔ زنده](https://kian-irani.github.io/mhrv-setup-full-tunell/)**

### ☁️ [Zyrln](https://github.com/KIAN-IRANI/zyrln-setup)
راه‌اندازی سریع مبتنی بر **Cloudflare Worker** در حساب خودِ کاربر — مخصوص مرورگر، رایگان.

**[▶ صفحهٔ زنده](https://kian-irani.github.io/zyrln-setup/)**

</td>
</tr>
</table>

| پروژه | توضیح |
|------|-------|
| ☁️ [Kian-CDN-Netlify](https://github.com/KIAN-IRANI/Kian-CDN-Netlify) | فرانتِ CDN روی Netlify برای اتصال پایدارتر، حتی وقتی آی‌پی سرور فیلتر شده |
| 🤖 [Jarvis-android](https://github.com/KIAN-IRANI/Jarvis-android) | اپ اندرویدی با CI/CD خودکار (ساخت APK روی push) |

---

## ⚙️ معماری و رویکرد

```
کاربر (مرورگر یا نرم‌افزار)
   │  کلید و کانفیگ همان‌جا ساخته می‌شود (هیچ‌چیز به سرور ما نمی‌رود)
   ▼
سرور خودِ کاربر (Ubuntu)
   │  نصب خودکار: Docker + Xray + WARP
   ▼
🌍 اینترنت آزاد
```

- **بدون نقطهٔ شکست مرکزی:** هر کاربر سرور و آی‌پی خودش را دارد → مقیاس‌پذیر و مقاوم.
- **حریم خصوصی:** کلیدها سمت کاربر ساخته می‌شوند؛ هیچ راز/توکنی در مخزن‌ها نیست.
- **سادگی:** طراحی‌شده تا حتی کاربر غیرفنی با چند کلیک و کپی‌پیست راه بیفتد.

---

## 💬 کانال‌ها و ربات‌ها

<div align="center">

[![Channel](https://img.shields.io/badge/Channel-kian__irani__cdn__f-229ED9?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/kian_irani_cdn_f)
[![Support](https://img.shields.io/badge/Support-Kian__irani__t-229ED9?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/Kian_irani_t)

[![MHRV Bot](https://img.shields.io/badge/Bot-Mhrv__script__bot-2ee6a6?style=flat-square&logo=telegram&logoColor=white)](https://t.me/Mhrv_script_bot)
[![Zyrln Bot](https://img.shields.io/badge/Bot-Zyrln__script__bot-2ee6a6?style=flat-square&logo=telegram&logoColor=white)](https://t.me/Zyrln_script_bot)

</div>

---

## 🧰 ابزارها و تکنولوژی‌ها

<div align="center">

![Bash](https://img.shields.io/badge/Bash-121a24?style=flat-square&logo=gnubash&logoColor=2ee6a6)
![Python](https://img.shields.io/badge/Python-121a24?style=flat-square&logo=python&logoColor=4dabcf)
![JavaScript](https://img.shields.io/badge/JavaScript-121a24?style=flat-square&logo=javascript&logoColor=f7df1e)
![Docker](https://img.shields.io/badge/Docker-121a24?style=flat-square&logo=docker&logoColor=22d3ee)
![Linux](https://img.shields.io/badge/Linux-121a24?style=flat-square&logo=linux&logoColor=f5b945)
![Cloudflare](https://img.shields.io/badge/Cloudflare-121a24?style=flat-square&logo=cloudflare&logoColor=f48120)
![Caddy](https://img.shields.io/badge/Caddy-121a24?style=flat-square&logo=caddy&logoColor=2ee6a6)
![GitHub Actions](https://img.shields.io/badge/CI%2FCD-121a24?style=flat-square&logo=githubactions&logoColor=22d3ee)
![SQLite](https://img.shields.io/badge/SQLite-121a24?style=flat-square&logo=sqlite&logoColor=4dabcf)

</div>

---

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=KIAN-IRANI&show_icons=true&hide_border=true&bg_color=0a0d12&title_color=2ee6a6&icon_color=22d3ee&text_color=c4d2df)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=KIAN-IRANI&layout=compact&hide_border=true&bg_color=0a0d12&title_color=2ee6a6&text_color=c4d2df&langs_count=8)

<br>

> 🔐 همهٔ پروژه‌ها متن‌بازند و هیچ رمز/کلیدی در مخزن‌ها قرار نمی‌گیرد.

**ساخته‌شده با ❤️ برای اینترنت آزاد**

</div>
