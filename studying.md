# Изучение

Когда вы нашли колоду которая вам нравится или добавили несколько записей
самостоятельно --- пора начинать обучение.

## Колоды

Заучивание карточек в Anki осуществляется в пределах выбранной в настоящий
момент колоды и любых подколод которые она содержит.

На экране колод ваши колоды представлены в виде списка. В нем присутствуют два
числовых столбца: 'К просмотру' и 'Новые'. 'К просмотру' --- это количество
ожидающих повторения и уже разучиваемые карточки. 'Новые' --- это количество
новых карточек, которые подготовлены к заучиванию в этот день.

При нажатии на колоду она станет 'текущей колодой' и Anki переключится на экран
изучения. Вы можете вернуться к списку колод, чтобы изменить выбранную в данный
момент колоду в любое время, нажав на 'Колоды' в верхней части главного окна.
(Можно также использовать действие Учить колоду для выбора новой колоды с
клавиатуры или нажать клавишу 's' для изучения выбранной в данный момент
колоды.)

Можно нажать кнопку шестерёнки справа от колоды, чтобы переименовать или удалить
колоду, изменить её параметры или [экспортировать](exporting.md) её.

Если в колоде имеются подколоды, карточки отобразятся из [каждой колоды по
очереди](studying.md#Порядок-отображения).

## Общие сведения об изучении

После нажатия на колоду для изучения, вы увидите экран на котором показано
сколько карточек у вас запланировано на сегодня. Это называется экраном
'обзора колоды'. Карточки разделены на три типа:

- **Новые** --- это карточки, которые вы скачали или добавлены вручную, но
  никогда раньше не изучали.

- **Изучаемые** --- это карточки, которые недавно были показаны первый раз и
  сейчас в процессе изучения.

- **Повторяемые** --- это карточки, которые были изучены ранее, а теперь должны
  быть пересмотрены, чтобы вы их не забыли.

Чтобы начать сеанс заучивания, нажмите кнопку **Учить**. Anki будет показывать
вам карточки до тех пор, пока запланированные на сегодня карточки не закончатся.

В процессе изучения можно вернуться к обзору, нажав клавишу "s" на клавиатуре.

## Вопросы

При показе карточки, сперва показывается только вопрос. Подумав над ответом,
нажмите либо кнопку **Показать ответ**, либо пробел на клавиатуре --- будет
показан ответ. Это нормально, если вам потребуется немного времени, чтобы
вспомнить ответ, но, как правило, если вы не можете ответить в течение 10
секунд, скорее всего, лучше сдаться и показать ответ, чем продолжать пытаться
его вспомнить. 

Когда покажется ответ, вам следует сравнить его с тем который вы придумали и
сообщить Anki, на сколько точно вы запомнили. Если вы не уверены в точности
сравнения ответов, вы можете указать Anki [предлагать вам набирать ответ с клавиатуры](templates/fields.md#Проверка-своего-ответа), а не просто показывать его вам.

Количество кнопок, доступных для оценки ответа, зависит от того, является ли
карточка 'изучаемой' или 'повторяемой'.

## Обучение

При изучении новых или переучивании забытых карточек, Anki будет показывать
карточки по одному или нескольку раз, чтобы помочь вам их запомнить. Каждый
такой показ называется 'обучающий шаг'. По умолчанию установлено два
шага: 1 минута и 10 минут. Количество и продолжительность таких шагов можно
изменить в [настройках колоды](deck-options.md).

В процессе обучения доступны три кнопки оценки:

**Снова** --- перемещает карточку обратно к первому шагу.

**Хорошо** --- перемещает карточку на следующий шаг. Если карточка была на
последнем шаге, то она переводится [прим. перев. *из изучаемой*] в повторяемую
карточку (она 'выпускник' (англ. *graduate*)). По умолчанию, карточка достигнув
конца обучающих шагов, будет показана снова на следующий день, затем задержки
между показами будут увеличиваться (смотрите следующий раздел).

**Легко** --- немедленно переводит карточку в повторяемую, даже если остались
ещё шаги. По умолчанию, карточка будет показана повторно через 4 дня, затем
задержки между показами будут увеличиваться. Лёгкая кнопка не будет показана,
если вы в режиме переучивания, и это задаст тот же интервал, что и "хорошо".

Когда карточки показываются в первый раз, они начинают на первом шаге. Это
означает, что ответив **Хорошо** на карточке с первого раза покажет её ещё раз
через 10 минут, а первый шаг в 1 минуту будет пропущен. Если вы нажмёте Снова,
карточка вернется через 1 минуту.

Вы можете использовать клавиши 1, 2 и 3 на клавиатуре, для выбора конкретной
кнопки, где 1 --- это **Снова**. Нажатие клавиши пробела выбирает **Хорошо**. 

Если нет других карточек для показа, Anki снова покажет изучаемые карточки,
даже если их задержка полностью не закончилась. Если вы предпочитаете ждать
всю обучающую задержку, вы можете изменить поведение в [настройках](preferences.md).

## Повторение

Когда карточка уже была изучена и готова к повторению, есть четыре кнопки для
оценки ответа:

**Снова** --- помечает ваш ответ как неверный и указывает Anki чаще показывать
карточку в будущем. Карточка считается 'забытой' (англ. *lapsed*). Смотрите
раздел [забытые](deck-options.md) для получения более подробной информации о
том, как обрабатываются забытые повторения.

**Трудно** --- показывает карточку с чуть большей задержкой, чем в прошлый раз
и указывает Anki чаще показывать карточку в будущем.

**Хорошо** --- сообщает Anki, что последняя задержка была примерно правильной и
лёгкость карточки не нуждается в уменьшении или увеличении. При значении
лёгкости по умолчанию, задержка перед следующим показом карточки будет примерно
в 2,5 раза дольше чем в предыдущий раз, так что если бы вы в прошлый раз ждали
10 дней, чтобы увидеть карточку, то следующая задержка составит около 25 дней.

**Легко** --- сообщает Anki, что вы сочли задержку слишком короткой. Карточка
будет запланирована дальше, чем при ответе 'Хорошо' и в последствии Anki будет
включать её в расписание чуть реже. Поскольку 'Легко' быстро увеличивает
задержку, она лучше всего подходит для, действительно, самых простых карточек.
Обычно вместо этого ответа, стоит использовать ответ 'Хорошо'.

Как и с изучаемыми карточками, вы можете использовать клавиши 1-4 на клавиатуре
для выбора ответа. Нажатие клавиши пробела выбирает **Хорошо**.

## Due Counts

Когда показывается только вопрос, Anki показывает в нижней части экрана три
числа вроде 12 + 34 + 56. Они обозначают новые карточки, изучаемые карточки и
повторяемые карточки. Если вы предпочитаете не видеть этих цифр, вы можете
отключить их в настройках Anki.

В старом планировщике, считается количество _просмотров_ необходимое для
завершения всех карточек в этой очереди, а не количество самих _карточек_. Если
задано несколько шагов для забытых карточек, то число увеличивается более чем
на один, если вы не справились с карточкой, так как она должна быть показана
несколько раз.

В новом планировщике, считается количество _карточек_, так что число всегда
увеличивается на один, независимо от оставшихся шагов.

Когда отображается ответ, Anki выводит примерное время следующего показа
карточки над каждой кнопкой. Если вы предпочитаете не видеть оценок, вы можете
отключить их в [настройках](preferences.md) Anki.

Кроме того, Anki случайным образом не много изменяет время следующего показа,
чтобы предотвратить случаи, когда карточки добавленные вместе и всегда
получавшие одинаковые оценки продолжали бы и дальше показываться одна за
другой. Эти изменения не отражаются в оценках времени, а применяются после
выбора кнопки.

## Правка и ещё

Для изменения текущей заметки нажмите кнопку **Правка** в левом нижнем углу.
Завершив редактирование вы будете возвращены к обучению. Экран редактирования
работает аналогично экрану [добавления записи](editing.md)

В правом нижнем углу экрана просмотра находится кнопка **Ещё**. Эта кнопка
предоставляет несколько других операций, которые можно выполнить с текущей
карточкой или записью:

Поставить флаг  
Ставит цветную метку на карточку или убирает её. Метки будут отображаться во
время изучения, а в окне Обзора можно выполнять поиск отмеченных карточек. Это
полезно, когда вы хотите выполнить некоторое действие над карточкой позднее,
например, когда вернётесь домой, поискать какое-нибудь слово.

Отметить запись  
Добавляет текущей записи метку "marked", что позволяет легко найти её в
обозревателе. Это схоже с отметкой отдельных карточек, только работает с
метками (англ. *tag*), поэтому, если в записи есть несколько карточек, все они
появятся в поиске по метке marked. Большинству пользователей лучше использовать
флаги --- отметки, в основном, оставлены для совместимости с более старыми
версиями Anki.

Отложить карточку / запись  
Прячет карточку или все карточки записи от показа до следующего дня. (Если вы
хотите вернуть карточки раньше, нажмите кнопку "вернуть" в окне [обзора колоды](studying.md#Общие-сведения-об-изучении).)
Это полезно, если в данный момент вы не можете ответить на карточку или хотите
вернуться к ней в другой раз. Откладывание также может [произойти автоматически](studying.md#Связанные-и-отложенные)
для карточек одной записи. Если карточки находятся в процессе изучения на момент
их откладывания, то сперва они перемещаются обратно в очередь новых карточек или
очередь повторяемых перед тем как быть отложеными.

Исключить карточку / запись  
Прячет карточку или все карточки записи от показа до тех пор, пока они не будут
включены вручную (нажатием кнопки исключения--включения в окне обзора). Это
полезно, если вы не хотите повторять запись некоторое время, но не хотите
удалять её. Если карточки находятся в процессе изучения на момент их исключения,
то сперва они перемещаются обратно в очередь новых карточек или очередь
повторяемых перед исключением.

Удалить запись  
Удаляет запись и все её карточки.

Настройки  
Редактировать настройки текущей колоды.

Повторное воспроизведение аудио  
Если у карточки есть аудио на лицевой или оборотной стороне, воспроизводит его повторно.

Записать свой голос  
Запись с микрофона для проверки произношения. Это временная запись и она
исчезнет при переходе к следующей карточке. Если вы хотите добавить на карточку
постоянную аудио-запись, то это можно сделать в окне редактирования.

Воспроизвести свой голос  
Воспроизвести предыдущую запись своего голоса (предположительно, после показа
ответа).

## Порядок отображения

В процессе изучения показываются карточки из текущей выбранной колоды и всех
колод, которые она содержит. Таким образом, если вы выберете колоду
"Французский", подколоды "Французский::Словарь" и "Французский::Моя тетрадь::Урок 1"
также будут показаны.

Новые и повторяемые карточки Anki выбирает из расположенных в алфавитном
порядке колод. Так в приведенном выше примере, сначала вы увидите карточки
из колоды "Моя тетрадь", затем "Словарь", и, наконец "Французский". Это можно
использовать для управления порядком отображения карточек, помещая карточки с
большим приоритетом в колоды, находящиеся выше по списку. При компьютерной
сортировке текста по алфавиту, символ "-" идёт перед буквами алфавита, а "\~"
--- после них [прим. перев. *но перед русскими. В русских (кириллических)
названиях колод вместо "\~" можно использовать знак "№"*]. Значит, вы можете
назвать колоду "-Французский", чтобы она отображалась первой, а другую ---
"№Словарь", чтобы отображать её после всего остального.

Новые и повторяемые карточки выбираются отдельно, и Anki не будет ждать, пока
закончатся обе очереди, прежде чем перейти к следующей колоде, так что
возможно, вам будут показываться новые карточки из одной колоды и повторяемые
из другой, и наоборот. Если вам это не подходит, нажимайте непосредственно
на колоду которую хотите изучать, а не на родительские колоды.

Изучаемые карточки, поскольку у них, так сказать, жесткий временной режим,
выбираются из всех колод одновременно и отображаются в порядке своей очереди.

Для управления порядком, в котором появляются карточки из определённой колоды,
или изменения порядка показа новых карточек из упорядоченного в произвольный,
смотрите в [настройках колоды](deck-options.md). Ещё более точно настроить
порядок появления новых карточек можно в [обозревателе](browsing.md).

## Связанные и отложенные

Вспомним из [основ](getting-started.md), что Anki может создавать более одной
карточки из каждой записи, например, карточки лицо→оборот и оборот→лицо, или
два разных заполнения пропусков из одного текста. Такие карточки, относящиеся к
одной записи, называются 'связанными'.

Отвечая на одну из связанных карточек, Anki может предотвращать показ связанных
с ней карточек в этот же день, автоматически 'откладывая' их. Отложенные
карточки скрыты от повтора до тех пор, пока на часах не наступит следующий день
или вы вручную не вернёте их при помощи кнопки "Вернуть" отображаемой внизу
экрана [обзора колоды](studying.md#Общие-сведения-об-изучении). Anki отложит
связанные карточки даже если они находятся в разных колодах (например, если вы
используете функцию [подмена колоды](templates/intro.md)).

Вы можете включить откладывание в окне [настроек колоды](deck-options.md) ---
отдельно для новых и повторяемых карточек.

Anki будет откладывать связанные карточки, которые являются новыми или
повторяемыми. Изучаемые карточки не будут скрываться, поскольку время для них
имеет существенное значение. С другой стороны, заучивая карточку которая
является изучаемой, любые новые/повторяемые карточки будут отложены.

## Клавиатурные сокращения

Для большинства общих действий в Anki имеются клавиатурные сокращения. Многие
из них легко обнаружить в элементах интерфейса: рядом с пунктами меню
отображаются их клавиатурные сокращения, а наведение курсора мыши на кнопку, как
правило, показывает её клавиатурное сокращение во всплывающей подсказке.

Во время обучения, как пробел так и клавиша ввода покажут ответ. Когда
покажется ответ, вы можете использовать клавиши пробела или ввода для выбора
кнопки Хорошо. Для выбора конкретной кнопки лёгкости можно использовать клавиши
1-4. Многим людям удобно отвечать на большинство карточек клавишей пробела и
держать один палец на цифре 1, на случай если забыли ответ.

Пункт "Учить колоду" в меню Инструменты позволяет вам быстро переключиться на
другую колоду с помощью клавиатуры. Вызвать его можно клавишей '/'. Будучи
открытым, в нём отображаются все ваши колоды и строка фильтра сверху. По мере
ввода символов, Anki будет отображать только те колоды которые соответствуют
введённым вами символам. Можно добавить пробел для разделения нескольких
условий поиска, и Anki покажет только колоды, соответствующие всем условиям.
Так "яп 1" или "ок1 яп" в обоих случаях будут соответствовать колоде
"Японский::Урок1".

## Отставание

Если вы отстали от графика повторения, Anki отдаст предпочтение карточкам,
которые ждут дольше всех. Она выбирает карточки ожидающие дольше всех и
показывает их в случайном порядке до тех пор, пока не будет исчерпан суточный
лимит показов. Такой порядок гарантирует, что никакие карточки не останутся в
состоянии вечного ожидания, однако это означает, что если вы добавите новых
карточек, то не увидите их до тех пор, пока не наверстаете отставание.

Если вы хотите изменить порядок просмотра просроченных карточек, вы можете это
сделать с помощью создания [фильтрованной колоды](filtered-decks.md).

Отвечая на карточки, некоторое время находившиеся в ожидании, Anki учитывает
эту задержку при определении времени следующего показа карточки.
Дополнительную информацию смотрите в разделе про [алгоритм](faqs.md)
интервальных повторений Anki.
