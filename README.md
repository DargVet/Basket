# Лабораторная работа: Система управления товарами в корзине

Проект представляет собой систему управления товарами в корзине с графическим интерфейсом (WForms) и консольным интерфейсом (Console).

## Структура проекта
Laba.sln
├── Console/ # Консольное приложение
│ ├── AddProduct.cs # Добавление товаров
│ ├── CalculateTotalClass.cs # Расчет общей стоимости
│ ├── GetProduct.cs # Поиск товаров
│ ├── RemoveProduct.cs # Удаление товаров
│ ├── ShowAllProductsClass.cs # Показать все товары
│ ├── ShowProductsByCategoryClass.cs # Товары по категориям
│ ├── UpdateProduct.cs # Обновление товаров
│ ├── Program.cs # Главная программа
│
├── ModelLogic/ # Бизнес-логика и модели данных
│ ├── LogicClass.cs # Основная логика приложения
│ ├── ProductClass.cs # Модель товара
│
└── WForms/ # Windows Forms приложение
├── Add.cs # Форма добавления товара
├── Del.cs # Форма удаления товара
├── Find.cs # Форма поиска товара
├── MainForm.cs # Главная форма
├── Update.cs # Форма обновления товара
├── AllCategories.cs # Форма категорий
├── ProductDisplayer.cs # Отображение товаров
├── Program.cs # Запуск приложения


## Методы класса Logic
**AddInBasket()** - Добавляет товар  
**RemoveProduct()** - Удаляет товар  
**GetProduct()** - Ищет товар  
**UpdateProduct()** - Обновляет товар  
**GetTotalPrice()** - Считает сумму  
**GetProductsByCategory()** - Ищет товары по категории  
**GetAllProducts()** - Возвращает все товары

## Функциональность
### Консольное приложение (Console)
1. Добавить товар(Создание сущности через Logic.AddInBasket)
2. Удалить товар(удаление сущности черех Logic.RemoveProduct)
3. Найти товар по имени(чтение сущности черех Logic.GetProduct)
4. Обновить товар(Изменение сущности черех Logic.UpdateProduct)
5. Посчитать общую сумму(Подсчет общей суммы вещей в корзине черех Logic.GetTotalPrice)
6. Показать товары по категории(Выводит все товары в категории через Logic.GetAllProducts)
7. Показать все товары(Выводит все товары через Logic.GetProductsByCategory)
0. Выход(Выход из консольного приложения)

### Windows Forms
1. Добавить товар(Создание сущности через Logic.AddInBasket)
2. Удалить товар(удаление сущности черех Logic.RemoveProduct)
3. Найти товар по имени(чтение сущности черех Logic.GetProduct)
4. Обновить товар(Изменение сущности черех Logic.UpdateProduct)
5. Посчитать общую сумму(Подсчет общей суммы вещей в корзине черех Logic.GetTotalPrice)
6. Показать товары по категории(Выводит все товары в категории Logic.GetProductsByCategory)
