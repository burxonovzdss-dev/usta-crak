# Usta Crak — PWA prototipi

Bu papka Usta Crak slayd ilovasining boshlang‘ich, brauzerda ishlaydigan prototipidir.

## Hozir ishlaydi
- Mobil va kompyuterga mos interfeys
- Brauzer ichida 3 ta taqdimot limiti
- Har bir taqdimotda 20 tagacha slayd
- Slayd qo‘shish va taqdimotni o‘chirish
- PDF uchun brauzerning Print / Save as PDF funksiyasi
- Slayd pastida “Usta Crak” belgisi
- PWA manifest va service worker boshlang‘ich fayllari

## Muhim cheklovlar
Bu hali internetda joylashtirilgan tayyor 24/7 xizmat emas. Ma’lumotlar hozir faqat bitta brauzerning localStorage xotirasida saqlanadi. Haqiqiy foydalanuvchi akkauntlari, maxfiy admin kabineti, serverda limit tekshiruvi, bulutli saqlash va PPTX eksportini ishonchli qilish uchun backend kerak. Admin huquqini faqat sahifadan yashirish yetarli emas; server tomonda tekshirish zarur.

## PWA sifatida sinash
PWA o‘rnatish va service worker uchun HTTPS orqali hosting kerak. Fayllarni hostingga yuklang (masalan, statik sayt hostingi). `file://` orqali ochilganda o‘rnatish funksiyasi ishlamasligi mumkin.

## Keyingi ishlab chiqish bosqichi
1. Hosting va domen
2. Auth / foydalanuvchi akkauntlari
3. Serverdagi rol va admin ruxsatlari
4. Taqdimotlarni bulutda saqlash va 3 × 20 limitini serverda tekshirish
5. PPTX/PDF eksporti va rasm yuklash
6. AI slayd generatsiyasi uchun bepul kvota yoki API ulash
