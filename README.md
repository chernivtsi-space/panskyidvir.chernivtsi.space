# Панський Двір 2

Live site: https://panskyidvir.chernivtsi.space

## About
Панський Двір 2 — готельний комплекс у Чернівцях. Односторінковий лендинг. Фото закладу немає (`photos_source: null`), тому hero типографічний (CSS/SVG), а єдині фото — міста Чернівців з Pexels (див. Photos).

## Hero concept
Геральдичний щит із монограмою «ПД» і римською «II» на світлому медальйоні — «панський» характер назви без вигаданої історичності.

## Amenities (verified, list.json)
- Безкоштовний Wi‑Fi
- Цілодобова рецепція
- Тераса
- Бар
- Кав’ярня
- Камера зберігання багажу
- Приміщення для зустрічей і банкетів
- Кондиціонер

## Check-in / check-out
не встановлено

## Reviews
Booking.com 9.3/10 (276), Google 4.5/5 (22). Знімок на 30.09.2026, платформи окремо, без aggregateRating.

## Contact
- Phone: +380 75 262 0013
- Email: 13sheptyckogo@gmail.com
- Official site: https://panskiy-dvir.com.ua/
- Booking.com: https://www.booking.com/hotel/ua/pans-kii-dvir-2.uk.html
- Google Maps: https://maps.google.com/?cid=14200027544103512104
- Address: вул. Андрія Шептицького, 13, Чернівці

## Not published
Час заїзду/виїзду, зірковість, Instagram, історичність будівлі, «центр міста», місткість залів. 20 номерів — Planet of Hotels (medium), у schema не передано. Google 4.5 має лише 22 відгуки, тому Booking.com показано першим.

## Forms
HotelOS (`ch-panskyidvir`): `stay-request` (проживання), `event-request` (зустрічі й банкети). Документ `hotels/ch-panskyidvir` у Firestore треба створити вручну, інакше правила відхилять заявки.

## Photos
Лише фото міста (не готелю), з Pexels, підключені за прямими посиланнями images.pexels.com (без копій у репо), з підписами та авторами на сторінці:

- Резиденція буковинських митрополитів, нині Чернівецький університет: pexels.com/photo/12961411 (Valeriia Harbuz)
- Цегляні арки: pexels.com/photo/38163642 (Natalia Sevruk)
- Чернівецький дворик: pexels.com/photo/17265321 (Андрій Копічевський)

## SEO
Title і description з маніфесту, canonical, Open Graph, `geo.*`, JSON-LD `Hotel` лише з підтвердженими полями (без numberOfRooms, starRating, aggregateRating), `robots.txt`, `sitemap.xml`, `404.html`.
