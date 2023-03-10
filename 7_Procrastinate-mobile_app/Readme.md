# Анализ убытков приложения ProcrastinatePRO+

# Задача:

для маркетингового аналитика развлекательного приложения Procrastinate Pro+. 
Несмотря на огромные вложения в рекламу, последние несколько месяцев компания терпит убытки. 
Ваша задача — разобраться в причинах и помочь компании выйти в плюс.

* Проведен анализ данных от ProcrastinatePRO+.
* Рассчитаны различные метрики, использован когортный анализ: LTV, CAC, Retention rate, DAU, WAU, MAU и т.д.
* Использованы уже написанные ранее функции расчёта метрик.
* Сделаны правильные выводы по полученным данным.

# Инструменты и навыки:

Pandas Seaborn Matplotlib

когортный анализ, продуктовые метрики, юнит-экономика

# Вывод:

Наш типичный платежеспособный пользователь приложения Procrastinate Pro+ - житель США, пользующийся IPhone, обращающий внимание на рекламу в FaceBoom.

Самая большая средняя стоимость привлечения клиента из канала TipTop-2.80, на втором месте - FaceBoom с 1.11, самая низкая стоимость у 4х каналов: OppleCreativeMedia - 0.25, YRabbit - 0.22, MediaTornado - 0.22, LeapBob 0.21. Возможно, пользователи, пришедшие с самых дорогих каналов, покупают много? ПРедварительно, нужно внимательно просмотреть настройку рекламы в канале TipTop, возможно, она не оптимально настроена с постоянным сливом бюджета. Например, постоянные клики на рекламный баннер. Возможно стоит обратить внимание на 4 самых дешевых канала привлечения рекламы?

3 рекламных канала, которые не окупили вложенных в них инвестиций: AdNonSense, FaceBoom, TipTop. Их основные пользователи - жители США. ПРи этом и удержание платящих пользователей из США оказалось хуже всех. ROI по странам в динамике показал, что с каждым месяцем привлеченные платящие пользователи из США всё хуже окупались, а динамика стоимости привлечения этих пользователей только росла.

Возможные причины, связанные с проблемой рекламы в США:

Летом 2019 произошло какое-то событие в США, которое оказало существенное влияние на поведение пользователей приложения.
Пользователи Mac и IPhone с трудом удерживаются, как платящие, возможно есть проблема с оптимизацией приложения Procrastinate Pro+ именно для ios устройств
TipTop оказался самым неэффективным рекламным каналом. Не стоило так неравномерно распределять бюджет по каналам. Возможно, он, вообще, в этом канале неограничен в настройках. А также, есть вероятность, что в этой соцсети не только жители США, а ее используют жители других стран, которые подключены через VPN. Необоснованное увеличение стоимости привлечения одного клиента в канале TipTop.


Конверсия пользователей FaceBoom была самой высокой, но удержание платящих пользователей было самое низкое. Можно ометить, что этот канал для привлечения работал хорошо, но качество платного контента не устраивало пользователей, поэтому возможно стоит пересмотреть визуаль рекламы для этого канала?


# Рекомендации для отдела маркетинга.
привлекать больше пользователей ПК и Андроида, так как они хорошо удерживаются и стабильно платят.
посмотреть приложение с точки зрения оптимизации именно для устройств Ios.
посмотреть настройки рекламы для канала TipTop - нужен анализ и оптимизация по бюджету и методу оплаты за рекламу(за просмотр, за скачивание приложения, за покупку в приложении и .т.п)


Также необходимо обратить внимание на привлечение пользователей из Европы, там реклама стабильно окупалась.
3 недооценённых канала с лучшей окупаемостью инвестиций: Yrabbit, MediaTornado, lambdaMediaAds. Возможно стоит здесь увеличить бюджеты?
Рекламный канал AdNonSense стоит оптимизировать именно в разрезе Европейского потребителя.
возможно отказаться от инвестиций в OppleCreativeMedia, LeapBob, так как конверсия этих каналов не высокая и они не окупаются обе уже с 4го дня.
Самый высокий LTV у канала lambdaMediaAds, при этом стабильные конверсия и удержание покупателей. Платящим пользователям этого канала приложение Procrastinate Pro+ нравится. Можно попробовать изменить визуальную часть рекламы, чтобы увеличить ROI.
