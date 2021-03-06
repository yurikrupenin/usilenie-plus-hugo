---
title: "Фэнтези-консоли, демосцена, и Playdate"
subtitle: 
date: 2019-06-07T06:30:00+03:00
draft: false
comments: true
author: Юрий Крупенин
type: post
url: "/2019/fantasy-consoles/"
featured: images/featured
#bigimg: [{src: "images/header.jpg"}]
categories:
  - Видеоигры
  - Шитпостинг
tags:
  - Консоли
  - Демосцена
  - Playdate
---

Зачем люди пишут видеоигры? Необъятный, не имеющий единственного ответа вопрос, но одним из вознаграждений для изобретательного ума всегда было познание границ возможностей системы и, может быть, возможностей собственных. 

К счастью или нет, но девяностые были, вероятно, последним десятилетием, когда нам действительно жадно недоставало процессорных и других соков; машинная благодать, конечно, не безгранична и сейчас, но одинокий творец совсем уже не на равных борется с платформой: последняя слишком обширна, окружает со всех сторон, можно усердно давить в какую-то конкретную точку, с машинным же упорством выстроить видеоигровую версию скрепочного максимизатора, оставив эстетику за скобками, но зачем? Выжимание современных систем -- уничижительно командная, параллельная, профессиональная работа. Что остаётся левшам? Пытать нарочно созданные примитивными окружения.

В какой-то степени эту жажду утоляла демосцена с её ограничениями на платформу или размер выполняемого файла. [Все][badapple1] [версии][badapple2] [Bad][badapple3] [Apple][badapple4], [классические][fr1] [и][fr2] [новые][fr3] [работы][fr4] [Farbrausch][fr5], с некоторыми оговорками -- пугающие своей комплексностью [сцены][asd1] [Andromeda][asd2] [Software][asd3] [Development][asd4]: эта группа работает вне ограничений платформ или форматов, но чуть притормаживает себя сама, максимально используя процедурную генерацию и алгоритмические решения, а не давя количеством ассетов[^demoscene].

\

{{<video src="images/iconoclast.mp4">}}
<center>
_Сложно передать словами, какие чувства вызывала эта сцена в 2005 году. Религиозные. Чудо. Никто не подбирается к уровню продакшна ASD. Никто._
</center>

Но нельзя копаться в амиге или шестидесяти четырёх килобайтах Windows-бинарника бесконечно, поэтому (но далеко не _только_ поэтому, конечно) были рождены фэнтези-консоли.

## Фэнтези-консоли

Что такое фэнтези-консоль? Само название передаёт общую концепцию (на всякий случай: оно ближе к явлению fantasy sports, чем к жанру писанины), но углубимся в детали: это обычно исключительно программная (работающая на вполне бытовых компьютерах) платформа, имеющая жёсткие искусственные ограничения по производительности, доступным средствам разработки, объёму памяти, цветовой палитре и разрешению экрана... по чему угодно, словом.

[Претендующие на некоторую полноту списки][console-list1] и образовавшиеся вокруг консолей [сообщества][hireddit] легко ищутся по ключевым словам, бегло пройдёмся по наиболее заметным представителям.

### PICO-8
Безусловно, самая известная из всех, породившая в значительной степени и весь современный бум _pretend-систем_. Суровые технические ограничения: 128x128, 16 цветов (палитры!), 32 килобайта на картридж, Lua в качестве языка разработки, но при желании -- доступно и абсолютно прямое управление "физической" памятью.

\

{{<img src="images/pico8">}}

<center>
_Анимация с [официального сайта][pico8]._
</center>

Строго? Может быть. Диктует определённую эстетику? Безусловно да, но тем интереснее [работы, пытающиеся выйти за границы и здесь][bluemarble]. Ах, да, играть в опубликованные игры из [каталога картриджей][picogames] можно прямо в браузере.

### Pixel Vision 8

[Молодая, но достаточно сумасшедшая платформа][pixelvision]. Среду разработки хочется просто съесть, до того она искрится никогда не существовавшим, лучшим прошлым. Вы вольны не только работать в рамках заданной конфигурации, но и выстроить (ну, набросать в игровой, конструкторной форме) спецификации системы самостоятельно.

\

{{<video src="images/pixelvision.mp4" >}}

\

К сожалению, не слишком много находящихся на виду игр, и никакой браузерной среды выполнения, зато есть [небезынтересный твиттер][pixelvision-twitter].

### EXAPUNKS TEC Redshift

#### Вы всё ещё со мной? Потому что это ключевая для моего рассказа платформа. 

Я не знаю, с чего начать. Существует основанная Заком Бартом компания [Zachtronics][zachtronics-site] (может быть в первую очередь знакома вам по **SpaceChem**), выпускающая игры, увлечение которыми всё больше и больше становится похожим на профессиональное программирование встраиваемых систем. Последняя, [EXAPUNKS][exapunks-steam], рассказывает историю хакера из альтернативного 1997 года, программирующего сеть примитивных наномашин.

EXAPUNKS не ставит перед вами вопросов, она выдвигает тезис: допустим, развитие всех информационных технологий пошло совсем иначе, и основной парадигмой для компьютерных систем стали высокопараллельные сети из крайне примитивных микроскопических блоков (всего по паре регистров, и очень небольшие объемы кода), легко снующих между узлами окружающего насквозь компьютеризированного мира.

Вместо синтетических паззлов -- обычные хакерские развлечения: сломать DRM в игровой консоли, перевести себе по паре центов с каждого банковского счёта, выкрасть из внутренней сети Новосибирского Государственного Технического Университета один ничем не примечательный файл, разложить пасьянс... Впрочем, я отвлёкся. Вместо мануалов и туториалов -- андерграундная хакерская листовка: представьте себе написанный с несколько большим уважением к умственным способностям читателя журнал **][akep** -- и не сильно ошибётесь.

\

{{<video src="images/exapunks.mp4">}}

\

В один момент в руки вашего персонажа попадает портативная консоль TEC Redshift, и игра не предлагает вам никакой определённой цели. Вы вольны просто возиться с этой новой системой, и никто не будет лезть к вам со своими оценками.

И это абсолютно инопланетная система. Арканоид выглядит, например, вот так:

{{<youtube nmdEHSe7Uxw>}}

\
\

## Наконец, Playdate

И именно этим меня и восхищает Redshift, и вот теперь -- [Playdate][playdate-site].

Это ретро-системы, которые никогда не существовали. Они не просто накладывают на вас какие-то ограничения, они предлагают новую парадигму.

Виртуальная портативная консоль, работающая на наномашинах вместо центрального процессора? Восхитительно.

**Настоящая** портативная консоль, с вроде бы мощным процессором[^mark1], но -- чёрнобелым экраном, и _ручкой, которую можно крутить_? **С ума сойти**.

\

{{<img src="images/playdate" caption="Господи, до чего ж хороша.">}}

Можно со скептицизмом относиться к готовящей запуск консоли **Panic**[^mark2], но если у неё получится -- из всей затеи может выйти что-то волшебное. Panic [уже объявила о двенадцати готовящихся к выходу играх от не последних в индустрии людей][playdate-announce], надеется --- всё зависит от продаж --- на то, что праздник на этом не закончится, но (пока что?..) не слишком хочет разговаривать о доступности официального SDK для всех желающих.

В любом случае, если внимание публики к эпатажной ретроконсоли не привлекут Кэйта Такахаси и Беннетт Фодди, то я не знаю, что вообще привлечёт (из реалистичных, конечно, возможностей --- мы не говорим о игре From Software на этой платформе).

Ручка, монохромный экран, всего две кнопки --- всё это само по себе, как технические решения или ограничения, не заслуживает и единого мимоходного комментария. Вы делаете эти вещи интересными, заставляя кучу умных людей придумывать, что интересного могут с ними сделать они.

И мне в каком-то смысле куда больше хочется увидеть, что работающие в одиночку или с небольшими командами признанные геймндизайнеры могут сделать с портативной чёрнобелой консолью с ручкой, чем снова убедиться, что многотысячные студии в общем-то прекрасно представляют, как обращаться с до омерзения стандартизированными многотерафлопсными ящиками.


[badapple1]: https://www.youtube.com/watch?v=MWdG413nNkI&feature=youtu.be&t=2m52s
[badapple2]: https://www.youtube.com/watch?v=u_pdp1QSp70
[badapple3]: https://www.youtube.com/watch?v=fu7rRYkWsyk
[badapple4]: https://www.youtube.com/watch?v=VJ4IPwLOutk

[fr1]: https://www.youtube.com/watch?v=Y3n3c_8Nn2Y
[fr2]: https://www.youtube.com/watch?v=jY5Vrc5G0lk
[fr3]: https://www.youtube.com/watch?v=5EPj_VCBDwQ
[fr4]: https://www.youtube.com/watch?v=6AUpZNq2vSQ
[fr5]: https://www.youtube.com/watch?v=ubKE-Es3r2g

[asd1]: https://www.youtube.com/watch?v=BQbntu4WqOw
[asd2]: https://www.youtube.com/watch?v=u00ErHIvF9A
[asd3]: https://www.youtube.com/watch?v=VacQErWAuMU
[asd4]: https://www.youtube.com/watch?v=SqPHOPwhc-Q

[pouet]: http://www.pouet.net/prodlist.php?order=thumbup

[console-list1]: https://github.com/paladin-t/fantasy
[hireddit]: https://www.reddit.com/r/fantasyconsoles/

[pico8]: https://www.lexaloffle.com/pico-8.php
[bluemarble]: https://www.lexaloffle.com/bbs/?pid=42377#p
[picogames]: https://www.lexaloffle.com/bbs/?cat=7#sub=2&mode=carts&orderby=featured

[pixelvision]: https://pixelvision8.itch.io/
[pixelvision-twitter]: https://twitter.com/pixelvision8

[zachtronics-site]: http://www.zachtronics.com/
[exapunks-steam]: https://store.steampowered.com/app/716490/EXAPUNKS/

[playdate-site]: https://play.date/
[playdate-faq]: https://play.date/media/
[panic-bullying]: https://www.gamesindustry.biz/articles/2019-05-28-playdate-handheld-pressured-playdate-event-to-change-name-says-organizer
[panic-apologizes]: https://twitter.com/cabel/status/1133427827972251648
[playdate-announce]: https://usilenie.plus/2019/05/playdate-new-console/ 

[^demoscene]: Если демосцена -- новое для вас явление, то вас возможно заинтересует сайт [pouet.net][pouet], где собрано всё связанное с явлением (обратите внимание, что практически для каждой сцены есть линк на ютуб или видео на других хостингах, но часть экспириенса, конечно, в том, чтоб смотреть, как чудо работает именно на вашем компьютере).
[^mark1]: [Официальный FAQ][playdate-faq] оперирует формулировкой "real beefy".
[^mark2]: Я вынужден, несмотря на моё восторженнное отношение к консоли, напомнить о некрасивой истории: Panic пыталась [отжать название][panic-bullying] у видеоигрового фестиваля; представитель компании [извинился][panic-apologizes], и будто бы сделал это довольно искренне, но это не может не вызывать вопросов о том, до какой степени Panic всё же движима любовью к видеоиграм (как заявляет официальный сайт), а не чем-то другим.