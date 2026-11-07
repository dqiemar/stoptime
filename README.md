<h1 align="center">⏱ Останови время</h1>

<p align="center">
  <img src="https://img.shields.io/badge/version-2.0.0-8ab4f8?style=for-the-badge" alt="version">
  <img src="https://img.shields.io/badge/status-active-34a853?style=for-the-badge" alt="status">
  <img src="https://img.shields.io/badge/license-MIT-fdd663?style=for-the-badge" alt="license">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
  <img src="https://img.shields.io/badge/No_Dependencies-000000?style=for-the-badge&logo=checkmarx&logoColor=white" alt="No dependencies">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/platform-web%20%7C%20mobile%20%7C%20desktop-blue?style=flat-square" alt="platform">
  <img src="https://img.shields.io/badge/storage-localStorage-9aa0a6?style=flat-square" alt="storage">
  <img src="https://img.shields.io/badge/font-SF%20Pro%20Display%20Medium-000000?style=flat-square&logo=apple&logoColor=white" alt="font">
</p>

<p align="center">
  <b>Минималистичная игра-таймер: запусти отсчёт и останови его как можно быстрее.</b><br>
  Чем меньше время — тем лучше результат. Всё работает локально, в браузере, без сервера.
</p>

---

## 📖 О проекте

**«Останови время»** — это одностраничное веб-приложение (single-file), которое проверяет вашу реакцию и чувство времени. Нажмите «СТАРТ», подождите несколько мгновений и нажмите «СТОП» — приложение зафиксирует прошедшее время с точностью до микросекунд. Цель — остановить таймер как можно раньше.

Приложение не требует установки, сборки и интернета. Достаточно открыть `index.html` в браузере.

<p align="center">
  <img src="https://img.shields.io/badge/🎮_Игра-таймер_на_реакцию-1b2e4b?style=for-the-badge" alt="game">
  <img src="https://img.shields.io/badge/🏆_Рекорды-сохраняются_локально-1b2e4b?style=for-the-badge" alt="records">
  <img src="https://img.shields.io/badge/⌨️_Хоткей-настраивается-1b2e4b?style=for-the-badge" alt="hotkey">
</p>

---

## ✨ Возможности

<table>
<tr>
<td width="50%" valign="top">

### 🎯 Игровой процесс
- ⏱ Таймер с точностью до микросекунд
- 🖱 Работает мышью, тапом и клавиатурой
- ⚡ Мгновенный отклик через `requestAnimationFrame`
- 📱 Адаптивен под мобильные устройства
- 🔒 Защита от двойного срабатывания

</td>
<td width="50%" valign="top">

### 🎨 Интерфейс
- 🌙 Тёмная тема по умолчанию
- 🔤 Шрифт **SF Pro Display Medium**
- ♿ Поддержка `prefers-reduced-motion`
- 👆 Крупные тач-цели (min 44px)
- 📐 Safe-area для iPhone с «вырезом»

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 💾 Данные
- 🗂 Сохранение истории попыток в `localStorage`
- 🏅 Отображение личного рекорда
- 🧹 Очистка истории в один клик
- 🔄 Синхронизация между вкладками
- 🛡 Валидация всех сохранённых данных

</td>
<td width="50%" valign="top">

### ⚙️ Настройки
- ⌨️ Назначение горячей клавиши для ПК
- 🚫 Защита от авто-повтора клавиши
- 🎛 Захват любой клавиши (кроме Esc)
- 🗑 Полный сброс прогресса
- 🧩 Работает без интернета

```bash
git clone https://github.com/your-username/stop-the-time.git
cd stop-the-time
