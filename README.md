<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=7C3AED&height=200&section=header&text=Teprans&fontSize=80&fontColor=ffffff&fontAlignY=38&desc=Мессенджер+нового+поколения&descAlignY=60&descSize=20&descColor=D0BCFF" width="100%">

<br>

[![Version](https://img.shields.io/badge/Version-1.0.0-7C3AED?style=for-the-badge&logo=android&logoColor=white)](https://github.com/Teprans-messages/teprans-messenger/releases)
[![Platform](https://img.shields.io/badge/Platform-Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)](#)
[![License](https://img.shields.io/badge/License-Private-red?style=for-the-badge&logo=lock&logoColor=white)](#)
[![E2EE](https://img.shields.io/badge/Encryption-E2EE-blueviolet?style=for-the-badge&logo=shield&logoColor=white)](#)
[![Free](https://img.shields.io/badge/Price-FREE-success?style=for-the-badge&logo=heart&logoColor=white)](#)

<br>

<a href="https://github.com/Teprans-messages/teprans-messenger/releases/download/v1.0.0/teprans.apk">
  <img src="https://img.shields.io/badge/📥_Download_APK-v1.0.0-7C3AED?style=for-the-badge" alt="Download">
</a>

<br><br>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Space+Grotesk&weight=700&size=28&duration=3000&pause=1000&color=C084FC&center=true&vCenter=true&multiline=true&repeat=true&width=600&height=100&lines=🔒+E2E+Шифрование;+🎤+Голосовые+сообщения;+📹+Видеозвонки+WebRTC;+👥+Группы+и+каналы)](https://git.io/typing-svg)

</div>

---

## 💬 О Teprans

**Teprans** — это быстрый, красивый и безопасный мессенджер для Android с полным E2E-шифрованием. Создан как альтернатива Telegram с акцентом на конфиденциальность и красоту интерфейса.

> 📡 **Real-time** WebSocket общение с Redis Pub/Sub  
> 🔒 **E2EE** RSA-2048 + AES-256 шифрование  
> 📱 **Material 3** дизайн, фиолетовая тема  
> ☁️ **S3** хранилище для медиафайлов  

---

## ✨ Возможности

<table>
<tr>
<td width="50%">

### 🔒 Безопасность
- End-to-End шифрование (RSA-2048 + AES-256)
- JWT + Refresh Token аутентификация
- 2FA через email OTP
- Rate limiting + Helmet.js
- Security headers + XSS защита

### 📱 Андроид приложение
- Material 3 + Jetpack Compose
- Фиолетовая тема, тёмный режим
- MVVM + Hilt DI + Room + DataStore
- Анимации и плавные переходы
- RU/EN локализация

</td>
<td width="50%">

### 💬 Сообщения
- Текст + изображения + видео + файлы
- 🎤 Голосовые сообщения
- 😀 Стикеры и emoji
- ↩️ Reply (проведи для ответа)
- Markdown (**bold**, *italic*, `code`)
- ✓✓ Двойные галочки и read receipts
- Push-уведомления (FCM)

### 👥 Группы
- Создание групп с много-выбором
- Роли: Admin / Member
- Ик участников (admin only)
- Закрепление сообщений
- Экран Group Info

</td>
</tr>
</table>

---

## 🚀 Технологии

<div align="center">

### Backend
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![WebSocket](https://img.shields.io/badge/WebSocket-010101?style=for-the-badge&logo=socket.io&logoColor=white)

### Android
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)
![Jetpack Compose](https://img.shields.io/badge/Jetpack_Compose-4285F4?style=for-the-badge&logo=jetpackcompose&logoColor=white)
![Material3](https://img.shields.io/badge/Material_3-757575?style=for-the-badge&logo=materialdesign&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)

### DevOps
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![AWS S3](https://img.shields.io/badge/S3_Storage-FF9900?style=for-the-badge&logo=amazons3&logoColor=white)
![PM2](https://img.shields.io/badge/PM2-2B037A?style=for-the-badge&logo=pm2&logoColor=white)

</div>

---

## 📥 Скачать

<div align="center">

| Сведение | Значение |
|---|---|
| 📱 **Платформа** | Android 5.0+ |
| 📦 **Размер** | 40 МБ |
| 💜 **Версия** | v1.0.0 |
| 💰 **Цена** | Бесплатно |

<br>

[![Download APK](https://img.shields.io/badge/%E2%AC%87%EF%B8%8F_Download_Teprans_APK-v1.0.0-7C3AED?style=for-the-badge&logo=android)](https://github.com/Teprans-messages/teprans-messenger/releases/download/v1.0.0/teprans.apk)

**Установка:**
1. Нажми кнопку Download выше
2. Открой файл `.apk` на телефоне
3. Разреши установку из неизвестных источников в настройках
4. 🚀 Пользуйся!

</div>

---

## 📊 Архитектура

```
teprans/
├── android/                 # 📱 Android приложение (Kotlin + Compose)
│   ├── ui/screens/          # Экраны: Chat, Groups, Settings...
│   ├── data/repository/     # Репозитории: Auth, Chat, User
│   └── firebase/            # FCM Push уведомления
├── backend/                 # ⚙️ Node.js сервер
│   ├── src/controllers/     # Auth, Chat, User контроллеры
│   ├── src/websocket/       # WebSocket + Redis Pub/Sub
│   └── src/db/              # PostgreSQL схема и миграции
└── .github/workflows/       # ✅ CI/CD пайплайны
```

---

## 🛣️ Дорожная карта

| Этап | Статус | Описание |
|---|---|---|
| **MVP** | ✅ Готово | Чаты, регистрация, JWT, WebSocket |
| **Beta** | ✅ Готово | Группы, медиа, звонки, голосовые |
| **Growth** | 🔜 План | Бизнес-аккаунты, боты, аналитика |
| **Global** | 🔜 План | Desktop, 1M+ пользователей |

---

<div align="center">

💬 **Teprans** — Общайся без границ 🚀

<img src="https://capsule-render.vercel.app/api?type=waving&color=7C3AED&height=120&section=footer" width="100%">

</div>