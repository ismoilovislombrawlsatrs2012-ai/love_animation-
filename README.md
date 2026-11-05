# Yuragimdan

Kod matritsasi ko‘z shakliga kiradi, tasvir ko‘z qorachig‘iga yaqinlashadi va yurak belgilar bilan qorachiq ichida chiziladi. Kiritilgan ism videoning boshida va kodli yurak markazida ko‘rinadi. Multfilm yoki rasmli ko‘z ishlatilmaydi. Animatsiya Web Audio API orqali yaratilgan kuy bilan ijro etiladi; video eksporti brauzer qo‘llaydigan MP4 yoki WebM formatida amalga oshadi.

## Ishga tushirish

`index.html` faylini zamonaviy brauzerda oching yoki loyiha papkasidan statik web-server ishga tushiring. Ismni kiriting va animatsiyani ko‘ring. **Video yaratish** tugmasi 12 soniyalik, 9:16 formatdagi animatsiyani yozadi; tayyor faylni saqlash tugmasi yozuv tugagach ko‘rinadi.

Loyiha framework, tashqi resurs yoki backend talab qilmaydi. Audio va video yozib olish uchun brauzer JavaScript, Web Audio, Canvas `captureStream` va `MediaRecorder` imkoniyatlarini qo‘llab-quvvatlashi kerak. Yangi Safari/iOS, Chrome/Android hamda Chrome/Edge/Windows brauzerlarida MP4 yoki WebM formati avtomatik tanlanadi. HTTPS yoki `localhost` orqali ishga tushirish tavsiya etiladi.

## Onlayn havola

GitHub Pages sayti: <https://ismoilovislombrawlsatrs2012-ai.github.io/love_animation-/>

`main` yoki animatsiya branchiga o‘zgarishlar yuborilganda sayt avtomatik yangilanadi.