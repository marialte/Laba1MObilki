
---

**Выполнил студент Мария Чашкина ИСП-213о**

---

Лабораторная работа №1: Создание Activity и передача параметров между ними

**Цель работы:**  
Знакомство с интерфейсом среды программирования Android Studio и изучение структуры проекта. Освоение создания активностей и передачи данных между ними с использованием `Intent`.

**Условия лабораторной работы:**

1. Создайте новый проект в Android Studio.
2. Реализуйте две активности. В первой активности должна быть кнопка (`Button`), при нажатии на которую пользователь будет перенаправлен во вторую активность.
3. Вторая активность должна содержать текстовое поле (`TextView`), которое будет отображать переданный параметр — фамилию студента.
4. При нажатии на кнопку в первой активности, используя `Intent`, необходимо передать параметр и открыть вторую активность.

**Ключевые классы:**  
`Activity`, `Intent`, `Button`, `TextView`.

**Описание лабораторной работы:**  
Этот проект демонстрирует основы работы с несколькими активностями в Android приложении. Было создано две активности: первая активность содержит кнопку, при нажатии на которую осуществляется переход ко второй активности. Вторая активность принимает переданный параметр и отображает его в текстовом поле.

**Используемые технологии:**  
- Kotlin
- Android Jetpack Compose

**Структура проекта:**
- **MainActivity:** Первая активность с кнопкой для перехода ко второй активности.
- **SecondActivity:** Вторая активность, которая отображает текст с переданным параметром.

---

### Установка

1. Склонируйте репозиторий.
2. Откройте проект в Android Studio.
3. Запустите приложение на эмуляторе или устройстве.
