Проект job4j_spring -  Spring.

Разберем причину появления Spring.
Идея DI.
1. Есть хранилище объектов. В нем мы будем регистрировать классы, объекты которых хотим иметь в проекте
2. Хранилище в рамках DI называется Context, то есть объекты относящиеся к предметной области нашего проекта.
3. После регистрации классов Context начинает инициализацию объектов. Он стоит дерево зависимостей. 
4. Сначала он создает объекты без зависимостей, а потом создаем объекты с зависимостями.
5. После инициализации программист может получить нужный объект из Context.
