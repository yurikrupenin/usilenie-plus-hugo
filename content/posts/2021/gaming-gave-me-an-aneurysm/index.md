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


<br />

Посты такого рода обычно начинаются с пассажа о том, как автор не имеет никакого представления о принципах работы нейросетей, а значит, дни человечества сочтены и мы добровольно подкладываем голову (метафорическую, общечеловеческую) под стремительно приближающуюся синтетическую пяту.

Но я человек простой, я вижу [новую модель](https://github.com/lucidrains/big-sleep), генерирующую картиночки по текстовому описанию[^mark1] -- я загоняю в неё названия видеоигр с метакритика, как иначе?

**BigSleep** на верхнем уровне, однако, достаточно простая вещь: она состоит на самом деле из двух моделей -- **CLIP**, оценивающей, что происходит на изображении, и **BigGAN**, изображения генерирующей. Вся большая идея заключается в том, чтобы многократно (каждая картинка проходит сотни и тысячи итераций) и последовательно модифицировать вывод BigGAN так, чтобы CLIP была всё более и более уверенна в том, что на картинке происходят именно вещи, которых просил пользователь.


<br />


{{<img src="images/howitworks">}}
<center><i>Украденная <a href="https://wandb.ai/gudgud96/big-sleep-test/reports/Image-Generation-Based-on-Abstract-Concepts-using-CLIP-BigGAN--Vmlldzo1MjA2MTE">(из чужого поста)</a> картинка, объясняющая общие принципы</i></center>


<br />


Вы можете видеть на картинке с визуализацией промежуточных итераций, как по запросу "Bioshock" узнаваемый стиль постепенно прорастает из изображения собачки с интересным выражением мордочки.

{{<img src="images/bioshock-iterations">}}
<center><i>Отвечает ли мордочка собаки на "shock" из запроса? Я намерен мучаться этим вопросом до конца своих дней.</i></center>


<br />


Всё, дальше в этом посте только сгенерированные BigSleep изображения, подпись к кажодму -- как несложно догадаться, запрос, по которому оно было сгенерированно. Иногда с моим страшно остроумным комментарием после дефиса, всем спасибо за внимание.

<br />


{{<img src="images/assassins_creed">}}
<center><i><b>Assassin's Creed</b></i> — классический (даже чуть странно писать это слово)! На вышке!</i></center>


<br />


{{<img src="images/baldurs_gate_shadows_of_amn">}}
<center><i><b>Baldur's Gate II: Shadows of Amn</b> — я в принципе вполне способен разглядеть здесь скриншот из игры</i></center>

<br />


{{<img src="images/batman_arkham_city">}}
<center><i><b>Batman: Arkham City</b></i></center>


<br />


{{<img src="images/bayonetta">}}
<center><i><b>Bayonetta</b> — да, это безошибочно Байонетта</i></center>


<br />


{{<img src="images/bioshock">}}
<center><i><b>Bioshock</b> — нет ни единого шанса разобраться, что здесь изображено, но это каким-то образом несомненно <b>именно тот</b> шейдинг</i></center>


<br />


{{<img src="images/bioshock_infinite">}}
<center><i><b>Bioshock: Infinite</b></i></center>


<br />


{{<img src="images/bloodborne">}}
<center><i><b>Bloodborne</b></i></center>


<br />


{{<img src="images/braid">}}
<center><i><b>Braid</b> — что ж, да, это косичка</i></center>


<br />


{{<img src="images/burnout_takedown">}}
<center><i><b>Burnout 3: Takedown</b> — главное, допустим, сеть ухватила!</i></center>


<br />


{{<img src="images/call_of_duty_modern_warfare">}}
<center><i><b>Call of Duty: Modern Warfare</b></i></center>


<br />


{{<img src="images/castlevania_symphony_of_the_night">}}
<center><i><b>Castlevania: Symphony of the Night</b></i></center>


<br />


{{<img src="images/celeste">}}
<center><i><b>Celeste</b> — мммм, у меня здесь впечатление, будто нас серьёзным образом не так поняли, явно какая-то другая Celeste.</i></center>


<br />


{{<img src="images/chrono_cross">}}
<center><i><b>Chrono Cross</b> — здесь впервые не уверен, что хоть что-то вижу</i></center>


<br />


{{<img src="images/company_of_heroes">}}
<center><i><b>Company of Heroes</b></i></center>


<br />


{{<img src="images/demons_souls">}}
<center><i><b>Demon's Souls</b></i></center>


<br />


{{<img src="images/devil_may_cry">}}
<center><i><b>Devil May Cry</b> — а вот это то ли просто скриншот из четвёртой части, то ли кадр из не вышедшего пока ещё лайвэкшна. Фантастика.</i></center>


<br />


{{<img src="images/diablo">}}
<center><i><b>Diablo</b> — да, это серьёзно злой щеночек, стоящий на паркетном полу</i></center>


<br />


{{<img src="images/disco_elysium">}}
<center><i><b>Disco Elysium</b></i></center>

<br />


{{<img src="images/gears_of_war">}}
<center><i><b>Gears of War</b></i></center>


<br />


{{<img src="images/goldeneye_007">}}
<center><i><b>GoldenEye 007</b> — Окей, явно слишком буквально.</i></center>

<br />

{{<img src="images/gran_turismo">}}
<center><i><b>Gran Turismo</b></i></center>


<br />


{{<img src="images/grand_theft_auto">}}
<center><i><b>Grand Theft Auto</b></i></center>


<br />


{{<img src="images/grand_theft_auto_vice_city">}}
<center><i><b>Grand Theft Auto: Vice City</b> — ehhh, по крайней мере она всё правильно поняла про цветовое решение</i></center>


<br />


{{<img src="images/grim_fandango">}}
<center><i><b>Grim Fandango</b></i></center>


<br />


{{<img src="images/hades">}}
<center><i><b>Hades</b> — ух ты, даже подписала</i></center>


<br />


{{<img src="images/halflife">}}
<center><i><b>Half-Life</b> — она нарисовала лямбду?..</i></center>


<br />


{{<img src="images/halo_combat_evolved">}}
<center><i><b>Halo: Combat Evolved</b> — нравится думать, что та гифка с мастерчифом-котиком сбила с толку (я понятия не имею, если честно, что там у CLIP за датасет)</i></center>


<br />


{{<img src="images/hollow_knight">}}
<center><i><b>Hollow Knight</b></i></center>

<br />


{{<img src="images/homeworld">}}
<center><i><b>Homeworld</b></i></center>


<br />


{{<img src="images/jet_set_radio">}}
<center><i><b>Jet Set Radio</b> — ааааааааааааа</i></center>


<br />


{{<img src="images/journey">}}
<center><i><b>Journey</b></i></center>


<br />


{{<img src="images/littlebigplanet">}}
<center><i><b>LittleBigPlanet</b></i></center>


<br />


{{<img src="images/loop_hero">}}
<center><i><b>Loop Hero</b> — редкий случай: игра ещё не вышла на момент обучения CLIP</i></center>

<br />


{{<img src="images/mass_effect">}}
<center><i><b>Mass Effect</b> — не могу вспомнить, какая это из концовок</i></center>


<br />


{{<img src="images/metal_gear_solid_sons_of_liberty">}}
<center><i><b>Metal Gear Solid: Sons of Liberty</b></i></center>


<br />


{{<img src="images/metroid_prime">}}
<center><i><b>Metroid Prime</b></i></center>


<br />


{{<img src="images/microsoft_flight_simulator">}}
<center><i><b>Microsoft Flight Simulator</b></i></center>

<br />


{{<img src="images/minecraft">}}
<center><i><b>Minecraft</b></i></center>


<br />


{{<img src="images/neverwinter_nights">}}
<center><i><b>Neverwinter Nights</b></i></center>


<br />


{{<img src="images/ninja_gaiden_black">}}
<center><i><b>Ninja Gaiden Black</b> — отовсюду понатаскала, уважаю!</i></center>


<br />


{{<img src="images/okami">}}
<center><i><b>Okami</b> — больше всего каждый раз восхищаюсь попытками ухватить стиль, хотя это кажется и вещь, которую GAN-сети умеют лучше всего</i></center>


<br />


{{<img src="images/ori_and_the_will_of_the_wisps">}}
<center><i><b>Ori and the Will of the Wisps</b></i></center>


<br />


{{<img src="images/perfect_dark">}}
<center><i><b>Perfect Dark</b></i></center>


<br />


{{<img src="images/portal">}}
<center><i><b>Portal</b></i></center>


<br />


{{<img src="images/quake">}}
<center><i><b>Quake</b> — ммм, ооооокей, нас точно чуть не так поняли.</i></center>


<br />


{{<img src="images/quake_iii_arena">}}
<center><i><b>Quake III: Arena</b> — да, так гораздо лучше</i></center>


<br />


{{<img src="images/red_dead_redemption">}}
<center><i><b>Red Dead Redemption</b></i></center>


<br />


{{<img src="images/resident_evil">}}
<center><i><b>Resident Evil</b></i></center>


<br />


{{<img src="images/rome_total_war">}}
<center><i><b>Rome: Total War</b> — это... это оверлей телеканала?..</i></center>


<br />


{{<img src="images/sekiro_shadows_die_twice">}}
<center><i><b>Sekiro: Shadows Die Twice</b></i></center>

<br />


{{<img src="images/sid_meiers_civilization">}}
<center><i><b>Sid Meier's Civilization</b> — вы меня извините, конечно, но я здесь абсолютно точно вижу Ричарда Столлмана, прогуливающегося по глобальной карте.</i></center>


<br />


{{<img src="images/soulcalibur">}}
<center><i><b>SoulCalibur</b></i></center>


<br />


{{<img src="images/splinter_cell_chaos_theory">}}
<center><i><b>Splinter Cell: Chaos Theory</b> — (смахивая слезу) да, да, именно так он и выглядел</i></center>


<br />


{{<img src="images/star_wars_knights_of_the_old_republic">}}
<center><i><b>Star Wars: Knights of the Old Republic</b></i></center>


<br />


{{<img src="images/super_mario_galaxy">}}
<center><i><b>Super Mario Galaxy</b> — интересно: это достаточно близко... композиционно, что ли... к некоторым скриншотам игры.</i></center>


<br />


{{<img src="images/system_shock">}}
<center><i><b>System Shock</b></i></center>


<br />


{{<img src="images/morrowind">}}
<center><i><b>The Elder Scrolls III: Morrowind</b></i></center>

<br />


{{<img src="images/the_elder_scrolls_skyrim">}}
<center><i><b>The Elder Scrolls V: Skyrim</b></i></center>


<br />


{{<img src="images/the_last_of_us">}}
<center><i><b>The Last of Us</b> — наконец-то видеоигры безошибочно искусство</i></center>


<br />


{{<img src="images/the_legend_of_zelda_ocarina_of_time">}}
<center><i><b>The Legend of Zelda: Ocarina of Time</b> — что ж, по цветам попадание, допустим, почти стопроцентное</i></center>


<br />


{{<img src="images/the_orange_box">}}
<center><i><b>The Orange Box</b> — да ещё и не одна</i></center>


<br />


{{<img src="images/the_witcher_wild_hunt">}}
<center><i><b>The Witcher 3: Wild Hunt</b> — а что, и вполне даже похож.</i></center>


<br />


{{<img src="images/tomb_raider">}}
<center><i><b>Tomb Raider</b></i></center>


<br />


{{<img src="images/tony_hawks_pro_skater">}}
<center><i><b>Tony Hawk's Pro Skater</b> — хотели буквально, но в датасете не было нужной птички, наверное</i></center>


<br />


{{<img src="images/twisted_metal_black">}}
<center><i><b>Twisted Metal: Black</b></i></center>

<br />


{{<img src="images/uncharted_among_thieves">}}
<center><i><b>Uncharted: Among Thieves</b> — да, я знаю, что она "2", но цифры иногда сбивают модель с толку <b>абсолютно</b></i></center>


<br />


{{<img src="images/undertale">}}
<center><i><b>Undertale</b></i></center>


<br />


{{<img src="images/unreal_tournament">}}
<center><i><b>Unreal Tournament</b> — определённо, присутствуют вайбы некоторых карт (почему-то больше из Unreal, мне кажется)</i></center>


<br />


{{<img src="images/vagrant_story">}}
<center><i><b>Vagrant Story</b></i></center>


<br />


{{<img src="images/what_remains_of_edith_finch">}}
<center><i><b>What Remains of Edith Finch</b></i></center>


<br />


{{<img src="images/world_of_goo">}}
<center><i><b>World of Goo</b> — велп, и ведь даже не получится сказать, что ничего такого не просил</i></center>




[^mark1]: Захотите поиграться -- там есть линк на простейший в использовании Google Colab-набросок. Если же будет желание развернуть у себя -- имейте в виду, понадобится CUDA (на всякий случай: с её установкой могут быть *проблемы*; если вы не знаете точно, на что идёте -- предприятие рискует затянуться) и более-менее современный Nvidia-GPU с 8 или более ГБайт VRAM. 