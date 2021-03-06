# Общие критерии ранкинга

Новые пункты добавляются по результатам обсуждения в [соответствующем форуме](https://osu.ppy.sh/forum/87).
**Обратите внимание,** что в критерии ранкинга также входят [нормы поведения при моддинге и маппинге](/wiki/Modding_Guides/Modding_And_Mapping), которые применяются ко всем игровым режимам.

## Обязательные правила

Всё нижеприведённое является правилами.
Это **не** рекомендации, их **нельзя** нарушать ни при каких обстоятельствах.

### Общие

- **Два игровых объекта не могут находиться на одном тике временной шкалы (исключение — режим [osu!mania](/wiki/Game_Modes/osu!mania)) или перекрываться во времени.**
  Даже если их как-то удастся пройти во время игры, они целиком и полностью разрушают идею следования ритму песни.
- **Не злоупотребляйте [киаи](/wiki/Beatmap_Editor/Kiai_Time).**
  Этим эффектом выделяются важные участки песни, например, припевы. Можно отключать киаи во время припева и затем включать его вновь, если это подходит музыке, но постоянное переключение киаи каждые несколько ударов бессмысленно и отвлекает игроков.
- **Не редактируйте вручную в файлах `.osu` то, что не может быть изменено в редакторе.**
  Исключения: сториборды для отдельных файлов `.osu`, скорости слайдеров и различные настройки скина, например, `SliderBorder` или `SliderTrackOverride`.
- **Фон, сториборд и видеоряд не должны содержать непотребных изображений.**
  Это включает в себя полную и частичную наготу, непристойности, насилие, употребление наркотиков и т.д.
  По возможности старайтесь придерживаться стандарта [PG-13](https://ru.wikipedia.org/wiki/Система_рейтингов_Американской_киноассоциации).
- **Категория [Approved](/wiki/Beatmaps) — только для марафонов.**
  Марафонами являются карты со временем дрейна 5 и более минут.
  Для карт короче требуется полный набор сложностей, и попасть они могут только в категорию [Ranked](/wiki/Beatmaps).

### Мапсет

- **Мапсет должен содержать минимум две сложности одного из режимов игры, одна из которых — `изи` или `нормал`** (это не относится к марафонам).
- **Мапсет должен включать в себя хорошо подобранный набор сложностей,** в том числе по крайней мере одну уровня `изи` или `нормал`.
  Это необходимо, чтобы игроки с любым навыком игры могли играть карты к песням, которые им нравятся.
- **Сложности в мапсете должны идти по возрастанию и/или с приемлемыми промежутками между ними.**
  **В сет можно не включать `изи` или `нормал`, если баланс без них всё ещё сохраняется.**
  - **Низшая сложность должна иметь 2 или менее звезды.**
  - Если мапсет состоит из двух сложностей, одна из них не должна быть `инсейном` или `экспертом`.
  - Уровень сложности в сете с osu!taiko или osu!mania также должен быть сбалансированным и содержать только `хард` или `инсейн`, если имеются стандартные сложности.
  - В osu!catch оценка сложности сета выполняется [номинаторами](wiki/People/Beatmap_Nomination_Group).
  - Сложность определяется по количеству звёзд:
    - ниже 1.5: `изи`;
    - ниже 2.25: `нормал`;
    - ниже 3.75: `хард`;
    - ниже 5.25: `инсейн`;
    - выше 5.25: `эксперт`.
- **Название любой сложности, кроме наивысшей, должно отражать её содержание.**
  Для наивысшей сложности может использоваться любое название, не относящееся к какому-либо игроку или его логину (стандартная форма, например, `Seikatu's Extra`, разрешена).
  - Разрешается назвать все сложности нестандартно, если по названиям можно чётко определить, что сложней чего.

  Марафоны с одной сложностью могут иметь любое название (опять-таки, оно не должно быть связано с другим пользователем).
- **Каждая сложность должна быть создана для одного игрока.**
  Другими словами, TAG2, TAG4 и прочее в мапсет включать нельзя (но ничто не мешает оставить ссылку на них в описании карты).
- **Для osu!taiko или osu!mania нужно как минимум две сложности,** одна из которых должна быть уровня `изи` или `нормал`, если сет osu!standard такую не содержит.
- **В мапсете osu!standard может быть только одна сложность режима osu!catch, если это не экстра,** поскольку стандартный режим корректно конвертируется в osu!catch.
  Для osu!taiko или osu!mania потребуется минимум две сложности osu!catch.

### Метаданные

- **Метаданные должны быть одинаковыми для каждой сложности.**
- **Восточные исполнители (например, корейские, японские, китайские) должны быть указаны в формате `Фамилия Имя`.**
  Если у имени артиста существует устоявшаяся романизация, используйте её.
  Если вы не уверены в правильности написания имён, сверьтесь с другими ранкнутыми картами, Google, Википедией или попросите кого-нибудь из номинаторов о помощи.
- **Японские названия песен для поля `Romanized Artist` должны романизовываться по изменённой системе Хэпбёрна.**
  Длинные гласные, например, おう или うう, должны быть заменены на ou и uu во избежание [макронов](https://ru.wikipedia.org/wiki/Макрон).
  Заимствованные слова романизируются так же, как в языке-первоисточнике.
- **Китайкие названия песен романизуются побуквенно: каждый символ заменяется на отдельное слово, написанное с заглавной буквы.**
  Допускается использование официальной романизации при её наличии.
  Заимствованные слова романизируются так же, как в языке-первоисточнике.
  Подробности: [Romanisation of Chinese](https://osu.ppy.sh/forum/t/244684).
- **Имена вокалоидов могут быть в поле `Artist`, только если продюсер/композитор указали их в официальных источниках.**
- **Не изменяйте название песни.** Сюда относятся изменение капитализации, приписывание `Short Ver`, `TV Size` и так далее.
  Постарайтесь найти в интернетах более-менее официальный источник и возьмите название из него.
  При конфликте источников используйте наиболее распространённое написание.
  - *Примечание переводчика: если у вас на руках оказался буклет с названием (например, от компакт-диска), обращайтесь к нему в последнюю очередь.*
    *Исполнители любят изменять названия в буклетах в угоду оформлению.*
- **Поле `Source` — только для видеоигры, фильма или сериала,** для которого написана или в котором прозвучала песня. В него не вносятся названия сайтов или альбомов.
- **Треки, написанные композиторами, состоящими в каком-либо doujin circle, должны содержать его название в качестве главного исполнителя.**
  Единственное исключение — когда композитор достаточно известен под своим именем, отдельно от сёркла; в этом случае он может быть указан в качестве исполнителя.
- **Не забудьте упомянуть гостевых мапперов.**
  - **Имена гостевых мапперов должны быть включены в тэги.**
  - Информацию о гостях можно также внести в сториборд, слова создателя или названия сложностей, главное — указать мапперов и принадлежащие им участки карт.

### Тайминг

- **Тайминг-секции (красные оффсеты) должны обеспечивать точный тайминг песни.**
  Они должны максимально близко следовать ритму песни и использовать корректную сигнатуру тайминга.
  Если неверная сигнатура длится более, чем 2 доли (2 удара), добавьте ещё один оффсет для исправления.
  Если вы не уверены, что поняли, о чём тут написано, загляните в [статью про тайминг](wiki/Beatmap_Editor/Timing).
- **Ваша карта должна быть идеально затаймлена.**
  Это означает, что BPM и оффсет(ы) выставлены верно, слайдеры кончаются там, где они должны кончаться, круги в общем случае следуют понятному для игрока ритму (такому, как текст песни или ударные), а все объекты начинаются и заканчиваются на тиках временной шкалы.
  Для проверки последнего пункта можно использовать AiMod.
- **Тайминг-секции должны совпадать в каждой сложности мапсета** (даже если, как вам кажется, они ни на что не влияют).
  Тайминг относится не к сложности, а к аудиофайлу.
- **Тайминг-секции не могут применяться для изменения скоростей слайдеров.**
  Это может быть крайне неожиданно для игрока, кроме того, это нарушает пульсацию в меню и делает тайминг не совсем корректным.
- **Два красных или зелёных оффсета не могут быть расположены в одном месте.**
  Наличие двух или более секций одного типа в одном месте может вызвать проблемы в карте.
  Исключение — установка зелёного оффсета на красный для изменения скорости слайдеров.

### Аудио

- **Мапсет может содержать только один аудиофайл, используемый всеми сложностями.**
  Несколько аудиофайлов в одном мапсете не поддерживаются osu! и могут вызвать проблемы с превью, метаданными и др.
- **Используйте аудио приемлемого качества.**
  [Битрейт](https://ru.wikipedia.org/wiki/Битрейт) аудиофайла должен быть не ниже 128 кбит/с и не выше 192 кбит/с; последнее ограничение не относится к переменному битрейту (VBR).
  - Если вы испытываете проблемы с нахождением подходящего аудиофайла, обратитесь за помощью к знающим людям, например, номинаторам.

  Не пытайтесь *увеличивать* битрейт, этим вы ничего не добьётесь.
- **Минимальное время игры для карты — 30 секунд**, рекомендуемое — не меньше 45 (не стоит путать время игры, drain time, с длительностью песни).
  Если ваш трек короче данного минимума, попробуйте увеличить его за счёт закольцовывания трека в аудиоредакторе.
  Цель этого правила — дать людям возможность наслаждаться как можно более полной версией песни и предотвратить чрезмерное её укорачивание.
- **Обрежьте аудио, если используете меньше 80%.**
  Это относится только к окончанию песни: в конце должно быть не более 20% пустого места.
  Если вы планируете замапать только часть песни, то использование полной версии mp3-файла будет бесполезной тратой места на сервере.
  Многие [аудиоредакторы](https://osu.ppy.sh/forum/t/34303) позволяют легко обрезать песню с постепенным затуханием.
  - Если у вас есть веская причина не обрезать аудиофайл после окончания карты (например, продолжается сториборд), то это правило можно не учитывать.
- **Вы должны использовать хитсаунды.**
  Без них карта будет слишком монотонной.
  Совершенно не обязательно ставить их на каждой ноте (это и не требуется), но хитсаунды должны звучать во время игры относительно часто.
- **Хитсаунды должны быть в формате `.wav`.**
  Это — предпочитаемый формат, поскольку `.mp3` могут некорректно зацикливаться и иметь задержку при воспроизведении (0–20 мс).
  `.mp3` можно использовать для особых хитсаундов, например, раскатистых тарелок с начальной задержкой.
  `.ogg` использовать нельзя в любом случае.
- **Звуки на кругах и слайдерах должны быть слышны.**
  Игрок должен слышать отдачу от каждой ноты.
  В конце концов, это ритм-игра, и полное заглушение хитсаундов просто не имеет смысла.
  Если вам не нравятся звуки по умолчанию, то лучше найти те, которые устроят, чем выставлять громкость на минимум.
  - Уменьшение громкости нескольких нот для создания, например, эффекта затухания, допускается, но абсолютное заглушение всё равно не разрешено.
  - Можно глушить спиннер, середину и конец слайдера, но только если это соответствует музыке.
  - **Запрещается** глушить слайдертики и сам звук скольжения по слайдеру одновременно.
- **Не используйте `sliderslide`, `sliderwhistle` и `spinnerspin` для звуков, имитирующих удар по кругу, началу или концу слайдера, звук слайдертика или реверса слайдера.**
  `sliderslide`, `sliderwhistle`, `spinnerspin` — непрерывные хитсаунды, которые закольцованы и звучат на протяжении всего слайдера или спиннера.
  - В попытках обойти это правило нельзя изменять участок со слайдером или спиннером, чтобы хитсаунд проигрывался всего один раз.
- **Песни с матом или «взрослой» тематикой в тексте должны быть помечены символом 18+ (или иначе) в описании карты.**
- **Каждая сложность должна иметь одно и то же превью.** Это используется для проигрывания песни в меню игры и на сайте.
- **Каждый `.wav`-файл должен длиться, по крайней мере, 100 миллесекунд,** во избежание проблем с воспроизведением на некоторых звуковых картах.
  Если требуется полностью убрать звук, вы **должны** использовать [этот пустой файл](https://up.ppy.sh/files/blank.wav).
  - Не пытайтесь использовать вместо него другие «пустые» файлы: они могут быть испорченными (как в случае со звуком, весящим 0 байт), так и быть не пустыми, а просто очень-очень короткими.
- **Задержка в начале хитсаундов не должна превышать 5 мс, за исключением особых случаев.**
  Каждый хитсаунд должен начинаться вовремя (желательно — в 0 мс), чтобы карта не казалась неправильно затаймленной и была синхронизирована с песней.
  Пример особого случая — [шум моря в конце карты](https://osu.ppy.sh/s/104260).
  - Если хитсаунд с задержкой содержится во **встроенном** стандартном скине (например, `normal-hitfinish`), это правило можно опустить.

### Видео

- **Мапсет не может содержать несколько видеофайлов.**
  Это не поддерживается `.osz2` и повлечёт за собой ошибки при выгрузке и обработке карты.
- **Разрешение видео не должно превышать 1280×720 пикселей.**
  Нужно это для того, чтобы не увеличивать размер карты и её ресурсоёмкость слишком сильно.
  Не стоит также растягивать видео с низким разрешением до высокого.
- **Оффсет видео должен быть правильным и одинаковым для всех сложностей,** чтобы видеоряд следовал музыке так, как это изначально предполагалось.
- **Из видеофайла должна быть удалена аудиодорожка.**
  Она не используется в osu! и только занимает место.

### Скин

- **Если вы используете какие-либо элементы, созданные другим человеком, получите у него разрешение.**
  Уважайте чужой труд.
- **Игровые элементы должны быть видимыми.**
  Создание невидимых элементов делает карту неинтуитивной или даже невозможной для игры.
- **Все элементы скина должны быть обработаны** так, чтобы на них не было заметно JPEG-артефактов или наполовину обрезанных теней.
  Если у вас нет фотошопа для этих целей, вы можете использовать бесплатные редакторы, например, Paint.NET или GIMP.
- **Размер фона не должен превышать 1920×1200 пикселей.**
  Изображения с соотношением сторон, отличным от 16:9, будут автоматически обёрнуты в чёрные полосы, обрезаны или отмасштабированы.
- **Фон карты должен быть пристойным.**
  Изображения должны быть приемлемы к публичному показу и не содержать вещей, которые в вашей стране находятся под цензурой.
  Если у вас есть сомнительные изображения, отправьте ссылки на них пользователю [peppy](https://osu.ppy.sh/u/2 "peppy") в [IRC](/wiki/Internet_Relay_Chat). На их основе будет составлен список приемлемых (или неприемлемых) изображений для установления более явных норм.
- **Фон должен присутствовать на каждом уровне сложности на карте.**
  Если в карте есть сториборд, можно скрыть фон в нём, но само изображение должно присутствовать, т. к. оно отображается при выборе песни в меню, на сайте и у игроков, которые играют карту без видео или сторибордов.
- **Следы попадания (300, 100, ...) должны быть хорошо отличимы друг от друга.**
  Самый лучший способ это сделать — раскрасить каждый след в разный цвет.
  В противном случае, игроку будет сложно ориентироваться, попадает он в ритм или нет.
- **Если вы меняете элементы геймплея, то менять нужно всю группу целиком.**
  То, как сгруппированы элементы, можно проверить в статье про [скининг](/wiki/Skinning) в разделе «Группы элементов».
  Например, если вы поменяли вид круга, то это значит, что в карту надо включить `hitcircle.png`, `hitcircleoverlay.png`, `approachcircle.png` и цвет края слайдера (делается вписыванием строчки `SliderBorder: 255,255,255` (цвет в формате RGB) в секцию `[Colors]` в каждом файле `.osu`).
  - Если вы не хотите включать в ваш скин какой-либо элемент, то разрешается использование элемента из стандартного скина.
  Также можно поставить принудительное включение стандартного скина через настройки.
- **Комбо-всплески должны быть ориентированы на появление с левой стороны экрана.**
  По умолчанию они выравниваются по нижней и левой сторонам, а для появления с правой стороны отзеркаливаются.
  Таким образом, нужно лишь проверить, что всплеск аккуратно и правильно обрезан с верхней и правой сторон.
- **Не используйте элементы скина, превышающие по размерам оригинальные.**
  Бо́льшие элементы могут повлиять на производительность игры.
  Однако, элементы, не влияющие напрямую на геймплей (например, картинки во время паузы) могут быть немного больше, если на это есть разумная причина.
- **В папке с картой не должно быть неиспользуемых файлов,** за исключением:
  - Файла с расширением `.osb` (который зачастую присутствует, даже если карта не содержит сториборд)
  - `Thumbs.db` (автоматически генерируется Windows, содержит миниатюры изображений)
  Оставлять неиспользуемые файлы и, следовательно, попусту увеличивать размер карты нельзя.

### Сториборд

- **Размер элементов сториборда не должен превышать 1920×1200 пикселей.**
  Внутреннее разрешение редактора osu! — 854×480.
- **Лишняя прозрачность вокруг картинок должна быть вырезана.**
  Если она вам зачем-то нужна, пожалуйста, объясните, зачем именно.
  Для спрайтов с прозрачностью вокруг картинки должна быть невидимая рамка по крайней мере в 1 пиксель, чтобы картинка правильно отображалась при [интерполяции](https://ru.wikipedia.org/wiki/Интерполяция); также можно использовать тень или свечение.
- **Карты с пульсирующими изображениями или яркими вспышками *должны* иметь предупреждение об эпилепсии,** выставляемое в настройках.
  Полезно также упомянуть об этом в треде с картой.

### Рекомендации

Важные моменты, которым нужно следовать в большинстве случаев.
Если вы почему-то решили их нарушить, подумайте, зачем и для чего.

- **Сложность мапсета должна постепенно нарастать и быть оправданной.**
  - Это означает, что между сложностями не должно быть заметного провала по количеству звёзд.
  - Под оправданностью понимается использование [подходящих по сложности элементов](/wiki/Difficulty_Appropriate_Gameplay_Elements).
  - Если сет начинается сразу с `нормала`, он должен следовать нормам и рекомендациям для `изи`.
  - Если `инсейн` оценен выше, чем в 5 звёзд, лучше добавьте между ним и `хардом` ещё один `инсейн`, но попроще.
- **Используйте не более трёх скоростей слайдеров (включая 1×).**
  Похожие множители можно объединить в один.
- **Изменение скорости слайдеров должно оправдываться заметным изменением в динамике карты.**
  Изменение спейсинга, короткая пауза или слайдер с хотя бы одним тиком помогут показать переход между двумя участками с разными скоростями.
- **Убедитесь, что вы сами можете пройти каждый уровень сложности на вашей карте.**
  Постоянное тестирование своей карты — лучший способ исправлять ошибки и вносить улучшения.
- **Все уровни сложности карты должны заканчиваться на одном месте.**
  Целиком замапанный `хард` и полупустой `нормал` отражают лишь вашу лень.
  Низкие сложности могут казаться скучными для вас, но не для игроков, которые только что начали играть и пока не могут проходить более сложные карты.
- **[Киаи](/wiki/Beatmap_Editor/Kiai_Time) должен быть одинаковым на всех уровнях сложности.**
  Если у вас присутствует гостевая сложность (от другого маппера), то тогда киаи возможен в другом сочетании, если это, конечно же, имеет смысл.
- **Киаи должен начинаться с сильной доли (белого тика).**
  Как правило, припев будет начинаться именно с этой части.
- **Песня не должна быть слишком длинной.**
  Ориентируйтесь на 3−4 минуты игрового времени максимум.
  Всё, что длиннее, либо скучно, либо утомляет игрока.
  Если вам нужно укоротить песню, обратитесь на форум.
- **Не забудьте про перерывы.**
  Даже если они длятся 2–5 секунд, это уже позволит игрокам хоть немного отдохнуть.
  - Избегайте перерывов длинней 15 секунд.
  - Кроме того, перерывы обязательны в `изи` и `нормале`.
- **Настройки вроде обратного отсчёта и леттербоксинга должны быть одинаковыми для каждой сложности.**
- **Старайтесь, чтобы общий размер файла не превышал 10 мегабайт, или 30, если в карте есть видео/сториборд.**
  Размер сториборда или видео может быть уменьшен даже незначительным понижением качества и/или размера.
- **Старайтесь не использовать хитсаунды в сториборде.**
  Если игрок промахнётся по такому объекту, то звук всё равно воспроизведётся, и игрок просто не поймёт, что произошло.
  Использование хитсаундов в местах, где нет никаких объектов, также заставит думать игрока, что эти объекты где-то есть, но он их не видит, что тоже глупо.
- **Озвучивание слайдертиков нежелательно.**
  Если вы хотите для этого использовать хитсаунды, убедитесь, что они не слишком громкие (должны быть заметно тише, чем все остальные хитсаунды).
  Очень громкий звук слайдертика слишком раздражает, кроме того, любой звук должен являться реакцией игры на действие игрока.
- **Старайтесь, чтобы нагрузка сториборда не превышала 5.0×,** чтобы игра не тормозила на слабых компьютерах.
  Нагрузку можно снизить, уменьшив размер картинок в сториборде.
