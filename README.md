# Generative_bot
Генеративный чат-бот, который должен говорить как персонаж Барнин Стинсон из сериала "Как я встретил вашу маму". 
Транскрипты диалогов скачаны с сайта https://scriptmochi.com/tv-series/how-i-met-your-mother
В качестве модели был выбран gpt2. Для обучения подавались реплики указанного персонажа, в качестве лейблов - следующее слово (то есть бот должен предсказать следующее слово персонажа). В итоге бот получился туповат и не сильн опохож на указанного персонажа. Местами да, но он также почему-то начал говорить фразами из Гарри Поттера. 
В планах: попробовать другую модель, T5, например. На данный момент не хватило времени и ресурсов. 
Попробовать расширить датасет за счет, возможно, генерации похожих фраз и потом дообучить модель. Хотелось бы для начала узнать, верна ли моя парадигма обучения бота или нет.
