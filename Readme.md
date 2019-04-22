## 23.04.2019.2

1. Форкнуть данный репозиторий.
2. Склонировать свою ветку к себе на десктоп.
3. Заполнить проекты EnumerableExtension и EnumerableExtension.Tests необходимой функциональностью.
4. Синхронизировать изменения с содержимым своего репозитория на gitub-e.
5. Сделать pull request к данному репозиторию.


## Постановка задания

- Как альтернативу классу [EnumerableExtension](https://github.com/AnzhelikaKravchuk/23.04.2019.1/blob/master/PseudoEnumerable/EnumerableExtension.cs) создать класс Enumerable, в который добавить:
  - методы для фильтрации и трансформации последовательности, использующие в качестве параметров соответсвующие версии типа делегат [`Func<T>`](https://docs.microsoft.com/en-us/dotnet/api/system.func-2?view=netframework-4.8);
  - метод SortBy, использующий стратегию сортировки по ключу (сортировка по возрастанию) (*не стратегию сравнения двух элементов*);
  - метод SortBy, использующий стратегию сравнения двух ключей (сортировка по возрастанию);
  - **метод SortByDescending, использующий стратегию сортировки по ключу (сортировка по убыванию);**
  - **метод SortByDescending, использующий стратегию сравнения двух ключей (сортировка по убыванию);**
- Проверить работу разработанных методов, используя различные типы данных.
