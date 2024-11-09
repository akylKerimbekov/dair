---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

![Описание изображения](assets/images/Dair.jpg)

<div class="container">
  <h1 id="headline">Countdown to start my treatment</h1>
  <div id="countdown">
    <ul>
      <li><span id="days"></span>days</li>
      <li><span id="hours"></span>Hours</li>
      <li><span id="minutes"></span>Minutes</li>
      <li><span id="seconds"></span>Seconds</li>
    </ul>
  </div>
  <div id="content" class="emoji">
    <span>🥳</span>
    <span>🎉</span>
    <span>🎂</span>
  </div>
</div>


<!-- Подключение стилей и скриптов -->
<link rel="stylesheet" href="{{ '/assets/css/countdown.css' | relative_url }}">
<script src="{{ '/assets/js/countdown.js' | relative_url }}" defer></script>
