# Медиа для лендинга

Складывайте фото и видео в эту папку (можно по подпапкам — по блокам),
затем пропишите их в объекте `MEDIA` в начале `<script>` в `index.html`.

Пример:

```js
const MEDIA = {
  space: [
    { src: 'media/space/01.jpg', caption: 'Зал на Кутузовском' },
    { video: 'media/space/light.mp4', poster: 'media/space/light.jpg', caption: 'Свет у рабочего места' },
  ],
};
```

Ключи блоков: hero, income, brand, clients, locations, team, service, space,
guests, creative, shows, personal, schedule, growth, stories, history, academy.

Пока в блоке нет файлов, в карусели показываются заглушки с подсказкой,
какой контент туда лучше поставить.

Рекомендации:
- фото: JPG/WebP, по длинной стороне 1600–2000 px, до ~400 КБ;
- видео: MP4 (H.264), без звука, 10–30 с, до ~8 МБ, плюс постер-кадр JPG;
- вертикальные кадры 4:5 — для блоков с текстом сбоку, горизонтальные 16:9 — для широких каруселей.
