# Mika Ads · Mike Kuznetsov · Mika Marketing

Система из 8 скиллов для Claude: запуск рекламы Meta (Facebook / Instagram) от анализа лендинга до ежедневных отчётов. Маркетолог принимает решения, Claude делает работу и после каждого шага показывает отчёт.

Автор: Михаил Кузнецов (Mike Kuznetsov), Mika Marketing · [mikaagency.com.ua](https://mikaagency.com.ua) · [Telegram](https://t.me/mihailfunnels)

## Скиллы

| Шаг | Скилл | Что делает | Скачать |
| --- | --- | --- | --- |
| 0 | ads-system-mike-kuznetsov-mika-marketing | Дирижёр: ведёт по шагам, создаёт документ проекта | [zip](https://github.com/jacksonjs30/mika-marketing-skills/raw/main/zip/ads-system-mike-kuznetsov-mika-marketing.zip) |
| 1-3 | landing-competitors-mike-kuznetsov-mika-marketing | Анализ лендинга, конкуренты, Ad Library | [zip](https://github.com/jacksonjs30/mika-marketing-skills/raw/main/zip/landing-competitors-mike-kuznetsov-mika-marketing.zip) |
| 4 | audience-research-mike-kuznetsov-mika-marketing | Аудитория: JTBD, боли, страхи, возражения, CJM | [zip](https://github.com/jacksonjs30/mika-marketing-skills/raw/main/zip/audience-research-mike-kuznetsov-mika-marketing.zip) |
| 4.5 | landing-page-mike-kuznetsov-mika-marketing | Лендинг по «Слоям ценности»: текст, дизайн, картинки, HTML | [zip](https://github.com/jacksonjs30/mika-marketing-skills/raw/main/zip/landing-page-mike-kuznetsov-mika-marketing.zip) |
| 5 | ad-creatives-mike-kuznetsov-mika-marketing | Креативы: ТЗ дизайнеру или сценарий видео | [zip](https://github.com/jacksonjs30/mika-marketing-skills/raw/main/zip/ad-creatives-mike-kuznetsov-mika-marketing.zip) |
| 5.5 | creative-pretest-mike-kuznetsov-mika-marketing | Претест готовых креативов через AI-аватары: что запускать | [zip](https://github.com/jacksonjs30/mika-marketing-skills/raw/main/zip/creative-pretest-mike-kuznetsov-mika-marketing.zip) |
| 6 | meta-ads-launch-mike-kuznetsov-mika-marketing | Сборка кампаний в кабинете Meta черновиком | [zip](https://github.com/jacksonjs30/mika-marketing-skills/raw/main/zip/meta-ads-launch-mike-kuznetsov-mika-marketing.zip) |
| 7 | ads-reporting-mike-kuznetsov-mika-marketing | Отчёты 00:00 / 08:00 / понедельник, алерты | [zip](https://github.com/jacksonjs30/mika-marketing-skills/raw/main/zip/ads-reporting-mike-kuznetsov-mika-marketing.zip) |

**Все 8 одним архивом:** [all-skills-mike-kuznetsov-mika-marketing.zip](https://github.com/jacksonjs30/mika-marketing-skills/raw/main/zip/all-skills-mike-kuznetsov-mika-marketing.zip) - внутри 8 отдельных zip. Распакуйте архив и загрузите в Claude каждый из 8 zip по очереди (Claude принимает один скилл на один zip).

## Установка (10 минут, один раз)

1. Скачайте 8 zip-файлов из таблицы выше.
2. claude.ai → **Customize → Skills → «+» → Upload a skill** → загрузите каждый zip. Проверьте, что все 8 включены.
3. **Customize → Connectors → Add custom connector** → `https://mcp.facebook.com/ads` → войдите через Facebook (нужно для шагов 6-7).
4. Подключите Google Sheets (для отчётов) и включите веб-поиск.

## Как запустить

Откройте новый чат и напишите:

> Запусти Mika Ads по лендингу https://ваш-сайт

Claude задаст уточняющие вопросы (гео, бюджет, цель), создаст документ проекта и пойдёт по шагам. После каждого шага - отчёт и вопрос «Утверждаю / Поправить».

| Что нужно | Что написать |
| --- | --- |
| Весь цикл | «Запусти Mika Ads по лендингу <ссылка>» |
| Продолжить в новом чате | «Продолжи проект Mika Ads <ссылка на документ>» |
| Только аудитория | «Исследуй аудиторию по сегментам: …» |
| Только креативы | «Придумай креативы для …» |
| Собрать кампанию | «Загрузи креативы: 1 кампания, 2 группы по $5, по 2 креатива» |
| Отчёт | «Отчёт по рекламе за вчера» |

## Безопасность

Кампании создаются только черновиком. Деньги начинают тратиться только после вашей явной команды на публикацию с подтверждением бюджета.
