﻿
# ﻿Практика «Readonly bytes»
Репозиторий содержит решения [этой](https://ulearn.me/course/basicprogramming2/Praktika_Eksponentsial_noe_sglazhivanie__c334ede2-2c35-4fcb-94cb-fb1c48e3e7bb) задачи с ulearn.me.
Задачи прошли код-ревью у преподавателя (баллы: 100/100). Все решения курса на максимальный балл также выложены в других репозиториях.
Ветка unsolved содержит изначальный проект.

Конечное код можно использовать как библиотеку, чтобы использовать массивы, которые сравниваются по содержимому, а не по ссылкам.

## Практика «Readonly bytes»

Иногда есть смысл в качестве ключей в Dictionary или HashSet использовать массивы байт. Однако по умолчанию массивы сравниваются по ссылкам, а не по содержимому, а часто нужно именно по содержимому. В таких случаях можно написать класс-обёртку над массивом, который переопределит Equals и HashCode так, чтобы сравнение происходило по содержимому. В этой задаче вам нужно создать именно такую обёртку.

В файле ReadonlyBytes.cs создайте класс ReadonlyBytes так, чтобы все тесты из файла ReadonlyBytesTests.cs компилировались и проходили.

