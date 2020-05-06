---
title: "Усиление+ Подкаст: Выпуск 5"
subtitle: "Что нового в новых консолях"
date: 2020-05-07T00:00:01+03:00
draft: false
comments: true
author: Юрий Крупенин
type: news
url: "/podcast/5"
categories:
  - Подкаст
  - Технологии
  - Видеоигры
tags:
  - Подкаст
---

Playstation 5 и Xbox Series X: непринципиально более мощные числодробилки или самая большая переработка архитектуры за десятилетия?

Не знаем, но наш подкаст рассматривает только оптимистичный вариант.

Десять раз обещал себе, что не буду больше делать таких обзорных материалов, но мог ли я *не* почесать языком о некстджен-мякотке? Извините за качество записи -- я мучал текст месяц, чтобы зачитать его второпях за один день, к тому же под неожиданные весенние звуки из-за окна; со второй частью проблемы попробую к следующему разу что-нибудь сделать!

\

<iframe width="100%" height="166" scrolling="no" frameborder="no" allow="autoplay" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/815045710&color=%23ff5500&auto_play=false&hide_related=false&show_comments=true&show_user=true&show_reposts=false&show_teaser=true"></iframe>

\

Альтернативные линки (новые эпизоды могут появляться с некоторым запозданием):

* [Google Podcasts](https://podcasts.google.com/?feed=aHR0cDovL2ZlZWRzLnNvdW5kY2xvdWQuY29tL3VzZXJzL3NvdW5kY2xvdWQ6dXNlcnM6MjM0MzMyOTQvc291bmRzLnJzcw) \
* [Apple Podcasts](https://podcasts.apple.com/ru/podcast/%D1%83%D1%81%D0%B8%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5-%D0%BF%D0%BE%D0%B4%D0%BA%D0%B0%D1%81%D1%82/id1487512789) \
* [Spotify](https://open.spotify.com/show/4dQbxnwJjsz4z9UdCVJR6H) \
* [Castbox](https://castbox.fm/channel/%D0%A3%D1%81%D0%B8%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5%2B-%D0%9F%D0%BE%D0%B4%D0%BA%D0%B0%D1%81%D1%82-id2462850) \
* [Overcast](https://overcast.fm/itunes1487512789) \
* [Яндекс.Музыка](https://music.yandex.ru/album/9244822) \
* [RSS](https://anchor.fm/s/1079e220/podcast/rss) \

\

* [<b>Чуть обособленно: патреон</b>](https://patreon.com/yurikrupenin)

\

**Примечание 1:** в определенные моменты вы можете заметить, что я слегка некорректно описываю TTS, light volumes и clustered deferred shading, не затрагиваю вопрос о имплементации BVH и RT/Tri-ускорителях в RDNA2, перехожу от рейтрейсинга к пафтрейсингу без объяснения различий, и вообще в угоду повествованию говорю куда больше о новых возможностях, чем о проблемах: это не то чтоб совсем умышленно, но сознательно -- я и так опять раздул выпуск, и мне не хватило бы и десяти часов, если бы я везде сохранял полную техническую точность; да, я много где здесь говорю о вещах, которые сам полностью не понимаю (меш-шейдинг сложно, я пока не полностью разобрался), но это не те случаи.

**Примечание 2:** а вот ускоряющую струткутуру называю "ускоряющей текстурой" случайно оговорившись, и вырезать и перемонтировать этот кусок так, чтоб не звучало еще болезненнее, у меня не вышло.

**Примечание 3:** Леонард Нимой был не в Civilization V, а в Civilization IV. Вот тут мне действительно стыдно.



Референсы:

* [Спецификации DXR](https://github.com/microsoft/DirectX-Specs/blob/master/d3d/Raytracing.md)
* [Презентация Марка Церни](https://www.youtube.com/watch?v=ph8LyNIT9sg)
* [Текстура стрелы в Daikatana](https://tcrf.net/File:Predaiarrow.png)
* [Несколько моментов из жизни стены в видеоигре](https://twitter.com/turbojedi/status/1022163802501074944)
* [Обзор архитектуры Turing (whitepaper на RDNA2 на момент компоновки материала ещё не был доступен)](https://www.nvidia.com/content/dam/en-zz/Solutions/design-visualization/technologies/turing-architecture/NVIDIA-Turing-Architecture-Whitepaper.pdf)
* [Sparse lighting при помощи VRS (презентация Microsoft)](https://www.youtube.com/watch?v=2vKnKba0wxk)
* [Как архитектура консолей влияет на дизайн (материал 2009 года)](https://www.gamasutra.com/blogs/PhilRA/20090606/84228/Why_quotNextGen_Gamesquot_Went_Gray_Brown_And_Grey.php)
* [Mesh-шейдеры по версии Microsoft](https://devblogs.microsoft.com/directx/coming-to-directx-12-mesh-shaders-and-amplification-shaders-reinventing-the-geometry-pipeline/)
* [Mesh-шейдеры по версии Nvidia](https://devblogs.nvidia.com/introduction-turing-mesh-shaders/)
