<p align="center">
  <b>ПУБЛИЧНЫЙ ПРОЕКТ</b><br>
  <a href="https://github.com/svllvsxprod/max-station">Основной репозиторий ↗</a> ·
  <a href="https://github.com/svllvsx">Портфолио</a>
</p>

---

<p align="center">
  <img src="https://raw.githubusercontent.com/svllvsxprod/max-station/main/voice-input/res/drawable-nodpi/assistant_icon.png" alt="Max Station" width="112">
</p>

<h1 align="center">Max Station</h1>

<p align="center">Станция Макс без обязательной подписки Яндекса — с ChatGPT Voice, Spotify, YouTube и Twitch.</p>

<p align="center">
  <a href="https://github.com/svllvsxprod/max-station"><b>Как повторить</b></a>
  &nbsp;·&nbsp;
  <a href="https://github.com/svllvsxprod/max-station/releases/latest"><b>Скачать APK</b></a>
</p>

Цель проекта — убрать зависимость Станции Макс от сервисов Яндекса и превратить её в Bluetooth-колонку и Android TV-приставку с приложениями на свой выбор. Удалены 22 штатных пакета для основного пользователя Android, включая Алису, Яндекс Музыку, обновлятор и мастер настройки. Оставленные компоненты для работы железа ограничены локальными соединениями. Сетевой запрет проверен после загрузки Android.

Голосовым помощником стал **ChatGPT Voice** через приложение и OpenAI API. Он отвечает на вопросы, ставит будильники, открывает приложения и управляет музыкой и громкостью. Вместо Яндекс Музыки используется **Spotify**, для видео — **YouTube через TizenTube Cobalt**, для трансляций — **Twitch**, для фильмов и сериалов — **Lampa**. Просмотр торрентов предусмотрен через TorrServer. В этой конфигурации он работает на отдельном сервере. Исходники помощника доступны для подключения другого голосового сервиса.

<table align="center">
  <tr>
    <td align="center" width="50%"><img src="https://raw.githubusercontent.com/svllvsxprod/max-station/main/docs/images/assistant.png" alt="Голосовой ассистент" width="100%"></td>
    <td align="center" width="50%"><img src="https://raw.githubusercontent.com/svllvsxprod/max-station/main/docs/images/time-minutes.png" alt="Настройка будильника с пульта" width="100%"></td>
  </tr>
  <tr>
    <td align="center"><sub>Голосовой ассистент</sub></td>
    <td align="center"><sub>Выбор времени будильника</sub></td>
  </tr>
  <tr>
    <td align="center" colspan="2"><img src="https://raw.githubusercontent.com/svllvsxprod/max-station/main/docs/images/assistant-overlay-spotify.png" alt="Плавающая панель ChatGPT поверх Spotify: голосовое управление громкостью" width="100%"><br><sub>Плавающий ассистент поверх Spotify</sub></td>
  </tr>
</table>

Удержание кнопки ассистента на пульте вызывает компактную панель поверх текущего приложения. На снимке — управление громкостью из Spotify, без перехода на главный экран ассистента.

Переделка проверена на Станции Макс **YNDX-0008 без Zigbee**. Подтверждён запуск «Любимых треков» Spotify по команде при выключенном телевизоре. Руководство с распиновкой USB, список удалённых пакетов, исходники и релизы лежат в основном репозитории.
