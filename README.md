# Roadmap DE interview
1. **SQL** &mdash; база любого ДЕ собеса на любой уровень (джун, мидл и тд).
   
   Необходимые знания:
   * умение писать базовые запросы (SELECT, WHERE, ORDER BY и тд);
   * умение джойнить таблицы, знание всех видов джойнов и чем они отличаются друг от друга (LEFT, RIGHT, INNER, CROSS, FULL);
   * умение работать с подзапросами (подзапросы в WHERE, подзапросы в FROM, знание что такое CTE и умение работать с ней);
   * очень желательно знать и уметь работать с оконными функциями;
   * желательно уметь понимать план запроса, в какой очередности выполняются операторы запроса SQL;

   Материалы для подготовки:
   * [DataLemur](https://datalemur.com/sql-tutorial) &mdash; курс по SQL, затрагивающий почти все вышеперечисленные темы (возможно нужен VPN, чтобы зайти на сайт);
   * [LeetCode](https://leetcode.com/studyplan/top-sql-50/) &mdash; задачи для решения, очень круто готовят к собесу, рекомендую решать все и по порядку;

2. **Python** &mdash; тоже база любого ДЕ собеса.

   Рекомендации &mdash; я думаю с питоном по знаниям все ок :) так что советую посмотреть пару роликов именно с вопросами с собесов по питону. Вот хорошие:
   * [Первый видос](https://www.youtube.com/watch?v=BoazgBZ4D7k);
   * [Второй](https://youtu.be/25xUoLye53w?si=GG02X_gJlZmxvZei);

4. **HADOOP** &mdash; в целом, тебе должны будут рассказать с чем ты будешь работать, какой стек и тд, но по моему опыту, в РФ и тем более в банках чаще всего работают на своих Hadoop кластерах, поэтому знание того, что это такое и основных принципов работы желательно:

   Знания:
   * как устроен Hadoop, основные принципы работы и концепты;
   * основные компоненты Hadoop;
   * концепция MapReduce &mdash; что это такое, как работает и тд;

    Материалы:
   * [Курс на степике](https://stepik.org/course/150/) &mdash; очень хороший курс по Hadoop, рекомендую к прохождению. Советую обязательно пройти 1-3 главы, и все материалы про Hive, Spark и Yarn, остальное уже по желанию;

     В целом, этого курса для начала мне сполна хватило :)

  5. **Spark** &mdash; почти уверен, что будут по нему спрашивать, но скорее всего тебе точно скажут что будет на собесе потом.

     Знания:
     * Понимание работы Spark, основных его концепций, почему он быстрее и лучше MapReduce;
     * Что такое RDD/DF/DS;
     * Как Spark выполняет запросы (спойлер: _лениво_)
     * На какие два типа делятся операции в Spark (actions/transformations), в чем различия, умение привести примеры операций каждого типа;
     * Что такое shuffle?
     * _Желательно:_ стратегии джойнов Spark;
     * _Желательно:_ знание, что такое broadcast и когда его применять, в чем его преимущества (спойлер: данные не шаффлятся);
    
     Материалы:
     * Глава про Spark в курсе по Hadoop'у упомянутом выше;
     * [Книжка](https://drive.google.com/file/d/1F-uAeAdEyr7XddGK_RtBnWYLyHALjrlH/view?usp=sharing) &mdash; просто офигенная книга, очень мало воды, много полезной теории, нашел здесь ответы почти на все вопросы со своих собесов. Советую обязательно прочитать первые пять глав, остальные по желанию. Рекомендую читать по порядку;
     * [Задачки](https://platform.stratascratch.com/coding?is_freemium=1&user_solution_state=unsolved&code_type=6&order_field=difficulty) &mdash; платформа с задачками для подготовки к собесам по SQL. Здесь также можно писать на pySpark, так что рекомендую попрактиковаться;
    
Из основного вроде все, могут также спросить что-нибудь про Linux, Airflow и какой-нибудь Docker, но, думаю, список основных тем на собесе тебе пришлет либо рекрутер, либо узнаешь на первой встрече со своим лидом, если такая будет.

**Желаю удачи, у тебя все получится! :)**
