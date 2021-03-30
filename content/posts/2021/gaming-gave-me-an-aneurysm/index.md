---
title: "Один из этих постов про нейросети"
subtitle: "Ну, в смысле, с картиночками"
date: 2021-03-30T15:00:00+03:00
draft: false
comments: true
author: Юрий Крупенин
type: post
url: "/2021/gaming-gave-me-an-aneurysm"
categories:
  - Шитпостинг
  - Технологии
tags:
  - Шитпостинг
  - Пргрмрвнне
  - Технологии
---


\

Посты такого рода обычно начинаются с пассажа о том, как автор не имеет никакого представления о принципах работы нейросетей, а значит, дни человечества сочтены и мы добровольно подкладываем голову (метафорическую, общечеловеческую) под стремительно приближающуюся синтетическую пяту.

Но я человек простой, я вижу [новую модель](https://github.com/lucidrains/big-sleep), генерирующую картиночки по текстовому описанию[^mark1] -- я загоняю в неё названия видеоигр с метакритика, как иначе?

**BigSleep** на верхнем уровне, однако, достаточно простая вещь: она состоит на самом деле из двух моделей -- **CLIP**, оценивающей, что происходит на изображении, и **BigGAN**, изображения генерирующей. Вся большая идея заключается в том, чтобы многократно (каждая картинка проходит сотни и тысячи итераций) и последовательно модифицировать вывод BigGAN так, чтобы CLIP была всё более и более уверенна в том, что на картинке происходят именно вещи, которых просил пользователь.

\

{{<img src="images/howitworks">}}
<center>_Украденная [из чужого поста](https://wandb.ai/gudgud96/big-sleep-test/reports/Image-Generation-Based-on-Abstract-Concepts-using-CLIP-BigGAN--Vmlldzo1MjA2MTE) картинка, объясняющая общие принципы_</center>

\
\

Вы можете видеть на картинке с визуализацией промежуточных итераций, как по запросу "Bioshock" узнаваемый стиль постепенно прорастает из изображения собачки с интересным выражением мордочки.

{{<img src="images/bioshock-iterations">}}
<center>_Отвечает ли мордочка собаки на "shock" из запроса? Я намерен мучаться этим вопросом до конца своих дней._</center>

\
\


Всё, дальше в этом посте только сгенерированные BigSleep изображения, подпись к кажодму -- как несложно догадаться, запрос, по которому оно было сгенерированно. Иногда с моим страшно остроумным комментарием после дефиса, всем спасибо за внимание.


\
\


{{<img src="images/baldurs_gate_shadows_of_amn">}}
<center>_**Baldur's Gate II: Shadows of Amn** -- я в принципе вполне способен разглядеть здесь скриншот из игры_</center>


\
\


{{<img src="images/batman_arkham_city">}}
<center>_**Batman: Arkham City**_</center>


\
\


{{<img src="images/bioshock">}}
<center>_**Bioshock** -- нет ни единого шанса разобраться, что здесь изображено, но это каким-то образом несомненно **именно тот** шейдинг_</center>

\
\


{{<img src="images/bioshock_infinite">}}
<center>_**Bioshock: Infinite**_</center>


\
\


{{<img src="images/bloodborne">}}
<center>_**Bloodborne**_</center>


\
\


{{<img src="images/braid">}}
<center>_**Braid** -- что ж, да, это косичка_</center>


\
\


{{<img src="images/burnout_takedown">}}
<center>_**Burnout 3: Takedown** -- главное, допустим, сеть ухватила!_</center>


\
\


{{<img src="images/call_of_duty_modern_warfare">}}
<center>_**Call of Duty: Modern Warfare**_</center>


\
\


{{<img src="images/castlevania_symphony_of_the_night">}}
<center>_**Castlevania: Symphony of the Night**_</center>


\
\


{{<img src="images/celeste">}}
<center>_**Celeste** -- мммм, у меня здесь впечатление, будто нас серьёзным образом не так поняли, явно какая-то другая Celeste._</center>


\
\


{{<img src="images/chrono_cross">}}
<center>_**Chrono Cross** -- здесь впервые не уверен, что хоть что-то вижу_</center>


\
\


{{<img src="images/company_of_heroes">}}
<center>_**Company of Heroes**_</center>


\
\


{{<img src="images/devil_may_cry">}}
<center>_**Devil May Cry** -- а вот это то ли просто скриншот из четвёртой части, то ли кадр из не вышедшего пока ещё лайвэкшна. Фантастика._</center>


\
\


{{<img src="images/diablo">}}
<center>_**Diablo** -- да, это серьёзно злой щеночек, стоящий на паркетном полу_</center>


\
\


{{<img src="images/disco_elysium">}}
<center>_**Disco Elysium**_</center>

\
\


{{<img src="images/gears_of_war">}}
<center>_**Gears of War**_</center>


\
\


{{<img src="images/goldeneye_007">}}
<center>_**GoldenEye 007** -- Окей, явно слишком буквально._</center>

\
\

{{<img src="images/gran_turismo">}}
<center>_**Gran Turismo**_</center>


\
\


{{<img src="images/grand_theft_auto">}}
<center>_**Grand Theft Auto**_</center>


\
\


{{<img src="images/grand_theft_auto_vice_city">}}
<center>_**Grand Theft Auto: Vice City** -- ehhh, по крайней мере она всё правильно поняла про цветовое решение_</center>


\
\


{{<img src="images/grim_fandango">}}
<center>_**Grim Fandango**_</center>


\
\


{{<img src="images/hades">}}
<center>_**Hades** -- ух ты, даже подписала_</center>


\
\


{{<img src="images/halflife">}}
<center>_**Half-Life** -- она нарисовала лямбду?.._</center>


\
\


{{<img src="images/halo_combat_evolved">}}
<center>_**Halo: Combat Evolved** -- нравится думать, что та гифка с мастерчифом-котиком сбила с толку (я понятия не имею, если честно, что там у CLIP за датасет)_</center>


\
\


{{<img src="images/homeworld">}}
<center>_**Homeworld**_</center>


\
\


{{<img src="images/jet_set_radio">}}
<center>_**Jet Set Radio** -- ааааааааааааа_</center>


\
\


{{<img src="images/journey">}}
<center>_**Journey**_</center>


\
\


{{<img src="images/littlebigplanet">}}
<center>_**LittleBigPlanet**_</center>


\
\


{{<img src="images/mass_effect">}}
<center>_**Mass Effect** -- не могу вспомнить, какая это из концовок_</center>


\
\


{{<img src="images/metal_gear_solid_sons_of_liberty">}}
<center>_**Metal Gear Solid: Sons of Liberty**_</center>


\
\


{{<img src="images/metroid_prime">}}
<center>_**Metroid Prime**_</center>


\
\


{{<img src="images/minecraft">}}
<center>_**Minecraft**_</center>


\
\


{{<img src="images/ninja_gaiden_black">}}
<center>_**Ninja Gaiden Black** -- отовсюду понатаскала, уважаю!_</center>


\
\


{{<img src="images/okami">}}
<center>_**Okami** -- больше всего каждый раз восхищаюсь попытками ухватить стиль, хотя это кажется и вещь, которую GAN-сети умеют лучше всего_</center>


\
\


{{<img src="images/ori_and_the_will_of_the_wisps">}}
<center>_**Ori and the Will of the Wisps**_</center>


\
\


{{<img src="images/perfect_dark">}}
<center>_**Perfect Dark**_</center>


\
\


{{<img src="images/portal">}}
<center>_**Portal**_</center>


\
\


{{<img src="images/quake">}}
<center>_**Quake** -- ммм, ооооокей, нас точно чуть не так поняли._</center>


\
\


{{<img src="images/red_dead_redemption">}}
<center>_**Red Dead Redemption**_</center>


\
\


{{<img src="images/resident_evil">}}
<center>_**Resident Evil**_</center>


\
\


{{<img src="images/sid_meiers_civilization">}}
<center>_**Sid Meier's Civilization** -- вы меня извините, конечно, но я здесь абсолютно точно вижу Ричарда Столлмана, прогуливающегося по глобальной карте._</center>


\
\


{{<img src="images/soulcalibur">}}
<center>_**SoulCalibur**_</center>


\
\


{{<img src="images/splinter_cell_chaos_theory">}}
<center>_**Splinter Cell: Chaos Theory** -- (смахивая слезу) да, да, именно так он и выглядел_</center>


\
\


{{<img src="images/star_wars_knights_of_the_old_republic">}}
<center>_**Star Wars: Knights of the Old Republic**_</center>


\
\


{{<img src="images/super_mario_galaxy">}}
<center>_**Super Mario Galaxy** -- интересно: это достаточно близко... композиционно, что ли... к некоторым скриншотам игры._</center>


\
\


{{<img src="images/system_shock">}}
<center>_**System Shock**_</center>


\
\


{{<img src="images/the_elder_scrolls_skyrim">}}
<center>_**The Elder Scrolls V: Skyrim**_</center>


\
\


{{<img src="images/the_last_of_us">}}
<center>_**The Last of Us** -- наконец-то видеоигры безошибочно искусство_</center>


\
\


{{<img src="images/the_legend_of_zelda_ocarina_of_time">}}
<center>_**The Legend of Zelda: Ocarina of Time** -- что ж, по цветам попадание, допустим, почти стопроцентное_</center>


\
\


{{<img src="images/the_orange_box">}}
<center>_**The Orange Box** -- да ещё и не одна_</center>


\
\


{{<img src="images/the_witcher_wild_hunt">}}
<center>_**The Witcher 3: Wild Hunt** -- а что, и вполне даже похож._</center>


\
\


{{<img src="images/tony_hawks_pro_skater">}}
<center>_**Tony Hawk's Pro Skater** -- хотели буквально, но в датасете не было нужной птички, наверное_</center>


\
\


{{<img src="images/uncharted_among_thieves">}}
<center>_**Uncharted: Among Thieves** -- да, я знаю, что она "2", но цифры иногда сбивают модель с толку **абсолютно**_</center>


\
\


{{<img src="images/undertale">}}
<center>_**Undertale**_</center>


\
\


{{<img src="images/unreal_tournament">}}
<center>_**Unreal Tournament** -- определённо, присутствуют вайбы некоторых карт (почему-то больше из Unreal, мне кажется)_</center>


\
\


{{<img src="images/vagrant_story">}}
<center>_**Vagrant Story**_</center>


\
\


{{<img src="images/what_remains_of_edith_finch">}}
<center>_**What Remains of Edith Finch**_</center>


\
\


{{<img src="images/world_of_goo">}}
<center>_**World of Goo** -- велп, и ведь даже не получится сказать, что ничего такого не просил_</center>




[^mark1]: Захотите поиграться -- там есть линк на простейший в использовании Google Colab-набросок. Если же будет желание развернуть у себя -- имейте в виду, понадобится CUDA (на всякий случай: с её установкой могут быть *проблемы*; если вы не знаете точно, на что идёте -- предприятие рискует затянуться) и более-менее современный Nvidia-GPU с 8 или более ГБайт VRAM. 