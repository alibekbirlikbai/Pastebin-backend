# Pastebin-project
inspired by - https://pastebin.com/

Pastebin - приложение в котором пользователи могут создавать обычные блоки текста, сохранять их в системе, и делиться этими ссылками (текстом) с другими пользователями.

## Info по веткам:
- _**main**_ - _Production_ ветка, стабильные (завершенные) версии проекта 
  - (только коммиты из _**release**_)
- _**release**_ - ветка _Тестирования_, подготовка новых релизов к _Production_ (v1.*)
  - (только коммиты из _**develop**_)
- _**develop**_ - _Development_ ветка, интеграция всех изменений (Фич) для релиза
  - (только коммиты из _**feature/***_)
- _**feature/***_ - ветка разработки новых функционалов и улучшений 


## Фичи:
- [x] _~~1. Пользователь может создать блок Текста, и загрузить его в систему;~~_
- [x] ~~2. Система должна генерировать уникальный URL адрес (ссылку) на этот блок текста;~~
- [x] ~~3. Пользователь может отправить эту ссылку другому пользователю, который перейдя по ней, увидит тот же блок текста;~~
- [ ] 4. Блоки текста и ссылки деактивируются через какое-то время и удаляются из системы;
  - [ ] 4.1. Пользователь может сам указать когда именно это происходит;

(Optional):
- [ ] 5. Можно определять Категорию вводимого блока текста;
  - [ ] 5.1. Поиск по Категории;
- [ ] 6. Можно определять Пароли на ссылки;
