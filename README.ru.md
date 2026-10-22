<p align="left">
  <a href="README.md"><img src="https://shieldcn.dev/badge/English.svg?variant=outline" /></a>
  <a href="README.ru.md"><img src="https://shieldcn.dev/badge/%D0%A0%D1%83%D1%81%D1%81%D0%BA%D0%B8%D0%B9-0078D4.svg" /></a>
</p>

<div align="center">

  # YouTubeMusic-WINUI

  **Современный десктопный клиент для YouTube Music на базе WinUI 3 и Microsoft Edge WebView2.**

  <br />

  <p>
    <img src="https://shieldcn.dev/badge/Windows%2010%20%7C%2011-0078D4.svg?logo=windows" />
    <img src="https://shieldcn.dev/badge/WinUI%203-512BD4.svg" />
    <img src="https://shieldcn.dev/badge/.NET%208.0-512BD4.svg" />
    <img src="https://shieldcn.dev/badge/WebView2-0078D7.svg?logo=microsoftedge" />
    <img src="https://shieldcn.dev/badge/MIT-2ea44f.svg" />
  </p>

</div>

---

## О приложении

> YouTubeMusic-WINUI объединяет веб-интерфейс YouTube Music с нативной средой Windows, дополняя его материалами Fluent Design из Windows 11, синхронизированными текстами песен, улучшением звука и блокировкой рекламы.

---

## Возможности

<table>
  <tr>
    <th width="50%">Интерфейс и дизайн</th>
    <th width="50%">Тексты и полноэкранный режим</th>
  </tr>
  <tr>
    <td valign="top">
      <ul>
        <li><b>Материалы Windows 11</b>: Поддержка фонов окна <code>Mica</code>, <code>Mica Alt</code> и <code>Desktop Acrylic</code>.</li>
        <li><b>Темы оформления</b>: Системная, тёмная и светлая темы.</li>
        <li><b>Гибкая навигация</b>: Переключение между боковой панелью слева и компактным верхним меню.</li>
        <li><b>Встроенный мини-плеер</b>: Компактное управление воспроизведением прямо в панели навигации.</li>
        <li><b>Поиск и история</b>: Поисковые подсказки и локальная история запросов.</li>
      </ul>
    </td>
    <td valign="top">
      <ul>
        <li><b>Синхронизированные тексты</b>: Построчные таймированные и обычные тексты песен из базы LRCLIB.</li>
        <li><b>Автопрокрутка и переход</b>: Следование за играющей строкой и перемотка трека по клику на текст.</li>
        <li><b>Перевод текстов</b>: Перевод строк песни на выбранный язык в реальном времени с фильтром исключения языков.</li>
        <li><b>Полноэкранный плеер</b>: Отдельный экран плеера с анимированным размытым фоном обложки альбома.</li>
      </ul>
    </td>
  </tr>
  <tr>
    <th width="50%">Воспроизведение и звук</th>
    <th width="50%">Сеть и доступность</th>
  </tr>
  <tr>
    <td valign="top">
      <ul>
        <li><b>AdBlock</b>: Блокировка видеорекламы и баннеров в плеере.</li>
        <li><b>SponsorBlock</b>: Автоматический пропуск спонсорских вставок, интро и завершений.</li>
        <li><b>Кроссфейд (Crossfade)</b>: Плавные переходы громкости между треками.</li>
        <li><b>Качество воспроизведения</b>: Принудительный выбор максимального битрейта аудио и настройка разрешения видео.</li>
      </ul>
    </td>
    <td valign="top">
      <ul>
        <li><b>Обход ограничений</b>: Встроенный локальный Sing-box SOCKS5 прокси для доступа к YouTube Music в регионах с блокировками.</li>
        <li><b>Переключение в один клик</b>: Включение и отключение прокси прямо в настройках приложения без влияния на общесистемный трафик.</li>
      </ul>
    </td>
  </tr>
</table>

---

## Системные требования

| Компонент | Требование |
| :--- | :--- |
| **Операционная система** | Windows 10 (версия 1809 / сборка 17763 или новее) или Windows 11 |
| **Среда выполнения** | Microsoft Edge WebView2 Evergreen Runtime |

---

## Лицензия

Проект распространяется под условиями лицензии [MIT License](LICENSE).
