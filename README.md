# ☁️ Cloud Browser

**Cloud Browser** — десктопный браузер на Electron с тёмным стеклянным интерфейсом, вкладками, боковой панелью Cloud Space и встроенными инструментами приватности.

<p align="center">
  <a href="https://github.com/XOXDabian/Cloud-Browser/releases/latest">
    <img src="https://img.shields.io/badge/Скачать-Windows-438DFF?style=for-the-badge&logo=windows&logoColor=white" alt="Скачать для Windows">
  </a>
  <a href="https://github.com/XOXDabian/Cloud-Browser/releases">
    <img src="https://img.shields.io/github/v/release/XOXDabian/Cloud-Browser?style=for-the-badge&label=Последний%20релиз" alt="Последний релиз">
  </a>
  <a href="https://github.com/XOXDabian/Cloud-Browser">
    <img src="https://img.shields.io/github/license/XOXDabian/Cloud-Browser?style=for-the-badge" alt="Лицензия">
  </a>
</p>

---

## Скачать Cloud Browser

**[Открыть все версии в GitHub Releases](https://github.com/XOXDabian/Cloud-Browser/releases)**

Последний опубликованный релиз на момент обновления этой страницы — **Cloud Browser V0.4**.

- **[Скачать установщик Windows V0.4 (.exe)](https://github.com/XOXDabian/Cloud-Browser/releases/download/new/Cloud.Browser.Setup.0.4.exe)**
- [Открыть описание релиза V0.4](https://github.com/XOXDabian/Cloud-Browser/releases/tag/new)
- [Посмотреть предыдущие версии](https://github.com/XOXDabian/Cloud-Browser/releases)

Перед установкой скачивайте файлы только со страницы официальных релизов этого репозитория.

## Languages

Процентное распределение по скриншоту GitHub Languages:

<p>
  <img src="https://img.shields.io/badge/Python-39.1%25-3572A5?style=for-the-badge&logo=python&logoColor=white" alt="Python 39.1%">
  <img src="https://img.shields.io/badge/CSS-20.3%25-663399?style=for-the-badge&logo=css3&logoColor=white" alt="CSS 20.3%">
  <img src="https://img.shields.io/badge/HTML-19.1%25-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML 19.1%">
  <img src="https://img.shields.io/badge/JavaScript-17.1%25-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111111" alt="JavaScript 17.1%">
  <img src="https://img.shields.io/badge/Batchfile-4.4%25-C1F12E?style=for-the-badge&logo=windows-terminal&logoColor=111111" alt="Batchfile 4.4%">
</p>

- **Python** — логика и вспомогательные инструменты проекта.
- **CSS** — стили интерфейса.
- **HTML** — структура пользовательского интерфейса.
- **JavaScript** — интерактивность и логика браузера.
- **Batchfile** — вспомогательные Windows-скрипты.

> Проценты перенесены с предоставленного скриншота. Это визуальные бейджи в README, а не автоматически рассчитываемая диаграмма GitHub Linguist. GitHub строит собственную диаграмму по языкам файлов, доступных в репозитории.


## Возможности

По описанию проекта и опубликованных релизов:

| Возможность | Описание |
| --- | --- |
| Вкладки и навигация | Открытие страниц, адресная строка, переход назад и вперёд, обновление |
| Стеклянный интерфейс | Минималистичное оформление с тёмной темой |
| Cloud Space | Боковая панель с историей, сохранёнными страницами и загрузками |
| AdBlock | Встроенная базовая блокировка рекламы и управление фильтрами |
| Приватность | Настройки защиты, управление доверенными и заблокированными доменами |
| Пароли | Локальное сохранение паролей и их повторное заполнение |
| Закладки | Сохранение избранных сайтов |
| Расширения | Поддержка расширений описана начиная с версии 0.3; совместимость зависит от типа расширения |
| Быстрые ссылки | Переход к часто используемым сайтам |

Наличие пункта в этом списке не означает, что каждая функция прошла независимое тестирование во всех сценариях. Если обнаружили неисправность, сообщите о ней через раздел Issues.

## Что нового в V0.4

Согласно описанию [релиза V0.4](https://github.com/XOXDabian/Cloud-Browser/releases/tag/new):

- Расширена базовая блокировка подозрительных и вредоносных доменов.
- Добавлено управление списками доверенных и заблокированных доменов.
- Улучшено отображение состояния безопасности сайта.
- Обновлены фильтры рекламы и трекеров.
- Улучшена проверка устанавливаемых расширений.
- Обновлены статусы вкладок, уведомления и элементы интерфейса.

## Скриншоты

Скриншоты интерфейса и демонстрации возможностей будут добавляться сюда по мере обновления проекта.

## Сообщить об ошибке или предложить улучшение

Нашли проблему с вкладками, загрузками, контекстным меню, AdBlock или другим компонентом?

1. Откройте [Issues](https://github.com/XOXDabian/Cloud-Browser/issues).
2. Создайте новое обращение.
3. Укажите версию браузера и версию Windows.
4. Опишите шаги, после которых возникает проблема.
5. При возможности приложите скриншот и текст ошибки из консоли.

Для предложений по развитию используйте тот же раздел Issues.

## Исходный код и запуск для разработчиков

Cloud Browser создан на Electron. Однако **в текущей ветке `main` исходные файлы приложения и `package.json` пока не опубликованы**: сейчас в ней доступны README и LICENSE.

Поэтому инструкции `npm install`, запуск проекта и сборку EXE нельзя проверить по содержимому текущей ветки. Чтобы разработчики могли воспроизвести сборку, необходимо добавить исходный проект, файл зависимостей и точные команды из используемого `package.json`.

Если вы хотите помочь с разработкой, сначала проверьте доступные материалы в [репозитории](https://github.com/XOXDabian/Cloud-Browser) и [релизах](https://github.com/XOXDabian/Cloud-Browser/releases).

## Лицензия

Проект распространяется на условиях лицензии, указанной в файле [LICENSE](./LICENSE).

---

<p align="center">
  **Cloud Browser — интернет становится проще.**
  <br>
  <a href="https://github.com/XOXDabian/Cloud-Browser/releases">Скачать</a> ·
  <a href="https://github.com/XOXDabian/Cloud-Browser/issues">Сообщить об ошибке</a> ·
  <a href="https://github.com/XOXDabian/Cloud-Browser">GitHub</a>
</p>
