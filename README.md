# Vector

# Описание программы
Аналог контейнера std::vector. Применяется идиома RAII, обеспечивается строгая гарантия безопасности исключений. Количество вызовов конструкторов, деструкторов и присваиваний соответствует std::vector.

# Стек технологий:
  1. Размещающий оператор new<br>
  2. Операторы new и new[], операторы delete и delete[]<br>
  3. Обработка исключений<br>
  4. Три уровня безопасности исключений<br>
  5. Работа с неинициализированной областью памяти : <memory>

# Методы, поддерживаемые текущей версией контейнера:
 - begin
 - end
 - cbegin
 - cend
 - Size
 - Capacity
 - operator[]
 - Allocate
 - Deallocate
 - DestroyN
 - CopyConstruct
 - Destroy
 - Reserve
 - operator=
 - Swap
 - Resize
 - PushBack
 - PopBack
 - EmplaceBack
 - Emplace
 - Erase
Пример использования в файле main.cpp

# Требования:
-std=c++17
g++ (MinG w64) 13.2.0

