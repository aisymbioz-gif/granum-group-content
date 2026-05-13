# План распространения: 1 исходник → 5 форматов → 3+ канала

## Исходник
SEO-статья «Как выбрать гранит для памятника: 7 критериев качества» (1500 слов)

## Производные форматы
| Формат | Файл | Канал | Расписание |
|---|---|---|---|
| Статья | article-granit-pamyatnik.md | Блог сайта granum-group.ru | День 1 |
| Telegram пост | telegram-post.md | Telegram канал | День 1 + 18:00 |
| Thread | twitter-thread.md | VK / Дзен | День 2-3 (по 1 в день) |
| Email | email-lead-nurture.md | Авто-серия после заявки | Триггер: новая заявка |
| FAQ | faq-site.md | Сайт (schema.org FAQPage) | День 1 |

## CTA
Единый CTA: «Размер + месторождение в WhatsApp — 3 варианта с фото за 2 минуты»

## UTM-метки
- ?utm_source=blog&utm_medium=article&utm_campaign=7criteria
- ?utm_source=telegram&utm_medium=post&utm_campaign=7criteria
- ?utm_source=vk&utm_medium=thread&utm_campaign=7criteria
- ?utm_source=email&utm_medium=nurture&utm_campaign=7criteria

## Целевые KPI на пакет
- Просмотры суммарно: 3000+
- CTR в WhatsApp: > 2%
- Заявок из контента за 14 дней: 5+

## Handoff to Marketer
```json
{
  "from": "content",
  "to": "marketer",
  "type": "content_ready",
  "payload": {
    "topic": "7 критериев выбора гранита для памятника",
    "formats": ["article", "telegram_post", "vk_thread", "email", "faq"],
    "channels": ["website_blog", "telegram", "vk", "dzen", "email_autoflow"],
    "cta": "WhatsApp: размер + месторождение → 3 варианта с фото за 2 мин",
    "utm_campaign": "7criteria"
  },
  "summary": "Пакет из 5 форматов на тему выбора гранита для памятника. Высокий коммерческий интент, единый CTA на WhatsApp.",
  "evidence": ["ГОСТ 9479-2011", "Каталог Карельский гранит"],
  "confidence": 0.82
  }
}
```
