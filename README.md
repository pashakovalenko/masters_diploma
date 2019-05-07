# ~~Здесь будет~~ Блог про мой магистерский диплом

**Задача**: закончить магистратуру.

**Дедлайн**: 01.07.19.

* * *

**08.05.2019**. Исправил замечания с предзащиты, текущую версию отправлю рецензенту А.А. Докукину. Также выкладываю [презентацию с предзащиты](https://github.com/pashakovalenko/masters_diploma/blob/master/presentation/draft.pdf).

* * *

**01.05.2019**. Добавил введение, заключение, список литературы.

* * *

**14.04.19**. Написал главу про сам алгоритм, про SVD++, вставил графики про MovieLens и Million Playlist Dataset.

* * *

**09.04.19**. На Ломоносове В.В. Китов предложил для RW с вероятностью остановки сделать зависимость между вероятностью остановки и степенью вершины. Надо бы попробовать. Хотя параметризовать это будет сложно.

* * *

**07.04.19** Досчитались основные эксперименты, внес в текст диплома.

Подготовил [презентацию на Ломоносова](https://github.com/pashakovalenko/masters_diploma/blob/master/lomonosov/presentation.pdf), выступление во вторник.

* * *

**17.03.19**. Написал разделы про метрики в задаче ранжирования и BPR.

* * *

**03.03.19**. Подал [тезисы на ломоносова](https://github.com/pashakovalenko/masters_diploma/blob/master/lomonosov/thesis.pdf).

Успел провести эксперименты с ALS и BPR на ML-1m, ML-20m и Million Playlists Dataset.

Все еще не дописал первую главу диплома, планирую к 17 марта.

* * *

**26.02.19**. Провел эксперименты на ML-1m с ALS и BPR. Для BPR получается значительный прирост по точности, для ALS - поменьше. Но метод работает.

Сейчас ставлю эксперименты на ML-20m. Хочу успеть до выходных подать тезисы на Ломоносова.

* * *

**02.02.19**. 
* Написал несколько страниц воды для диплома. 
* Написал програмку на плюсах, которая случайно блуждает по графу и пишет результат в файл. Сначала написал на питоне, но получилось очень медленно, на серьезных датасетах совсем не запустить.
* По поводу датасетов. Сейчас взял MovieLens (x4) и Million Playlist с последнего RecSys'а. Можно по приколу взять датасет с работы, но не раскрывать подробности про природу данных.

К 17 февраля:
* Провести первые эксперименты, хотя бы proof of concept на ML-100k
* Дописать в тексте про метрики качества, нарисовать картинки и таблицы про датасеты. Введение пока не хочу писать, там должны быть намеки на то, какие результаты получены в работе, а результатов пока не видно.

* * *

**20.12.18**. До 1 февраля нужно
* Написать введение
* Выбрать датасеты
* Написать прототип программы, хотя бы как в статье

* * *

**09.12.18**. Я прочитал несколько релевантных статей. Сохраняю их здесь: https://docs.google.com/spreadsheets/d/1taaTBxiEgajltQxlpEucfZg6Ti2Zx6Ec24rpBAZZl3A/edit#gid=0

Текущий план примерно следующий: расширить 3-ю статью из списка (про Random Walks + Matrix Factorization), попробовать другие способы вычисления random walks (нефиксированная длина пути, невзвешенные переходы, точный подсчет распределения vs семплирование путей) и другие алгоритмы обучать на их выходе (pointwise SVD, SVD++ или Factorization Machines, возможно бустинги, обучать ранжирование или бинарный таргет с весами). Все это проверять, вероятно, на MovieLens, потому что в половине статей точность меряют на нем.

* * *

**31.10.18**. Выкладываю [презентацию с выступления на спецсеминаре](https://github.com/pashakovalenko/masters_diploma/blob/master/presentations/1_recsys.pdf)

Зафиксировали тему диплома - "Использование случайных блужданий по графу для повышения качества рекомендаций"

* * *

**12.10.18**. Почитал решения последних лет. Есть несколько интересных и неочевидных идей, но все это скорее какие-то хаки, которые можно попробовать применить на практике, но которые неинтересно рассказывать в обзорной презентации.

Планирую еще немного погуглить, посмотреть статьи с последнего RecSys'а, не получившие best paper. Настораживает, что пока не видел статей про использование нейронок в рекомендациях.

* * *

**08.10.18**. Начал читать решения RecSys Challenge. 

[Табличка с кратким содержанием решений](https://docs.google.com/spreadsheets/d/11-0LiNUxZDPdB0K-BxQjABRb64M-nsTvD-GtrCuCtcI/edit#gid=1469726117)

* * *

**07.10.18**. Дочитал best paper'ы, обновил таблицу. Среди статей последних лет есть несколько интересных с практической точки зрения, взял на заметку. Дальше по плану - почитать лучшие решения RecSys Challenge прошлых лет.

* * *

**23.09.18**. Читал best paper'ы с RecSys'ов прошлых лет. Много статей из области около-рекомендаций (поиск поддельных отзывов, особенности рекомендаций в социальных графах) и fine-tuning (учет неслучайных пропусков в данных). Свежих подходов пока не видел, в основном улучшения SVD и затачивание под конкретные задачи.

[Табличка с просмотренными статьями и моими комментариями](https://docs.google.com/spreadsheets/d/11-0LiNUxZDPdB0K-BxQjABRb64M-nsTvD-GtrCuCtcI/edit#gid=0).

* * *

**13.09.18**. Решили, что будем заниматься рекомендательными системами.

Текущая задача - доклад на спецсеминаре про свежие подходы к рекомендациям на основе статей с последних RecSys. Доклад запланирован на 15.10.
