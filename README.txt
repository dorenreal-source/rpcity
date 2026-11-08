RP City — мод для Minecraft 26.1.2 (Fabric). Часть 1: мебель.

КАК СОБРАТЬ И ЗАПУСТИТЬ
1. Установи JDK 25 (Temurin 25) и IntelliJ IDEA Community.
2. В IntelliJ: File > Open > выбери эту папку. Дождись, пока Gradle всё скачает.
3. Справа вкладка Gradle: Tasks > fabric > runClient — запустится Minecraft с модом.
4. Готовый .jar: Tasks > build, файл появится в build/libs/ (берёшь rpcity-0.1.0.jar без -sources).
   Для игры нужен Fabric Loader и Fabric API для 26.1.2.

ЧТО ВНУТРИ
Стул, стол, диван, торшер, шкаф, холодильник, плита, кухонная тумба.
Всё во вкладке «Функциональные блоки» (креатив). Есть крафты.
Текстуры пока взяты из ванильных блоков — потом заменим на свои
(assets/rpcity/models/block/*.json).
