
### Оглавление

- #### [[#**Ticket 2 Basic Syntax**|Ticket 2: Basic Syntax]]
	- [[#Ticket 2 Введение]] 
	- [[#Арифметика и типы]]
	- [[#Функции]]
	- [[#Операторы]]
	- [[#Тип List]]
	- [[#Конструкции и выражения]]
	- [[#Функции высшего порядка]]
	- [[#Полиморфизм]]
	- [[#Каррирование и частичное применение]]
	- [[#Функции]]
	- [[#Сопоставление с образцом]]
	- [[#Расширения языка]]
	- [[#Применение функций]]
	- [[#Оператор композиции `.`]]
	- [[#Генерация списков]]
	- [[#Ленивое вычисление]]
- #### [[#**Ticket 3 Datas, Classes, Instances**|Ticket 3: Datas, Classes, Instances]]
	- [[#Ticket 3 Введение]] 
	- [[#Custom Types (Пользовательские типы)]]
	- [[#ADT (Алгебраические типы данных)]]
	- [[#Record Types (Типы-записи)]]
	- [[#Type Classes (Классы типов)]]
	- [[#Модули]]
	- [[#Дополнительные темы]]
	- [[#Ticket 3 Итог]]
- #### [[#**Ticket 4 Basic typeclasses: Monoid, Functor, Applicative**|Ticket 4: Basic typeclasses: Monoid, Functor, Applicative]]
	- [[#1. Type-classes]]
		- [[#1.1. Semigroup (Полугруппа)]]
		- [[#1.2. Monoid (Моноид)]]
	- [[#2. Свёртка (Fold)]]
		- [[#2.1. `foldr` и `foldl`]]
		- [[#2.2. Класс `Foldable`]]
	- [[#3. Functor]]
	- [[#4. Applicative]]
	- [[#5. Alternative]]
	- [[#6. Traversable]]
	- [[#7. Фантомные типы]]
	- [[#8. Расширения]]
		- [[#8.1. `ScopedTypeVariables`]]
		- [[#8.2. `TypeApplications`]]
		- [[#8.3. `AllowAmbiguousTypes`]]
- #### [[#**Ticket 5 Monads|Ticket 5: Monads]]
	- [[#Введение в монады]] 
	- [[#Примеры монад]]
		- [[#1. Maybe Monad]]
		- [[#2. Either Monad]]
		- [[#3. List Monad]]
	- [[#Композиция монад]]
	- [[#Операторы и функции]]
		- [[#1. Оператор `>>` (Zen)]]
		- [[#2. Функция `join`]]
	- [[#Монадические законы]]
	- [[#Специализированные монады]]
		- [[#1. Writer Monad]]
		- [[#2. Reader Monad]]
		- [[#3. State Monad]]
	- [[#Дополнительные темы]]
- #### [[#**Ticket 6 RealWorld|Ticket 6: RealWorld]]
	- [[#1. `getchar` и проблемы чистых функций]] 
	- [[#2. `RealWorld` и модель `IO`]]
	- [[#3. `do`-нотация и порядок выполнения]]
	- [[#4. Работа с вводом-выводом]]
	- [[#5. Ленивое IO и проблемы]]
	- [[#6. FFI (Foreign Function Interface)]]
	- [[#7. Изменяемые объекты]]
	- [[#8. Исключения]]
	- [[#9. Класс `Exception`]]
	- [[#10. Полезные функции для работы с исключениями]]
	- [[#11. Небезопасные операции (`unsafePerformIO`)]]
	- [[#12. Работа со строками `Text` и `ByteString`]]
- #### [[#**Ticket 7 Monad Transformers|Ticket 7: Monad Transformers]]
	- [[#Монады как эффект]] 
		- [[#Пример комбинирования эффектов]]
	- [[#Реализация монадных трансформеров]]
		- [[#Пример с MaybeT]]
		- [[#Класс MonadTrans]]
		- [[#Пример с ReaderT]]
		- [[#MonadIO для работы с IO]]
	- [[#Пакет mtl]]
	- [[#Класс `MonadReader`]]
	- [[#Обработка исключений]]
		- [[#Классы MonadThrow и MonadCatch]]
		- [[#Класс MonadError (из mtl)]]
	- [[#Ticket 7 Итог]]
- #### [[#**Ticket 8 Speeding up Haskell**|Ticket 8 Speeding up Haskell]]
	- [[#DList]]
	- [[#Строгость в Haskell]]
	- [[#Оптимизация прохода по списку]]
	- [[#Изменяемые объекты]]
- #### [[#**Ticket 9 Parallel and Concurrent Haskell|Ticket 9: Parallel and Concurrent Haskell]]
	- [[#Fork a thread]] 
	- [[#Where is my join?]]
	- [[#More about MVar]]
	- [[#What to do thread id?]]
	- [[#Exceptions classification]]
	- [[#Handle exception]]
	- [[#Masquerade]]
	- [[#Bracket is your friend]]
	- [[#Never use forkIO]]
	- [[#Async package - Basic primitives]]
	- [[#Concurrently newtype]]
	- [[#Async package - Advanced usage]]
	- [[#Transactions (1/3, 2/3, 3/3)]]
	- [[#STM]]
	- [[#Преимущества неизменности]]
	- [[#Parallel primitives]]
	- [[#Classic example: fib]]
	- [[#threadscope]]
	- [[#What about sparks?]]
	- [[#Innacurate parallelism]]
	- [[#What else?]]
	- [[#Дополнительно]]
- #### [[#**Ticket 10 Template Haskell and Lens|Ticket 10: Template Haskell and Lens]]
	- [[#Введение в проблему доступа к полям структур]] 
	- [[#Основы линз]]
		- [[#1. Определение линзы]]
		-  [[#2. Пример реализации]]
		-  [[#3. Композиция линз]]
	- [[#Обобщенные линзы и функторы]]
		- [[#1. Линзы как обобщенные функции]]
		- [[#2. Законы линз]]
	- [[#Traversal и работа с коллекциями]]
		- [[#1. Traversal]]
		-  [[#2. Функции для traversal]]
	- [[#Примеры использования]]
		-  [[#1. Игровая логика]]
		-  [[#2. Работа с контекстами]]
	- [[#Дополнительные возможности]]
		-  [[#1. Автоматическая генерация линз]]
		-  [[#2. Операторы]]
	- [[#Ticket 10 Итог]]
- #### [[#**Ticket 11 Brand new DSL world|Ticket 11: Brand new DSL world]]
	- [[#DSL и GSL]] 
	- [[#GADT (Generalized Algebraic Data Types)]]
		- [[#Проблема ADT]]
		- [[#Решение через GADT]]
	- [[#Экзистенциальные типы]]
		- [[#Проблема парсинга]]
		- [[#Решение через SomeAE]]
		- [[#Работа с Typeable]]
	- [[#forall и ранги типов]]
		- [[#Синтаксис forall]]
		- [[#Ранги типов]]
		- [[#Пример функции с forall]]
	- [[#Final Tagless]]
		- [[#Замена GADT на классы типов]]
		- [[#Реализации для разных целей]]
		- [[#Использование]]
	- [[#Ticket 11 Итог]]
- #### [[#Ticket 12 Some fun with kinds]]
	- [[#1. Определение кайндов]] 
	- [[#2. Использование кайндов]]
	- [[#3. Declassified Kind `Constraint`]]
	- [[#4. Типовые операторы (`-XTypeOperators`)]]
	- [[#5. Грамматика кайндов]]
	- [[#6. Пользовательские кайнды (`DataKinds`)]]
	- [[#7. Type-Level Symbols (`GHC.TypeLits`)]]
	- [[#8. Type Families (Типовые функции)]]
	- [[#9. Ограничения Type Families]]
	- [[#10. Практические примеры]]
	- [[#11. Замечания о Free Monads]]
	- [[#Ticket 11 Итог]]
- #### [[#Ticket 13 Comonads]]
	- [[#1. Концепция комонад]] 
		- [[#1.1 Основные понятия]]
		- [[#1.2 Операторы и правила]]
		- [[#1.3 Пример: Identity-комонада]]
	- [[#2. List Zipper]]
		- [[#2.1 Структура данных]]
		- [[#2.2 Основные операции]]
		- [[#2.3 Реализация комонады]]
		- [[#2.4 Пример: Игра "Жизнь"]]
	- [[#3. Алгебраические типы]]
		- [[#3.1 Кардинальность типов]]
		- [[#3.2 Дифференцирование типов]]
	- [[#4. Zipper и производные]]
		- [[#4.1 Связь с комонадами]]
		- [[#4.2 Примеры]]
	- [[#5. Три комонады апокалипсиса]]
		- [[#5.1 Env (Среда)]]
		- [[#5.2 Traced (Лог)]]
		- [[#5.3 Store (Хранилище)]]
	- [[#6. Другие комонады]]
		- [[#6.1 Stream (Бесконечный список)]]
		- [[#6.2 NonEmpty (Непустой список)]]
	- [[#7. Codo-нотация]]
		- [[#7.1 Синтаксис и преобразование]]
	- [[#Ticket 13 Итог]]



---
<div class="page-break" style="page-break-before: always;"></div>

# **Ticket 2: Basic Syntax**
### Ticket 2 Введение
**Особенности Haskell**:
- Статическая типизация.
- Иммутабельность (неизменяемость объектов).
- Чистота (чистые функции).
- Отсутствие `null`.
- Ленивые вычисления (вычисление только при необходимости).
- Поддержка бесконечных списков.

**Чистая функция**:
- Результат зависит только от аргументов.
- Гарантирует одинаковый вывод для одних и тех же входных данных.
- Типы (например, `IO`) указывают на нечистые функции.

---
<div class="page-break" style="page-break-before: always;"></div>

### Арифметика и типы
**Базовые операции**:
```haskell
1 + 2 + 3        -- 7
3 / 5 * (7 + 1)  -- 4.8
2 ^ 16           -- 65536
1 < 2 && 2 < 3   -- True
```

**Вызов функций**:
- Аргументы разделяются пробелами.
- Примеры: `div 7 3`, `max 3 5`, `min 6 (10 * 2)`.

**Префиксная/инфиксная запись**:
- Операторы в префиксной форме: `(+) 3 4`.
- Функции в инфиксной форме: ``7 `mod` 3``.

**Группировка аргументов**:
- Приоритет применения функций выше операторов.
- Примеры:
  ```haskell
  div 7 3 + 1  -- 3
  div 7 (3 + 1) -- 1
  ```

**Определение переменных**:
- Иммутабельность: `x = 7 + 8`.

**Строки**:
- Тип `String` (`[Char]`).
- Конкатенация через `++`: `"Hello" ++ " world!"`.

**Типы**:
- Команда `:t` в GHCi для проверки типов.
- Пример: `42 :: Num t => t` (полиморфизм).

---
<div class="page-break" style="page-break-before: always;"></div>

### Функции
**Синтаксис**:
- Сигнатура типа: `addMul :: Int -> Int -> Int -> Int`.
- Определение: `addMul x y z = x + y * z`.

**Примеры**:
- `greet name = "Hello, " ++ name ++ "!"`.
- Загрузка модуля: `:l Lecture.hs`.

---

### Операторы
**Создание операторов**:
- Указание ассоциативности (`infixl`, `infixr`, `infix`) и приоритета (0–9).
- Пример:
  ```haskell
  infixr 1 ==>
  (==>) :: Bool -> Bool -> Bool
  a ==> b = not a || b
  ```

**Ассоциативность**:
- `infixl`: левая, `infixr`: правая, `infix`: неассоциативен.

---
<div class="page-break" style="page-break-before: always;"></div>

### Тип List
**Создание списков**:
- Примеры: `[1, 2, 3]`, `5 : list`, `[0 .. 5]`.

**Иммутабельность**:
- Операции не изменяют исходный список.

**Базовые функции**:
- `head`, `tail`, `last`, `init` (небезопасны для пустых списков).
- `take`, `drop`, `reverse`, `zip`, `words`, `unwords`.

**Range-генерация**:
- `[0 .. 5]`, `[1, 3 .. 10]`, бесконечные списки: `[0, 2 ..]`.

---
<div class="page-break" style="page-break-before: always;"></div>

### Конструкции и выражения
**let-in**:
- Локальные определения:
  ```haskell
  pythagoras x y = let x2 = x^2; y2 = y^2 in x2 + y2
  ```

**where**:
- Определения после выражения:
  ```haskell
  pythagoras a b = a2 + b2 where square x = x^2; a2 = square a
  ```

**if-then-else**:
- Тернарный оператор:
  ```haskell
  factorial n = if n <= 1 then 1 else n * factorial (n - 1)
  ```

**Guards**:
- Условия через `|`:
  ```haskell
  collatzSum n
    | n == 1 = 1
    | even n = n + collatzSum (n `div` 2)
    | otherwise = n + collatzSum (3 * n + 1)
  ```

**case**:
- Сопоставление с образцом:
  ```haskell
  getFont n = case n of 0 -> "PLAIN"; 1 -> "BOLD"; _ -> "UNKNOWN"
  ```

---
<div class="page-break" style="page-break-before: always;"></div>

### Функции высшего порядка
**Пример**:
- Функция, принимающая другую функцию:
  ```haskell
  changeTwiceBy op val = op (op val)
  ```

**Анонимные функции**:
- Лямбда-синтаксис: `\x -> x + 1`.

---

### Полиморфизм
**Параметрический**:
- Пример: `id :: a -> a`.
- Функции: `map`, `filter`, `foldr1`, `zipWith`.

**Специальный (классы типов)**:
- Пример: `Num`, `Eq`.

---
<div class="page-break" style="page-break-before: always;"></div>

### Каррирование и частичное применение
- Частичное применение: `div7By = div 7`.
- Примеры с операторами: `map (+2) [1, 2, 3]`.

**Осторожно с `-`**:
- Используйте `subtract`: `map (subtract 5) [1..5]`.

---

### Функция flip
- Перестановка аргументов:
  ```haskell
  flip f x y = f y x
  ```

---

### Сопоставление с образцом
**Примеры**:
- `fact 0 = 1; fact n = n * fact (n - 1)`.
- Списки: `sumList3 [x, y, z] = x + y + z`.
- Alias через `@`: `dropWhile p l@(x:xs)`.

---
<div class="page-break" style="page-break-before: always;"></div>

### Расширения языка
**TupleSections**:
- `(42,)` вместо `\x -> (42, x)`.

**LambdaCase**:
- Сокращение для `case`:
  ```haskell
  veryLongFunctionName = \case 0 -> foo; 1 -> bar; n -> baz n
  ```

**ViewPatterns**:
- Использование функций в паттернах:
  ```haskell
  exactTwoWords (words -> [_, _]) = True
  ```

---

### Применение функций
**Оператор `$`**:
- Низкий приоритет: `length $ filter odd $ map (div 2) list`.

**Оператор `&`**:
- Обратное применение: `[1, 2] & \l -> l ++ reverse l`.

---
<div class="page-break" style="page-break-before: always;"></div>

### Оператор композиции `.`
- Композиция функций: `(f . g) x = f (g x)`.

---

### Генерация списков
**List comprehensions**:
- Примеры:
  ```haskell
  [x | x <- [1..10], even x]
  quickSort (x:xs) = quickSort [y | y <- xs, y <= x] ++ [x] ++ quickSort [y | y > x]
  ```

---

### Ленивое вычисление
**Порядок вычислений**:
- Выражения вычисляются только при необходимости.

**Формы выражений**:
- **Normal form (NF)**: Полностью вычисленное значение (например, `42`).
- **Weak head normal form (WHNF)**: Частично вычисленное (например, `(1 + 2, 3 + 4)`).
---
<div class="page-break" style="page-break-before: always;"></div>

# **Ticket 3: Datas, Classes, Instances**
### Ticket 3 Введение  
Цель: изучение создания пользовательских типов, алгебраических типов данных (ADT), записей (Record), классов типов (Type classes), полиморфизма и модулей.

---

### Custom Types (Пользовательские типы)
#### Зачем свои типы?
- **Проблемы с кортежами (Tuple):**  
  Отсутствие проверок на уровне типов. Пример:  
  ```haskell
  userFullId :: (Int, String, String) -> String
  userFullId (uid, login, _) = show uid ++ ":" ++ login
  ```
  Нет защиты от перепутывания полей.

- **Псевдонимы типов (Type Aliases):**  
  Не обеспечивают безопасность, только улучшают читаемость:  
  ```haskell
  type User = (Int, String, String)
  ```

### ADT (Алгебраические типы данных)
#### Теория
- **Product types** (произведение типов): `T1 × T2` (например, структуры).
- **Sum types** (сумма типов): `T1 + T2` (например, `Either`).
<div class="page-break" style="page-break-before: always;"></div>

#### Примеры ADT
1. **Перечисления (Enums):**  
   ```haskell
   data TrafficLight = Red | Yellow | Green | Blue
   ```

2. **Структуры:**  
   ```haskell
   data User = MkUser Int String String
   ```

3. **Параметрические типы:**  
   ```haskell
   data Point2D a = Point2D a a
   ```

4. **Суммы типов:**  
   ```haskell
   data IntResult = Success Int | Failure String
   ```

5. **Параметрические суммы:**  
   ```haskell
   data Vector a = Vector2D a a | Vector3D a a a
   ```

6. **Рекурсивные типы:**  
   ```haskell
   data List a = Nil | Cons a (List a)
   ```

#### Примеры стандартных типов
- **Maybe (аналог Optional):**  
  ```haskell
  data Maybe a = Nothing | Just a
  ```
- **Either:**  
  ```haskell
  data Either a b = Left a | Right b
  ```

---
<div class="page-break" style="page-break-before: always;"></div>

### Record Types (Типы-записи)
- **Определение:**  
  ```haskell
  data User = User 
    { uid :: Int
    , login :: String
    , password :: String 
    }
  ```
- **Особенности:**
  - Автогенерация функций доступа (например, `login :: User -> String`).
  - Обновление записей: `ivan { uid = 2 }`.
  - **RecordWildCards:** Шаблоны для упрощения сопоставления:  
    ```haskell
    toUnsafeString User{..} = login ++ ":" ++ password
    ```
  - **DuplicateRecordFields:** Расширение для полей с одинаковыми именами.
  - **newtype:** Оптимизированная обёртка для одного поля:  
    ```haskell
    newtype UserId = UserId Int
    ```

---
<div class="page-break" style="page-break-before: always;"></div>

### Type Classes (Классы типов)
#### Ad-hoc полиморфизм
- Пример класса `Printable`:  
  ```haskell
  class Printable p where
    printMe :: p -> String
  ```

#### Базовые классы
1. **Eq:** Проверка на равенство.  
   ```haskell
   class Eq a where
     (==), (/=) :: a -> a -> Bool
   ```

2. **Ord:** Сравнение.  
   ```haskell
   class Eq a => Ord a where
     compare :: a -> a -> Ordering
   ```

3. **Num:** Числовые операции.  
   ```haskell
   class Num a where
     (+), (-), (*) :: a -> a -> a
   ```

4. **Show:** Конвертация в строку.  
5. **Read:** Парсинг из строки (используйте `readMaybe` для безопасности).

#### Deriving
- Автоматическая генерация реализаций:  
  ```haskell
  data TrafficLight = Red | Yellow Green deriving (Eq, Show)
  ```
- **GeneralizedNewtypeDeriving:** Наследование для `newtype`:  
  ```haskell
  newtype Size = Size Int deriving (Num, Ord)
  ```

---
<div class="page-break" style="page-break-before: always;"></div>

### Модули
- **Экспорт:** Указание видимых компонентов.  
  ```haskell
  module Lib (User(..), foo) where
  ```
- **Импорт:**  
  ```haskell
  import Data.List (nub)
  import qualified Data.Map as Map
  ```

---
<div class="page-break" style="page-break-before: always;"></div>

### Дополнительные темы
1. **ADT как функции (Church Encoding):**  
   Пример:  
   ```haskell
   type Doctor_f who r = (who -> who -> r) -> (Int -> r) -> r
   ```

2. **Классы типов как словари:**  
   Реализация через передачу словаря функций:  
   ```haskell
   data EqC a = EqDict 
     { eq :: a -> a -> Bool
     , neq :: a -> a -> Bool }
   ```

---

### Ticket 3 Итог
- **ADT** позволяют создавать безопасные и выразительные структуры данных.
- **Record Types** упрощают работу с составными типами.
- **Type Classes** обеспечивают полиморфизм и переиспользование кода.
- **Модули** помогают организовать код и управлять видимостью.

Ссылки: [LearnYouAHaskell](https://learnyouahaskell.com/), [Haskell Wiki](https://wiki.haskell.org/).

---
<div class="page-break" style="page-break-before: always;"></div>

# **Ticket 4: Basic typeclasses: Monoid. Functor. Applicative**
### 1. Type-classes  
#### 1.1. Semigroup (Полугруппа)  
**Определение**:  
- Полугруппа — структура с ассоциативной бинарной операцией.  
- В Haskell: класс `Semigroup` с оператором `<>`.  

```haskell  
class Semigroup m where  
  (<>) :: m -> m -> m  
  -- Ассоциативность: (x <> y) <> z = x <> (y <> z)  
```  

**Дополнительные методы**:  
- `sconcat` — объединение непустого списка элементов:  
  ```haskell  
  sconcat :: NonEmpty m -> m  
  ```  
- `stimes` — повторение элемента `n` раз:  
  ```haskell  
  stimes :: Integral b => b -> m -> m  
  ```  

**Примеры**:  
- Список (`[a]`): операция `<>` — конкатенация (`++`).  
- Числовые типы через обёртки `newtype`:  
  ```haskell  
  newtype Sum a = Sum { getSum :: a }  
  instance Num a => Semigroup (Sum a) where  
    Sum x <> Sum y = Sum (x + y)  

  newtype Product a = Product { getProduct :: a }  
  instance Num a => Semigroup (Product a) where  
    Product x <> Product y = Product (x * y)  
  ```  
---
<div class="page-break" style="page-break-before: always;"></div>

#### 1.2. Monoid (Моноид)  
**Определение**:  
- Моноид — полугруппа с нейтральным элементом `mempty`.  

```haskell  
class Semigroup m => Monoid m where  
  mempty :: m  
  -- Законы:  
  -- x <> mempty = x  
  -- mempty <> x = x  
```  

**Дополнительные методы**:  
- `mappend` — синоним `<>` (по умолчанию `mappend = (<>)`).  
- `mconcat` — объединение списка с учётом пустого случая:  
  ```haskell  
  mconcat :: [m] -> m  
  mconcat [] = mempty  
  ```  

**Примеры**:  
- Список: `mempty = []`, `mappend = (++)`.  
- Пары моноидов:  
  ```haskell  
  instance (Monoid a, Monoid b) => Monoid (a, b) where  
    mempty = (mempty, mempty)  
    (a1, b1) <> (a2, b2) = (a1 <> a2, b1 <> b2)  
  ```  

---
<div class="page-break" style="page-break-before: always;"></div>

### 2. Свёртка (Fold)  
#### 2.1. `foldr` и `foldl`  
- **Правая свёртка** (`foldr`):  
  ```haskell  
  foldr :: (a -> b -> b) -> b -> [a] -> b  
  foldr f z [] = z  
  foldr f z (x:xs) = f x (foldr f z xs)  
  ```  

- **Левая свёртка** (`foldl`):  
  ```haskell  
  foldl :: (b -> a -> b) -> b -> [a] -> b  
  foldl f z [] = z  
  foldl f z (x:xs) = foldl f (f z x) xs  
  ```  

#### 2.2. Класс `Foldable`  
**Определение**:  
```haskell  
class Foldable t where  
  foldr :: (a -> b -> b) -> b -> t a -> b  
  foldMap :: Monoid m => (a -> m) -> t a -> m  
  fold :: Monoid m => t m -> m  
```  

**Примеры**:  
- Для списка (`[]`):  
  ```haskell  
  instance Foldable [] where  
    foldr f z [] = z  
    foldr f z (x:xs) = f x (foldr f z xs)  
  ```  

- Для `Maybe`:  
  ```haskell  
  instance Foldable Maybe where  
    foldr _ z Nothing = z  
    foldr f z (Just x) = f x z  
  ```  
---
<div class="page-break" style="page-break-before: always;"></div>

### 3. Functor  
**Определение**:  
- Позволяет применять функцию к значению в контексте.  

```haskell  
class Functor f where  
  fmap :: (a -> b) -> f a -> f b  
  -- Законы:  
  -- 1. fmap id = id  
  -- 2. fmap (f . g) = fmap f . fmap g  
```  

**Примеры**:  
- `Maybe`:  
  ```haskell  
  instance Functor Maybe where  
    fmap f (Just x) = Just (f x)  
    fmap _ Nothing = Nothing  
  ```  

- Список: `fmap = map`.  
- Функции:  
  ```haskell  
  instance Functor ((->) r) where  
    fmap = (.)  
  ```  

**Оператор**:  
```haskell  
(<$>) :: Functor f => (a -> b) -> f a -> f b  
(<$>) = fmap  
```  

---
<div class="page-break" style="page-break-before: always;"></div>

### 4. Applicative  
**Определение**:  
- Расширение `Functor` для работы с функциями в контексте.  

```haskell  
class Functor f => Applicative f where  
  pure :: a -> f a  
  (<*>) :: f (a -> b) -> f a -> f b  
  liftA2 :: (a -> b -> c) -> f a -> f b -> f c  
```  

**Примеры**:  
- `Maybe`:  
  ```haskell  
  instance Applicative Maybe where  
    pure = Just  
    Just f <*> Just x = Just (f x)  
    _ <*> _ = Nothing  
  ```  

- Список:  
  ```haskell  
  instance Applicative [] where  
    pure x = [x]  
    fs <*> xs = [f x | f <- fs, x <- xs]  
  ```  

**Законы**:  
1. Тождество: `pure id <*> v = v`.  
2. Композиция: `pure (.) <*> u <*> v <*> w = u <*> (v <*> w)`.  
3. Гомоморфизм: `pure f <*> pure x = pure (f x)`.  
4. Обмен: `u <*> pure y = pure ($ y) <*> u`.  

---
<div class="page-break" style="page-break-before: always;"></div>

### 5. Alternative  
**Определение**:  
- Моноид для `Applicative` с операцией "или-иначе".  

```haskell  
class Applicative f => Alternative f where  
  empty :: f a  
  (<|>) :: f a -> f a -> f a  
```  

**Примеры**:  
- `Maybe`:  
  ```haskell  
  instance Alternative Maybe where  
    empty = Nothing  
    Nothing <|> r = r  
    l <|> _ = l  
  ```  

- Список:  
  ```haskell  
  instance Alternative [] where  
    empty = []  
    (<|>) = (++)  
  ```  

---
<div class="page-break" style="page-break-before: always;"></div>

### 6. Traversable  
**Определение**:  
- Позволяет обходить структуру, сохраняя контекст.  

```haskell  
class (Functor t, Foldable t) => Traversable t where  
  traverse :: Applicative f => (a -> f b) -> t a -> f (t b)  
  sequenceA :: Applicative f => t (f a) -> f (t a)  
```  

**Примеры**:  
- `Maybe`:  
  ```haskell  
  instance Traversable Maybe where  
    traverse _ Nothing = pure Nothing  
    traverse f (Just x) = Just <$> f x  
  ```  

- Список:  
  ```haskell  
  instance Traversable [] where  
    traverse f = foldr (\x ys -> (:) <$> f x <*> ys) (pure [])  
  ```  

---
<div class="page-break" style="page-break-before: always;"></div>

### 7. Фантомные типы  
**Мотивация**: Добавить информацию о типе для безопасности.  

```haskell  
newtype Hash a = MkHash String  

class Hashable a where  
  hash :: a -> Hash a  

-- Пример использования:  
hashPair :: Int -> Hash (Int, Int)  
hashPair n = hash (n, n)  
```  

---
<div class="page-break" style="page-break-before: always;"></div>

### 8. Расширения  
#### 8.1. `ScopedTypeVariables`  
**Проблема**: Типы в `where` не видят полиморфные переменные.  

```haskell  
{-# LANGUAGE ScopedTypeVariables #-}  
prepend2 :: forall a. a -> [a] -> [a]  
prepend2 x xs = pair ++ xs  
  where  
    pair :: [a]  
    pair = [x, x]  
```  

#### 8.2. `TypeApplications`  
**Пример**: Явное указание типа.  

```haskell  
{-# LANGUAGE TypeApplications #-}  
read @Int "3" -- 3  
read @Double "3.0" -- 3.0  
```  

#### 8.3. `AllowAmbiguousTypes`  
**Проблема**: Тип-параметр не используется в методах класса.  

```haskell  
{-# LANGUAGE AllowAmbiguousTypes #-}  
class Size a where  
  size :: Int  

instance Size Int where size = 8  
instance Size Double where size = 16  

-- Использование:  
size @Double -- 16  
```  

--- 
<div class="page-break" style="page-break-before: always;"></div>

# **Ticket 5: Monads**
### Введение в монады
- **Монада** — контейнер для вычислений, позволяющий комбинировать зависимости между ними.
- **Отличия от Functor и Applicative**:
  - `Functor` (`<$>`): `(a → b) → t a → t b`
  - `Applicative` (`<*>`): `t (a → b) → t a → t b`
  - `Monad` (`>>=`): `t a → (a → t b) → t b` (вычисления зависят от предыдущих результатов).

**Класс Monad**:
```haskell
class Applicative m => Monad m where
  return :: a → m a        -- Аналог pure из Applicative
  (>>=)  :: m a → (a → m b) → m b  -- Оператор bind
```

---
<div class="page-break" style="page-break-before: always;"></div>

### Примеры монад

#### 1. Maybe Monad
- **Инстанс**:
  ```haskell
  instance Monad Maybe where
    return = Just
    Nothing >>= _ = Nothing
    Just a  >>= f = f a
  ```
- **Примеры**:
  ```haskell
  Just 5 >>= (\x → Just (x + 3))   -- Just 8
  Nothing >>= (\_ → Just 5)        -- Nothing
  ```

#### 2. Either Monad
- **Инстанс** (для `Either e`):
  ```haskell
  instance Monad (Either e) where
    return = Right
    Left e  >>= _ = Left e
    Right a >>= f = f a
  ```
- **Пример** (валидация):
  ```haskell
  mkUser :: String → Either ValidationError Username
  mkUser name = stripUsername name >>= validateLength 15 >>= return . Username
  ```

#### 3. List Monad
- **Инстанс**:
  ```haskell
  instance Monad [] where
    return x = [x]
    xs >>= f = concatMap f xs
  ```
- **Примеры**:
  ```haskell
  [1,2] >>= \x → [x, x+1]  -- [1,2,2,3]
  replicate 3 5             -- [5,5,5]
  ```

---
<div class="page-break" style="page-break-before: always;"></div>

### Композиция монад
- **Стрелка Клеисли**:
  ```haskell
  (<=<) :: Monad m => (b → m c) → (a → m b) → a → m c
  (>=>) :: Monad m => (a → m b) → (b → m c) → a → m c
  ```
- **Ассоциативность**: `(f >=> g) >=> h = f >=> (g >=> h)`.

---

### Операторы и функции
#### 1. Оператор `>>` (Zen)
- **Определение**:
  ```haskell
  (>>) :: Monad m => m a → m b → m b
  m >> k = m >>= \_ → k
  ```
- **Пример**:
  ```haskell
  [True, False] >> [1,2]  -- [1,2,1,2]
  ```

#### 2. Функция `join`
- **Определение**:
  ```haskell
  join :: Monad m => m (m a) → m a
  join = (>>= id)
  ```
- **Примеры**:
  ```haskell
  join (Just (Just 3))    -- Just 3
  join [[1,2], [3]]       -- [1,2,3]
  ```

---

### Монадические законы
1. **Левое тождество**: `return a >>= f ≡ f a`.
2. **Правое тождество**: `m >>= return ≡ m`.
3. **Ассоциативность**: `(m >>= f) >>= g ≡ m >>= (\x → f x >>= g)`.

---
<div class="page-break" style="page-break-before: always;"></div>

### Специализированные монады

#### 1. Writer Monad
- **Логирование вычислений**:
  ```haskell
  newtype Writer w a = Writer { runWriter :: (a, w) }
  ```
- **Инстанс** (для `Monoid w`):
  ```haskell
  instance Monoid w => Monad (Writer w) where
    return a = Writer (a, mempty)
    Writer (a, log1) >>= f = 
      let Writer (b, log2) = f a 
      in Writer (b, log1 <> log2)
  ```
- **Пример** (вычисление степени с логами):
  ```haskell
  binPow n a | even n = ... >>= \b → tell "Square..." >> return (b*b)
  ```

#### 2. Reader Monad
- **Работа с глобальным окружением**:
  ```haskell
  newtype Reader e a = Reader { runReader :: e → a }
  ```
- **Инстанс**:
  ```haskell
  instance Monad (Reader e) where
    return a = Reader (\_ → a)
    m >>= f = Reader (\e → runReader (f (runReader m e)) e)
  ```
- **Пример**:
  ```haskell
  inEnv :: Int → Reader Environment Bool
  inEnv i = asks (elem i . ids)
  ```

#### 3. State Monad
- **Управление состоянием**:
  ```haskell
  newtype State s a = State { runState :: s → (a, s) }
  ```
- **Инстанс**:
  ```haskell
  instance Monad (State s) where
    return a = State (\s → (a, s))
    m >>= f = State (\s → 
      let (a, s') = runState m s 
      in runState (f a) s')
  ```
- **Пример** (стек):
  ```haskell
  pop :: State Stack Int
  pop = state (\(x:xs) → (x, xs))
  ```

---
<div class="page-break" style="page-break-before: always;"></div>

### Дополнительные темы
#### Типизированные дыры
- Используются для выведения типов:
  ```haskell
  join :: Monad m => m (m a) → m a
  join m = m >>= _  -- GHC подскажет тип: _ = id
  ```

#### Cont Monad
- **Continuation Passing Style (CPS)**:
  ```haskell
  newtype Cont r a = Cont { runCont :: (a → r) → r }
  ```
- **Инстанс**:
  ```haskell
  instance Monad (Cont r) where
    return a = Cont (\k → k a)
    m >>= f = Cont (\k → runCont m (\a → runCont (f a) k))
  ```
- **Пример**:
  ```haskell
  squareCPS :: Int → Cont r Int
  squareCPS x = return (x * x)
  ```

---
<div class="page-break" style="page-break-before: always;"></div>

# **Ticket 6: RealWorld**
### 1. `getchar` и проблемы чистых функций
- **Проблема 1**: Ленивые вычисления могут привести к однократному вызову `getchar`.
- **Проблема 2**: Отсутствие гарантий порядка выполнения.
- **Решение**: 
  - Введение счетчика как параметра.
  - Возврат пары `(Char, Int)` для контроля состояния.
```haskell
getchar :: Int -> (Char, Int)
get2chars :: Int -> [Char]
```

### 2. `RealWorld` и модель `IO`
- **Тип `IO a`** моделирует взаимодействие с "внешним миром":
  ```haskell
  type IO a = RealWorld -> (a, RealWorld)
  ```
- Реализация в стандартной библиотеке:
  ```haskell
  newtype IO a = IO { unIO :: State# RealWorld -> (State# RealWorld, a) }
  ```
- **Инстанс монады `IO`**:
  - `>>=` обеспечивает последовательное выполнение.
  - `return` оборачивает значение без изменения состояния.
<div class="page-break" style="page-break-before: always;"></div>

### 3. `do`-нотация и порядок выполнения
- **Эквивалентность** `do` и оператора `>>`:
  ```haskell
  main = do
    action1
    action2
  -- Эквивалентно:
  main = action1 >> action2
  ```
- **Функция `sequence_`** для выполнения списка действий:
  ```haskell
  sequence_ :: [IO a] -> IO ()
  ```

### 4. Работа с вводом-выводом
- **Пример с `getLine`**:
  ```haskell
  main = do
    s <- getLine
    putStrLn s
  ```
- **Использование `return`** для упаковки значений в `IO`:
  ```haskell
  getReversedLine :: IO String
  getReversedLine = do
    s <- getLine
    return (reverse s)
  ```
<div class="page-break" style="page-break-before: always;"></div>

### 5. Ленивое IO и проблемы
- **Пример с перезаписью файла**:
  ```haskell
  main = do
    fileContent <- readFile "foo.txt"
    writeFile "foo.txt" ('a' : fileContent)  -- Ошибка: файл занят
  ```
- **Ленивое чтение** (`readFile`) может привести к конфликтам ресурсов.

### 6. FFI (Foreign Function Interface)
- **Интеграция с C**:
  - Пример C-функции:
    ```c
    int example(int a, int b) { return a + b; }
    ```
  - Вызов из Haskell:
    ```haskell
    foreign import ccall safe "example" example :: CInt -> CInt -> CInt
    ```

### 7. Изменяемые объекты
- **`IORef`** для изменяемых переменных:
  ```haskell
  main = do
    varA <- newIORef 0
    writeIORef varA 1
    a <- readIORef varA  -- a = 1
  ```
- **`IOArray`** для массивов:
  ```haskell
  arr <- newArray (1,10) 37 :: IO (IOArray Int Int)
  ```

### 8. Исключения
- **Бросок исключений** через `throwIO`:
  ```haskell
  throwIO :: Exception e => e -> IO a
  ```
- **Обработка** через `catch`:
  ```haskell
  safeReadAndDivide = readAndDivide `catch` \DivideByZero -> return (-1)
  ```
- **Пользовательские исключения**:
  ```haskell
  data MyException = DummyException deriving (Show, Typeable, Exception)
  ```
<div class="page-break" style="page-break-before: always;"></div>

### 9. Класс `Exception`
- **Методы**:
  - `fromException` / `toException` для приведения к `SomeException`.
  - `displayException` для строкового представления.
- **Пример обработки любого исключения**:
  ```haskell
  tryReadAndDivide = readAndDivide `catch` \(e :: SomeException) -> ...
  ```

### 10. Полезные функции для работы с исключениями
- **`try`** и **`tryJust`** для безопасного выполнения.
- **`finally`** и **`onException`** для гарантии действий.
- **`bracket`** для управления ресурсами (аналог RAII):
  ```haskell
  bracket (openFile) (closeFile) (\file -> useFile file)
  ```

### 11. Небезопасные операции (`unsafePerformIO`)
- **`unsafePerformIO`** обходит гарантии `IO`:
  ```haskell
  unsafePerformIO :: IO a -> a
  ```
- **Пример** (непредсказуемый порядок вывода):
  ```haskell
  let two = unsafePerformIO (helper 2)  -- Порядок выполнения не гарантирован
  ```

### 12. Работа со строками: `Text` и `ByteString`
- **Проблемы `String`**:
  - Медленная работа из-за списков `[Char]`.
  - Отсутствие поддержки Unicode.
- **`Data.Text`** и **`Data.ByteString`**:
  - Используют низкоуровневые оптимизации (через C указатели).
  - `unsafePerformIO` скрыт внутри реализации для чистого API.

---
<div class="page-break" style="page-break-before: always;"></div>

# **Ticket 7: Monad Transformers**
### Монады как эффект  
Монады представляют эффекты вычислений. Таблица соответствия:  

| Монада | Эффект                                |
| ------ | ------------------------------------- |
| Maybe  | Вычисление может завершиться неудачей |
| Either | Неудача с конкретной ошибкой          |
| []     | Множество возможных значений          |
| Writer | Моноидальный аккумулятор              |
| Reader | Доступ к неизменяемому контексту      |
| State  | Доступ к изменяемому состоянию        |
| IO     | Взаимодействие с внешним миром        |

**Проблема**: Комбинирование нескольких эффектов (например, `Reader` + `State`).  

#### Пример комбинирования эффектов  
1. **Прямой подход** с `ReaderT` и `State`:  
   ```haskell  
   foo :: Int -> ReaderT Int (State [Int]) Int  
   foo i = do  
     baseCounter <- ask  
     let newCounter = baseCounter + i  
     put [baseCounter, newCounter]  
     return newCounter  
   ```  
   - `ReaderT` добавляет доступ к контексту, `State` управляет изменяемым состоянием.  

2. **Проблема композиции монад**:  
   - Для `Functor`, `Applicative`, `Traversable` композиция возможна через `Compose f g`.  
   - Для монад композиция в общем случае невозможна из-за структуры `>>=`.  
<div class="page-break" style="page-break-before: always;"></div>

### Реализация монадных трансформеров  

#### Пример с `MaybeT`  
**Цель**: Совместить `Maybe` с другими монадами (например, `IO`).  
- Определение трансформера:  
  ```haskell  
  newtype MaybeT m a = MaybeT { runMaybeT :: m (Maybe a) }  
  ```  

- Instance монады:  
  ```haskell  
  instance Monad m => Monad (MaybeT m) where  
    return x = MaybeT (return (Just x))  
    MaybeT action >>= f = MaybeT $ do  
      result <- action  
      case result of  
        Nothing -> return Nothing  
        Just x  -> runMaybeT (f x)  
  ```  

- **Функция подъёма** (`lift`):  
  ```haskell  
  transformToMaybeT :: Functor m => m a -> MaybeT m a  
  transformToMaybeT = MaybeT . fmap Just  
  ```  
<div class="page-break" style="page-break-before: always;"></div>

#### Класс `MonadTrans`  
- Определение:  
  ```haskell  
  class MonadTrans t where  
    lift :: Monad m => m a -> t m a  
    -- Законы:  
    -- 1. lift . return ≡ return  
    -- 2. lift (m >>= f) ≡ lift m >>= (lift . f)  
  ```  

- Instance для `MaybeT`:  
  ```haskell  
  instance MonadTrans MaybeT where  
    lift = transformToMaybeT  
  ```  
<div class="page-break" style="page-break-before: always;"></div>

#### Пример с `ReaderT`  
- Определение:  
  ```haskell  
  newtype ReaderT r m a = ReaderT { runReaderT :: r -> m a }  
  ```  

- Instance монады:  
  ```haskell  
  instance Monad m => Monad (ReaderT r m) where  
    return = lift . return  
    m >>= f = ReaderT $ \r -> do  
      a <- runReaderT m r  
      runReaderT (f a) r  
  ```  

- Instance `MonadTrans`:  
  ```haskell  
  instance MonadTrans (ReaderT r) where  
    lift = ReaderT . const  
  ```  

#### `MonadIO` для работы с `IO`  
- Определение:  
  ```haskell  
  class Monad m => MonadIO m where  
    liftIO :: IO a -> m a  
  ```  

- Примеры instance'ов:  
  ```haskell  
  instance MonadIO IO where  
    liftIO = id  

  instance MonadIO m => MonadIO (StateT s m) where  
    liftIO = lift . liftIO  
  ```  
<div class="page-break" style="page-break-before: always;"></div>

### Пакет `mtl`  
Предоставляет готовые трансформеры и классы типов для упрощения работы.  

### Класс `MonadReader`  
- Определение:  
  ```haskell  
  class Monad m => MonadReader r m | m -> r where  
    ask    :: m r  
    local  :: (r -> r) -> m a -> m a  
    reader :: (r -> a) -> m a  
  ```  
  - `| m -> r`: Функциональная зависимость — тип `r` определяется монадой `m`.  

### Обработка исключений  

#### Классы `MonadThrow` и `MonadCatch`  
- `MonadThrow`:  
  ```haskell  
  class Monad m => MonadThrow m where  
    throwM :: Exception e => e -> m a  
  ```  

- `MonadCatch`:  
  ```haskell  
  class MonadThrow m => MonadCatch m where  
    catch :: Exception e => m a -> (e -> m a) -> m a  
  ```  

#### Класс `MonadError` (из `mtl`)  
- Определение:  
  ```haskell  
  class Monad m => MonadError e m | m -> e where  
    throwError :: e -> m a  
    catchError :: m a -> (e -> m a) -> m a  
  ```  
  - Позволяет комбинировать обработку ошибок с другими эффектами (например, через `ExceptT`).  

### Ticket 7 Итог  
- Монадные трансформеры позволяют комбинировать эффекты (например, `ReaderT`, `StateT`, `MaybeT`).  
- Классы типов (`MonadTrans`, `MonadIO`, `MonadReader`) упрощают подъём операций между слоями.  
- Пакет `mtl` предоставляет готовые решения для работы с трансформерами.  
- Обработка исключений реализуется через `MonadThrow`, `MonadCatch`, `MonadError`.  
---
<div class="page-break" style="page-break-before: always;"></div>

# **Ticket 8: Speeding up Haskell**

### DList
- **Проблема конкатенации списков**: из-за неизменяемости конкатенация (`++`) требует копирования, что медленно.  
- **Пример `trinity`**:  
  ```haskell
  trinity a b c = a ++ b ++ c         -- (1) и (2): правая ассоциативность (быстрее)  
  trinity a b c = (a ++ b) ++ c       -- (3): левая ассоциативность (медленнее, O(2n + m)).  
  ```  
- **Определение `DList`**:  
  ```haskell
  newtype DList a = DL { unDL :: [a] -> [a] }  
  ```  
  - `fromList`: `fromList l = DL (l++)`  
  - `toList`: `toList (DL lf) = lf []`  
  - `append`: `append (DL f) (DL g) = DL (\xs -> f (g xs))`  
- **Преимущество DList**: автоматическая оптимизация ассоциативности конкатенации, избегая лишних копирований.

---
<div class="page-break" style="page-break-before: always;"></div>

### Строгость в Haskell
- **`seq`**:  
  ```haskell
  seq :: a -> b -> b  
  ```  
  - Вычисляет первый аргумент до **WHNF** (Weak Head Normal Form).  
  - Примеры:  
    ```haskell
    undefined `seq` 10   -- Exception  
    Just undefined `seq` 10  -- 10 (конструктор в WHNF).  
    ```  
- **Разница `foldl` и `foldl'`**:  
  - `foldl` создает thunk-и, что приводит к space leaks.  
  - `foldl'` использует `seq` для строгого вычисления аккумулятора:  
    ```haskell
    foldl' f a (x:xs) = let a' = f a x in seq a' (foldl' f a' xs)  
    ```  
- **`deepseq` и `NFData`**:  
  - `deepseq` вычисляет объект до **нормальной формы** (NF).  
  - Класс `NFData`:  
    ```haskell
    class NFData a where  
      rnf :: a -> ()  
    ```  
  - Пример для списка:  
    ```haskell
    instance NFData a => NFData [a] where  
      rnf [] = ()  
      rnf (x:xs) = rnf x `seq` rnf xs  
    ```  

- **Расширение `BangPatterns`**:  
  - Синтаксис `!` для принудительного вычисления:  
    ```haskell
    sum :: Num a => [a] -> a  
    sum = go 0 where  
      go !acc (x:xs) = go (acc + x) xs  -- Строгий аккумулятор  
    ```  
  - Строгие функции: `$!` (seq) и `$!!` (deepseq).  

- **Ленивый Pattern Matching (`~`)**:  
  - Откладывает проверку паттерна:  
    ```haskell
    lazyHead ~(x:_) = x  -- Не вызывает ошибку на пустом списке.  
    ```  

- **Строгие поля и прагмы**:  
  - Строгие поля в `data`:  
    ```haskell
    data Config = Config { users :: !Int }  
    ```  
  - Прагмы:  
    - `StrictData`: все поля строгие.  
    - `Strict`: весь модуль строгий.  

---
<div class="page-break" style="page-break-before: always;"></div>

### Оптимизация прохода по списку
- **Deforestation**: устранение промежуточных списков.  
  - Пример оптимизации `map f . map g` в `map (f . g)`.  
  - Ручное преобразование `foldr` и `map`:  
    ```haskell
    func l = case l of  
      [] -> 0  
      (y:ys) -> y * 10 + func ys  
    ```  

- **Stream Fusion**:  
  - Типы для стримов:  
    ```haskell
    data Step s a = Done | Skip s | Yield a s  
    data Stream a = forall s. Stream (s -> Step s a) s  
    ```  
  - Функции:  
    - `stream :: [a] -> Stream a`  
    - `unstream :: Stream a -> [a]`  
    - `mapS`, `filterS` для работы со стримами.  
  - Правила переписывания (Rewrite Rules):  
    ```haskell
    {-# RULES "stream/unstream" forall s. stream (unstream s) = s #-}  
    ```  

---
<div class="page-break" style="page-break-before: always;"></div>

### Изменяемые объекты
- **Монада `ST`**:  
  - Аналог `IO`, но с гарантией безопасности:  
    ```haskell
    newtype ST s a = ST (State# s -> (# State# s, a #))  
    runST :: (forall s. ST s a) -> a  
    ```  
  - Пример использования `STRef`:  
    ```haskell
    sumST xs = runST $ do  
      n <- newSTRef 0  
      for_ xs $ \x -> modifySTRef n (+x)  
      readSTRef n  
    ```  

- **Массивы `MArray`**:  
  - Типы: `STArray` (boxed) и `STUArray` (unboxed).  
  - Методы: `newArray`, `readArray`, `writeArray`.  

- **Векторы `Vector` и `MVector`**:  
  - `Vector`: неизменяемый, эффективный доступ по индексу.  
  - `MVector`: изменяемый, работает с `PrimMonad` (включая `IO` и `ST`).  
  - Методы: `read`, `write`, `freeze`.  

--- 

**Итог**:  
- **DList** и **Stream Fusion** оптимизируют работу со списками.  
- **Строгость** (`seq`, `foldl'`, `BangPatterns`) предотвращает space leaks.  
- **ST монада** и **изменяемые массивы** позволяют эффективно работать с мутабельными структурами без потери чистоты кода.

---
<div class="page-break" style="page-break-before: always;"></div>

# **Ticket 9: Parallel and Concurrent Haskell**

---
<div class="page-break" style="page-break-before: always;"></div>

### Fork a thread
- `forkIO` создает легковесный поток.
- Пример:
  ```haskell
  main = do
    _tid <- forkIO $ do
      threadDelay 1000000
      putStrLn "Forked thread awake"
    threadDelay 2000000
    putStrLn "Main thread finishes"
  ```
- Компиляция с поддержкой многопоточности:
  ```bash
  ghc -threaded -o test Test.hs
  ./test +RTS -N2
  ```

---

### Where is my join?
- **MVar** — потокобезопасный контейнер (пустой/заполненный).
- Пример синхронизации:
  ```haskell
  main = do
    tm1 <- newEmptyMVar
    tm2 <- newEmptyMVar
    forkIO $ putMVar tm1 100500
    forkIO $ putMVar tm2 "Hello"
    r1 <- takeMVar tm1  -- Блокируется до заполнения
    r2 <- takeMVar tm2
  ```

---
<div class="page-break" style="page-break-before: always;"></div>

### More about MVar
- Блокировка на пустом MVar вызывает исключение `BlockedIndefinitelyOnMVar`.
- Пример:
  ```haskell
  main = do
    m <- newEmptyMVar
    takeMVar m  -- Исключение: BlockedIndefinitelyOnMVar
  ```

---

### What to do thread id?
- **Асинхронные исключения**: `throwTo` и `killThread`.
- Пример прерывания потока:
  ```haskell
  main = do
    tid <- forkIO myHeavyComputation
    threadDelay 1000000
    killThread tid
  ```

---
<div class="page-break" style="page-break-before: always;"></div>

### Exceptions classification
- **Синхронные**: `throwIO`, `throw` (например, деление на ноль).
- **Асинхронные**: `throwTo` (исключения между потоками).
- Пример обработки:
  ```haskell
  main = handle intrHandler $ mapM_ [1..1000] $ \i -> do
    threadDelay 1000000
    putStrLn $ "Round " ++ show i
  ```

---

### Handle exception
- Универсальные функции: `catch`, `handle`.
- Пример перехвата пользовательского исключения:
  ```haskell
  data MyException = MyException deriving Show
  instance Exception MyException

  main = throwIO MyException `catch` \MyException -> putStrLn "Caught!"
  ```

---
<div class="page-break" style="page-break-before: always;"></div>

### Masquerade
- **Проблема**: Асинхронные исключения в обработчиках.
- **Решение**: Использовать `mask_` для защиты критических секций.
  ```haskell
  main = action `catch` \e -> mask_ $ do
    printError e
    cleanup
  ```

---

### Bracket is your friend
- **bracket** гарантирует выполнение очистки ресурсов.
- Пример:
  ```haskell
  withFile :: FilePath -> IOMode -> (Handle -> IO a) -> IO a
  withFile path mode = bracket (openFile path mode) hClose
  ```

---
<div class="page-break" style="page-break-before: always;"></div>

### Never use forkIO
- **Проблема**: Исключения в дочерних потоках могут привести к deadlock.
- **Решение**: Использовать `concurrently` из библиотеки Async.
  ```haskell
  main = do
    (res1, res2) <- concurrently action1 action2
    putStrLn $ "Results: " ++ res1 ++ ", " ++ res2
  ```

---

### Async package - Basic primitives
- **concurrently**: Запуск двух действий параллельно.
- **race**: Возвращает результат первого завершившегося действия.
- **mapConcurrently**: Параллельное выполнение списка действий.
  ```haskell
  test3 = mapConcurrently worker [0..10000]
  ```

---
<div class="page-break" style="page-break-before: always;"></div>

### Concurrently newtype
- Композиция через `Applicative` и `Alternative`:
  ```haskell
  test1 = runConcurrently $ (,) <$> Concurrently action1 <*> Concurrently action2
  test2 = runConcurrently $ Left <$> Concurrently action1 <|> Right <$> Concurrently action2
  ```

---

### Async package - Advanced usage
- **withAsync**: Управление жизненным циклом асинхронных задач.
- Пример:
  ```haskell
  withAsync (getURL url1) $ \a1 -> withAsync (getURL url2) $ \a2 -> do
    page1 <- wait a1
    page2 <- wait a2
  ```

---
<div class="page-break" style="page-break-before: always;"></div>

### Transactions (1/3, 2/3, 3/3)
- **Проблема**: Гонки данных при использовании `IORef`/`MVar`.
- **Решение**: STM (Software Transactional Memory).
  ```haskell
  transfer :: Integer -> Account -> Account -> STM ()
  transfer amount from to = do
    debit amount from
    credit amount to
  ```

---

### STM
- **Атомарность**: `atomically` выполняет транзакцию целиком или откатывает.
- **TVar**: Транзакционные переменные.
- Пример:
  ```haskell
  atomically $ transfer 100 acc1 acc2
  ```

---
<div class="page-break" style="page-break-before: always;"></div>

### Преимущества неизменности
1. Легче отлаживать.
2. Нет гонок данных.
3. Не требуются блокировки.

---

### Parallel primitives
- **Eval-монада**: `rpar` (параллельное выполнение), `rseq` (последовательное).
- Пример:
  ```haskell
  runEval $ do
    a <- rpar (f x)
    b <- rpar (f y)
    return (a, b)
  ```

---

### Classic example: fib
- Параллельное вычисление Фибоначчи:
  ```haskell
  parFib n = runEval $ do
    a <- rpar (fib (n-1))
    b <- rpar (fib (n-2))
    return (a + b)
  ```
- Анализ через ThreadScope:
  ```bash
  ghc -O2 -threaded -rtsopts -eventlog TestFib.hs
  ./TestFib +RTS -N2 -s -l
  ```

---
<div class="page-break" style="page-break-before: always;"></div>

### threadscope
- Визуализация работы потоков:
  

---

### What about sparks?
- **Спарки** (sparks): 
  - Converted — полезные.
  - Overflowed/Dud/GC'd/Fizzled — потерянные.

---

### Innacurate parallelism
- **Проблема**: Избыточные спарки (например, рекурсивный `parFib`).
  ```haskell
  parFib n = runEval $ do
    a <- rpar (parFib (n-1))  -- Создает миллионы спарков
    b <- rpar (parFib (n-2))
    return (a + b)
  ```

---

### What else?
- **Дополнительные темы**: 
  - REPA (Parallel arrays).
  - Каналы (`Chan`, `TChan`).
  - Распределенное программирование (CloudHaskell).

---

### Дополнительно
#### Strategies
- **Параллельные стратегии**:
  ```haskell
  parPair = evalTuple2 rpar rpar
  evalFibPair `using` parPair
  ```

#### Par Monad
- **Пример**:
  ```haskell
  parMap :: NFData b => (a -> b) -> [a] -> Par [b]
  example2 = runPar $ parMap (+1) [1..25]
  ```

---
# **Ticket 10: Template Haskell and Lens**
### Введение в проблему доступа к полям структур
**Сравнение с JavaScript**:
   - В JavaScript объекты — это вложенные мапы, доступ к полям осуществляется через ключи.
   - В Haskell для работы с вложенными структурами (например, `Person` с полем `Address`) требуется ручное создание геттеров и сеттеров.
   - Пример структур:
     ```haskell
     data Person = Person { address :: Address }
     data Address = Address { street :: String, city :: String }
     ```
   - **Проблема**: Изменение вложенных полей требует много boilerplate-кода (например, обновление `city` через `address`).

---
<div class="page-break" style="page-break-before: always;"></div>

### Основы линз
##### 1. **Определение линзы**:
   - Линза — пара функций:
     - **Геттер**: Извлекает значение поля из структуры.
     - **Сеттер**: Создает новую структуру с обновленным значением поля.
   - Тип линзы: `Lens s a = (a -> f a) -> s -> f s` (упрощенно: пара функций `get` и `set`).

##### 2. **Пример реализации**:
   - Линза для поля `address` в `Person`:
     ```haskell
     addressLens :: Lens' Person Address
     addressLens = lens get set
       where
         get = address
         set person newAddress = person { address = newAddress }
     ```
   - Линза для вложенного поля `city`:
     ```haskell
     cityLens :: Lens' Address String
     cityLens = lens get set
       where
         get = city
         set addr newCity = addr { city = newCity }
     ```

##### 3. **Композиция линз**:
   - Комбинирование линз для доступа к вложенным полям:
     ```haskell
     personCityLens :: Lens' Person String
     personCityLens = addressLens . cityLens
     ```
   - Пример использования:
     ```haskell
     over personCityLens (++ "!") person  -- Изменяет city, добавляя "!"
     ```

---
<div class="page-break" style="page-break-before: always;"></div>

### Обобщенные линзы и функторы
##### 1. **Линзы как обобщенные функции**:
   - Линзы используют функторы для работы в различных контекстах (например, `Identity` для `over`, `Const` для `view`).
   - Тип линзы через функторы:
     ```haskell
     type Lens s a = forall f. Functor f => (a -> f a) -> s -> f s
     ```
   - **View** (получение значения):
     ```haskell
     view :: Lens' s a -> s -> a
     view lens = getConst . lens Const
     ```
   - **Over** (изменение значения):
     ```haskell
     over :: Lens' s a -> (a -> a) -> s -> s
     over lens f = runIdentity . lens (Identity . f)
     ```

##### 2. **Законы линз**:
   - **Get-Put**: `set l (get l s) s = s`.
   - **Put-Get**: `get l (set l v s) = v`.
   - **Put-Put**: `set l v' (set l v s) = set l v' s`.

---
<div class="page-break" style="page-break-before: always;"></div>

### Traversal и работа с коллекциями
##### 1. **Traversal**:
   - Линзы для работы с несколькими (или нулевыми) значениями (например, элементы списка).
   - Тип traversal: `Traversal' s a = forall f. Applicative f => (a -> f a) -> s -> f s`.
   - Пример: изменение всех элементов списка:
     ```haskell
     over (traversed . _1) (+1) [(1, "a"), (2, "b")]  -- Увеличивает первые элементы кортежей
     ```
##### 2. **Функции для traversal**:
   - `toListOf` (получение списка значений):
     ```haskell
     toListOf (traversed . _1) [(1, "a"), (2, "b")]  -- [1, 2]
     ```
   - `filtered` (фильтрация элементов):
     ```haskell
     over (traversed . filtered (>1)) (+1) [1,2,3]  -- [1,3,4]
     ```
---
<div class="page-break" style="page-break-before: always;"></div>

### Примеры использования
##### 1. **Игровая логика**:
   - Структура данных:
     ```haskell
     data Game = Game { score :: Int, units :: [Unit], boss :: Unit }
     data Unit = Unit { health :: Int, position :: (Double, Double) }
     ```
   - Линзы:
     ```haskell
     bossLens :: Lens' Game Unit
     healthLens :: Lens' Unit Int
     positionLens :: Lens' Unit (Double, Double)
     ```
   - **Атака босса**:
     ```haskell
     attackBoss :: State Game ()
     attackBoss = bossLens.healthLens %= subtract 10
     ```
   - **Движение юнитов**:
     ```haskell
     moveUnits :: State Game ()
     moveUnits = unitsLens.traversed.positionLens._1 += 10.0
     ```
##### 2. **Работа с контекстами**:
    - Использование `zoom` для фокусировки на подструктуре:
      ```haskell
      zoom bossLens $ healthLens += 100  -- Увеличение здоровья босса
      ```
    - Пример с `IO`:
      ```haskell
      breatheFire :: IO ()
      breatheFire = do
        putStrLn "Breathing fire!"
        modify $ unitsLens.traversed.healthLens -~ 3
      ```

---
<div class="page-break" style="page-break-before: always;"></div>

### Дополнительные возможности
##### 1. **Автоматическая генерация линз**:
	- Использование Template Haskell для генерации линз:
      ```haskell
      makeLenses ''Person  -- Генерирует линзы для всех полей
      ```
    - Пример: `address` и `city` генерируются автоматически.

##### 2. **Операторы**:
    - `^.` (view): `person ^. addressLens`.
    - `.~` (set): `person & cityLens .~ "New York"`.
    - `%~` (over): `person & healthLens %~ (+10)`.

---

### Ticket 10 Итог
- Линзы упрощают работу с вложенными структурами, уменьшая boilerplate-код.
- Поддержка композиции, функторов и аппликативов делает их мощным инструментом.
- Примеры: управление состоянием игры, фильтрация и трансформация коллекций.

**Примечание**: Лекция завершается обсуждением домашних заданий и важности понимания линз для экзамена.

---
<div class="page-break" style="page-break-before: always;"></div>

# **Ticket 11: Brand new DSL world**
### DSL и GSL
- **DSL** (Domain-Specific Language) — язык, предназначенный для решения задач в конкретной предметной области (пример: Verilog).
- **GSL** (General-Purpose Language) — универсальные языки (Python, Java, C++), решающие широкий спектр задач.

---

### GADT (Generalized Algebraic Data Types)
#### Проблема ADT
Пример определения арифметических выражений с ADT:
```haskell
data ArithExpr = 
    AENum Int 
  | AEPlus ArithExpr ArithExpr 
  | AEAnd ArithExpr ArithExpr 
  | AEGt ArithExpr ArithExpr
```
- **Проблема**: Конструкторы не контролируют типы операндов (например, `12 && 23` пройдёт проверку типов).

#### Решение через GADT
Использование типового параметра для контроля типов на этапе компиляции:
```haskell
data ArithExpr a where
  AENum  :: Int -> ArithExpr Int
  AEPlus :: ArithExpr Int -> ArithExpr Int -> ArithExpr Int
  AEAnd  :: ArithExpr Bool -> ArithExpr Bool -> ArithExpr Bool
  AEGt   :: ArithExpr Int -> ArithExpr Int -> ArithExpr Bool
```
- **Преимущества**: Некорректные выражения (например, `AENum 12 AEAnd AENum 23`) не скомпилируются.

---
<div class="page-break" style="page-break-before: always;"></div>

### Экзистенциальные типы
#### Проблема парсинга
Функция `parse :: String -> Maybe (ArithExpr a)` не работает, так как требует полиморфного типа `a`.

#### Решение через `SomeAE`
```haskell
data SomeAE where
  SomeAE :: Show a => ArithExpr a -> SomeAE

-- Альтернативный синтаксис с прагмой:
{-# LANGUAGE ExistentialQuantification #-}
data SomeAE = forall a. Show a => SomeAE (ArithExpr a)
```
- **Ограничение**: Доступ только к методам класса `Show`.

#### Работа с `Typeable`
Использование `eqT` для проверки типов в runtime:
```haskell
parseInt :: String -> Maybe (ArithExpr Int)
parseInt s = parse s >>= 
  \(SomeAE (expr :: ArithExpr t)) -> do
    Refl <- eqT @t @Int
    pure expr
```

---
<div class="page-break" style="page-break-before: always;"></div>

### `forall` и ранги типов
#### Синтаксис `forall`
- **Пример**: 
  ```haskell
  length :: forall a. [a] -> Int
  ```
- **Прагма**: `{-# LANGUAGE RankNTypes #-}` для функций с высокими рангами.

#### Ранги типов
- **Ранг 0**: Нет полиморфизма (например, `Int -> Int`).
- **Ранг 1**: Один `forall` на верхнем уровне (например, `forall a. a -> a`).
- **Ранг 2**: `forall` в контравариантной позиции (например, `(forall a. a -> a) -> Int`).

#### Пример функции с `forall`
```haskell
applyToTuple :: (forall a. [a] -> Int) -> ([b], [c]) -> (Int, Int)
applyToTuple f (x, y) = (f x, f y)
```
- Использование: `applyToTuple length ("hello", [1,2,3])` вернёт `(5, 3)`.

---
<div class="page-break" style="page-break-before: always;"></div>

### Final Tagless
#### Замена GADT на классы типов
Определение класса:
```haskell
class ArithExpr expr where
  aeNum  :: Int -> expr Int
  aePlus :: expr Int -> expr Int -> expr Int
  aeAnd  :: expr Bool -> expr Bool -> expr Bool
  aeGt   :: expr Int -> expr Int -> expr Bool
```
Пример выражения:
```haskell
myExpr :: ArithExpr expr => expr Bool
myExpr = ((aeNum 23 `aePlus` aeNum 12) `aeGt` aeNum 170) `aeAnd` (aeNum 35 `aeGt` aeNum 47)
```

#### Реализации для разных целей
1. **Преобразование в строку (`ToS`)**:
   ```haskell
   newtype ToS a = ToS { toString :: String }
   instance ArithExpr ToS where
     aeNum = ToS . show
     aePlus a b = a <> ToS " + " <> b
     aeAnd a b = a <> ToS " && " <> b
     aeGt a b = castTS a <> ToS " > " <> castTS b
   ```
   - `castTS` позволяет менять тип `ToS`.

2. **Вычисление значений (`Interpret`)**:
   ```haskell
   newtype Interpret a = Interpret { interpret :: a }
   instance ArithExpr Interpret where
     aeNum = Interpret
     aePlus a b = Interpret $ interpret a + interpret b
     aeAnd a b = Interpret $ interpret a && interpret b
     aeGt a b = Interpret $ interpret a > interpret b
   ```

#### Использование
- `toString myExpr` → `"23 + 12 > 170 && 35 > 47"`.
- `interpret myExpr` → `False`.

---
<div class="page-break" style="page-break-before: always;"></div>

### Ticket 11 Итог
- **GADT** обеспечивает безопасность типов для DSL.
- **Экзистенциальные типы** и `Typeable` решают проблемы парсинга полиморфных выражений.
- **`forall`** и **ранги типов** расширяют возможности полиморфизма.
- **Final Tagless** предлагает гибкий подход через классы типов, разделяя структуру данных и интерпретацию.

---
<div class="page-break" style="page-break-before: always;"></div>

# **Ticket 12: Some fun with kinds**
### 1. Определение кайндов
- **Кайнд** — это "тип типа", определяющий, как тип может быть параметризован.
- Примеры базовых типов:
  ```haskell
  ghci> :kind Int   -- Int :: *
  ghci> :kind Char  -- Char :: *
  ```
- Параметризованные типы:
  ```haskell
  ghci> :kind Maybe    -- Maybe :: * -> *
  ghci> :kind Maybe String  -- Maybe String :: *
  ```
- Тип функции `(->)`:
  ```haskell
  ghci> :kind (->)  -- (->) :: * -> * -> *
  ```

---
<div class="page-break" style="page-break-before: always;"></div>

### 2. Использование кайндов
- **Указание кайндов для пользовательских типов**:
  ```haskell
  newtype ReaderT r (m :: * -> *) (a :: *) = ReaderT { runReaderT :: r -> m a }
  -- Кайнд ReaderT: * -> (* -> *) -> * -> *
  ```

---

### 3. Declassified Kind: `Constraint`
- Классы имеют кайнд, заканчивающийся на `Constraint`:
  ```haskell
  ghci> :k Num  -- Num :: * -> Constraint
  ```
- **Алиасы для `Constraint`**:
  ```haskell
  type MyConstraints a = (Read a, Num a, Show a)
  foo :: MyConstraints a => String -> a -> a
  ```
- **`Constraint` не только в конце**:
  ```haskell
  type ConstraintEndomorphism p a = p a => a -> a
  -- Кайнд: (* -> Constraint) -> * -> *
  ```

---
<div class="page-break" style="page-break-before: always;"></div>

### 4. Типовые операторы (`-XTypeOperators`)
- Определение типов через операторы:
  ```haskell
  data a * b = Mult a b  -- Кайнд: * -> * -> *
  ```
- Конструкторы в операторном стиле:
  ```haskell
  let x = Mult @Int 3 True  -- Тип: Int * Bool
  ```

---

### 5. Грамматика кайндов
- Базовые кайнды: `*`, `Constraint`.
- Комбинации: 
  - Если `a` и `b` — кайнды, то `a -> b` тоже кайнд.
  - Типы данных имеют кайнд `*` или `k -> *`.
  - Классы — `Constraint` или `k -> Constraint`.

---
<div class="page-break" style="page-break-before: always;"></div>

### 6. Пользовательские кайнды (`DataKinds`)
- Промоутинг типов в кайнды:
  ```haskell
  data Nat = Z | S Nat  -- После DataKinds: Nat становится кайндом.
  data Vec :: * -> Nat -> * where
    Nil :: Vec a Z
    Cons :: a -> Vec a n -> Vec a (S n)
  ```
- Пример использования:
  ```haskell
  v :: Vec Int (S (S Z))  -- Вектор с двумя элементами.
  ```

---

### 7. Type-Level Symbols (`GHC.TypeLits`)
- Использование числовых литералов на уровне типов:
  ```haskell
  data Vec :: * -> Nat -> * where
    Nil :: Vec a 0
    (:>) :: a -> Vec a n -> Vec a (n + 1)
  ```
- Кайнд `Nat` автоматически поддерживает арифметику.

---
<div class="page-break" style="page-break-before: always;"></div>

### 8. Type Families (Типовые функции)
- **Закрытые семьи**:
  ```haskell
  type family FromMaybe (m :: Maybe k) (def :: k) :: k where
    FromMaybe ('Just t) _ = t
    FromMaybe 'Nothing def = def
  ```
- **Открытые семьи**:
  ```haskell
  type family Foo bar :: *
  type instance Foo Char = Double
  ```
- **Ассоциированные типы в классах**:
  ```haskell
  class Foo p where
    type AType p :: *
    data BType p :: *
  ```

---

### 9. Ограничения Type Families
- Проблема неинъективности решается через `TypeFamilyDependencies`:
  ```haskell
  type family Foo a = r | r -> a where
    Foo Char = Double
    Foo Int = Int
  ```

---
<div class="page-break" style="page-break-before: always;"></div>

### 10. Практические примеры
- **Гетерогенные списки**:
  ```haskell
  data HList :: [*] -> * where
    HNil :: HList '[]
    (:^) :: a -> HList t -> HList (a ': t)
  ```
- **Free Monads**:
  ```haskell
  data Free f a = Pure a | Free (f (Free f a))
  instance Functor f => Monad (Free f) where
    Pure a >>= f = f a
    Free m >>= f = Free (fmap (>>= f) m)
  ```

---

### 11. Замечания о Free Monads
- **Преимущества**: Позволяют абстрагировать мультиступенчатые вычисления.
- **Недостатки**: 
  - Низкая производительность (O(d) для `>>=`, где d — глубина вычислений).
  - Не подходит для сложных сценариев (например, конкурентных операций).

---

### Ticket 11 Итог
- **Кайнды** позволяют контролировать структуру типов на уровне компиляции.
- **Расширения** (`DataKinds`, `TypeOperators`, `TypeFamilies`) расширяют возможности работы с кайндами.
- **Примеры** (векторы, гетерогенные списки, Free Monads) демонстрируют практическое применение кайндов для создания типобезопасных структур.

---
<div class="page-break" style="page-break-before: always;"></div>

# **Ticket 13: Comonads**
### 1. Концепция комонад
#### 1.1 Основные понятия
- **Комонады** — дуальны монадам
- **Сигнатуры базовых функций**:
  ```haskell
  extract   :: w a -> a          -- Аналог return для монад
  duplicate :: w a -> w (w a)    -- Аналог join для монад
  extend    :: (w a -> b) -> w a -> w b
  ```

#### 1.2 Операторы и правила
- **Оператор `=>>`**:
  ```haskell
  (=>>) :: Comonad w => w a -> (w a -> b) -> w b
  x =>> f = extend f x
  ```
- **Композиция Коклейсли**:
  ```haskell
  (=<=) :: Comonad w => (w b -> c) -> (w a -> b) -> (w a -> c)
  g =<= f = g . extend f
  ```
- **Правила**:
  1. Ассоциативность: `(h =<= g) =<= f ≡ h =<= (g =<= f)`
  2. Тождество: `extract =<= f ≡ f` и `f =<= extract ≡ f`

#### 1.3 Пример: Identity-комонада
```haskell
instance Comonad Identity where
  extract = runIdentity
  duplicate = Identity
```

---
<div class="page-break" style="page-break-before: always;"></div>

### 2. List Zipper
#### 2.1 Структура данных
```haskell
data ListZipper a = LZ [a] a [a]  -- Левый список, фокус, правый список
```

#### 2.2 Основные операции
- **Движение**:
  ```haskell
  lLeft (LZ (l:ls) c rs) = LZ ls l (c:rs)
  lRight (LZ ls c (r:rs)) = LZ (c:ls) r rs
  ```
- **Запись**:
  ```haskell
  lWrite x (LZ ls _ rs) = LZ ls x rs
  ```

#### 2.3 Реализация комонады
```haskell
instance Functor ListZipper where
  fmap f (LZ ls x rs) = LZ (map f ls) (f x) (map f rs)

instance Comonad ListZipper where
  extract (LZ _ x _) = x
  duplicate = lGenerator lLeft lRight
```

#### 2.4 Пример: Игра "Жизнь"
- **Правило эволюции**:
  ```haskell
  rule :: Grid Bool -> Bool
  rule g = case aliveNeighbors g of
    2 -> extract g
    3 -> True
    _ -> False
  ```
- **Применение правил**:
  ```haskell
  evolve :: Grid Bool -> Grid Bool
  evolve = extend rule
  ```

---
<div class="page-break" style="page-break-before: always;"></div>

### 3. Алгебраические типы
#### 3.1 Кардинальность типов
- Примеры:
  - `Void` ≡ 0
  - `Unit` ≡ 1
  - `Bool` ≡ 2 (`1 + 1`)
  - `Either a b` ≡ `a + b`
  - `Pair a` ≡ `a * a`

#### 3.2 Дифференцирование типов
- **Алгоритм**:
  1. Вставка типизированных дыр
  2. Удаление дыр
  3. Создание нового типа

**Пример для `Pair a`**:
- Исходный тип: `a * a`
- Производная: `2a` (тип `Either a a`)

---
<div class="page-break" style="page-break-before: always;"></div>

### 4. Zipper и производные
#### 4.1 Связь с комонадами
- **Зиппер** = Производная типа × Фокусный элемент:  
  `Z_T(a) = a × T'(a)`

#### 4.2 Примеры
- **ListZipper**:  
  `Z_L(a) = L(a) × a × L(a)`
- **TreeZipper**:
  ```haskell
  data TreeZipper a = TZ (Tree a) a (Tree a) [Up a]
  data Up a = LeftBranch (Tree a) | RightBranch a (Tree a)
  ```

---
<div class="page-break" style="page-break-before: always;"></div>

### 5. Три комонады апокалипсиса
#### 5.1 Env (Среда)
```haskell
data Env e a = Env e a

instance Comonad (Env e) where
  extract (Env _ a) = a
  extend f (Env e _) = Env e (f (Env e a))
```

#### 5.2 Traced (Лог)
```haskell
newtype Traced m a = Traced { runTraced :: m -> a }

instance Monoid m => Comonad (Traced m) where
  extract (Traced f) = f mempty
  extend f (Traced g) = Traced (\m -> f (Traced (\m' -> g (m <> m'))))
```

#### 5.3 Store (Хранилище)
```haskell
data Store s a = Store (s -> a) s

instance Comonad (Store s) where
  extract (Store f s) = f s
  extend f (Store g s) = Store (f . Store g) s
```

---
<div class="page-break" style="page-break-before: always;"></div>

### 6. Другие комонады
#### 6.1 Stream (Бесконечный список)
```haskell
data Stream a = Cons a (Stream a)

instance Comonad Stream where
  extract (Cons x _) = x
  extend f s@(Cons _ xs) = Cons (f s) (extend f xs)
```

#### 6.2 NonEmpty (Непустой список)
```haskell
data NonEmpty a = a :| [a]

instance Comonad NonEmpty where
  extract (x :| _) = x
  extend f w@(_ :| xs) = f w :| case xs of
    [] -> []
    (y:ys) -> toList (extend f (y :| ys))
```

---
<div class="page-break" style="page-break-before: always;"></div>

### 7. Codo-нотация
#### 7.1 Синтаксис и преобразование
**Исходный код**:
```haskell
method
  wa> expr1
  wb> expr2
  wc> expr3
```

**Преобразование**:
```haskell
\wa -> 
  let wb = extend (\this -> expr1) wa
      wc = extend (\this -> expr2) wb
  in extract (extend (\this -> expr3) wc)
```

---

### Ticket 13 Итог
- Комонады предоставляют структуры для работы с контекстно-зависимыми вычислениями.
- ListZipper, Grid и другие структуры демонстрируют применение комонад.
- Алгебраические типы и их производные связаны с концепцией зипперов.
- Env, Traced, Store — основные комонады для работы с состоянием, средой и логами.
- Codo-нотация упрощает работу с комонадами через синтаксический сахар.