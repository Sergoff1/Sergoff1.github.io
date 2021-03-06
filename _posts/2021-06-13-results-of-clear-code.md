---
layout: post
title:  "Результаты прохождения курса \"Ясный стиль — выработка хорошего стиля кодирования\""
date:   2021-06-13
tags:
- Качество кода
---

Приветствую на страницах моего блога, читатель. Сегодня я хочу поделиться некоторыми знаниями, полученными мной в ходе прохождения курса по стилю кодирования. Этот курс является следующим после "28 задач повышающейся сложности" в [Высшей школе программирования Сергея Бобровского](https://vk.com/lambda_brain). Он основан на книгах по хорошему стилю кодирования: "Совершенный код" (Стив Макконнелл), "Идеальный программист" и "Чистый Код" (Роберт Мартин) и др. В нём содержится 16 занятий, по основам написания качественного кода. Информация подана кратко, всё по делу, присутствуют примеры, в конце каждого занятия нужно будет выполнить от одного до нескольких заданий, для закрепления материала. Задания заключаются в исправлении своего старого кода, у меня это был код, оставшийся от решения 28 задач.

К этому курсу я приступил примерно через 2 недели после окончания предыдущего, получается что от момента решения первой задачи и до начала уроков по стилю кодирования прошло не больше 2-х месяцев. Мне казалось, что мой код довольно понятен, в нём легко разобраться даже через продолжительное время (давно я так не ошибался:).   
В самом начале разбиралось правильное именование переменных, в конце занятий предлагалось внести несколько правок (обычно 12) в свой код. Вот здесь меня и поджидало немалое разочарование в своих способностях:) Начав разбирать свой код, чтобы дать переменным осмысленные названия, я осознал, что мне не ясен смысл некоторых из них. Пару раз было так, что я не понимал смысл той или иной функции. Приходилось долго смотреть в код, вспоминать что требовалось в задании, в паре случаев, я бы, наверное, и не понял что делают некоторые методы, если бы не отыскал условия задач.  
Тут я и осознал важность качественного написания кода. Прошло всего ничего, а я уже с трудом понимаю написанное, а ведь это мой код. Что было бы, начни его читать другие?

Теперь очень кратко изложу некоторые вещи которые я усвоил из курса по стилю кодирования.  
#### Переменные
Хорошие имена переменных крайне важны для понимания программы.  
- Имена должны точно описывать переменную, быть максимально конкретны.
- Длина имени не должна превышать 20 символов.
- Если какое-то число встречается более двух раз, то есть смысл сделать записать его с помощью константы. Это позволит легко изменить это число во всей программе, если в этом возникнет потребность. Это же справедливо и для строк.
- Для одной сущности одно имя. Не стоит использовать одну переменную сначала для одной вещи, потом для другой. Это внесёт путаницу в код.
- Для булевых переменных следует выбирать такие имена, которые однозначно подразумевают значение true или false.
- Имена должны находиться на уровне том абстракции, на котором решается задача. Не нужно давать имя "Сумма" переменной, если там хранится значение расходов за день, даже если они были вычислены путём суммирования.

#### Методы
- Имя метода должно быть глаголом.
- Имя должно описывать всё то, что делает метод.
- Метод должен делать только одну вещь, это серьёзно упростит понимание программы.

#### Комментарии
Комментарий - признак неудачи. Если что-то приходиться комментировать, значит у нас не получилось ясно выразить свою мысль в коде.
- Если возникает желание написать комментарий, то стоит пересмотреть код, можно ли его переделать, чтобы упростить восприятие написанного.
- Следует избегать неинформативных комментариев, тех, что не приносят ничего для понимания кода.
- Хороший комментарий может подчеркивать важность некоторых, кажущихся на первый взгляд незначительных, обстоятельств.
- Имеет смысл прояснять комментариями загадочные аргументы/возвращаемые значения, в тех случаях, если используется код, который вы не можете изменить.

### Итоги
Здесь описана небольшая часть того, что есть на курсе. Кроме вышеописанного там можно встретить советы по работе с типами данных, классами, интерфейсами, массивами. Больше узнать о работе с переменными, методами, комментариями. Я же привёл лишь некоторую часть информации, потому что не хочу копировать курс, а это трудно, ибо информация там подана совсем без воды.

Самое главное: что же изменилось в моём коде благодаря этому курсу.  
Теперь можно смело сказать, что даже через приличное время я пойму свой код. Чтобы узнать, что делает функция, достаточно взглянуть на её название. Также и с переменными, достаточно посмотреть на их имена, как сразу станет ясно что в них хранится. А приличную часть комментариев я убрал, ибо они оказались излишни, после переработки кода. Помимо этого я стал активнее использовать константы, что позволит с минимумом усилий менять некоторые вещи в программе.  
Подводя черту можно сказать, что данный курс, позволил мне хорошо прокачать навык необходимый каждому программисту, навык позволяющий писать чистый и понятный код. Конечно, это не конец пути, нужно не только поддерживать полученные умения, но и всячески улучшать их, ибо нет предела совершенству. Но старт дан хороший, уже сейчас я знаю как писать достойный код, который будет понятен не только мне, но и другим людям.

А на этом всё, спасибо за внимание.