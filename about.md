---
layout: page
title: O stronie
permalink: /about/
---

<ul>
{% for item in site.data.dane %}
  <li>
    <strong>{{ item['klucz'] }}</strong>:
    {% for anotherItem in item['klucz2'] %}
      {{ anotherItem}}
    {% endfor %}
  </li>
  {% endfor %}
</ul>

## Nagroda Akademii Filmowej

### Katalog laureatów

![Odnosnik](https://s-media-cache-ak0.pinimg.com/favicons/be9afebb549c0ec878450efb186428573f13171d0072b99ed59d337c.ico?81e86945d3dc421cb83147bcb4f1c59e)

Strona zawiera wszystkich laureatów **Nagrody Akademii Filmowej** od roku *1929* we wszystkich kategoriach:

- Najlepszy Film
- Najlepszy Reżyser
- Najlepszy Scenariusz Oryginalny
- Najlepszy Scenariusz Adaptowany
- Najlepszy Aktor
- Najlepsza Aktorka
- Najlepszy Aktor Drugoplanowy
- Najlepsza Aktorka Drugoplanowa
- Najlepsza Scenografia i Dekoracja Wnętrz
- Najlepsze Zdjęcia
- Najlepszy Montaż
- Najlepsze Efekty specjalne
- Najlepszy Dźwięk
- Najlepszy Montaż Dźwięku
- Nalepsza Muzyka
- Najlepsza Piosenka
- Najlepsze Kostiumy
- Najlepsza Charakteryzacja
- Najlepszy Pełnometrażowy Film Animowany
- Najlepszy Krótkometrażowy Film Animowany
- Najlepszy Pełnometrażowy Film Dokumentalny
- Najlepszy Krótkometrażowy Film Dokumentalny
- Najlepszy Film Nieanglojęzyczny
- Najlepszy Krótkometrażowy Film Aktorski
- Najlepsza choreografia
- Oscary Honorowe i Specjalne
