# week14

### Вопросы 💎

1. Что называется массивом?

Совокупность переменных под одним именем.

Упорядоченная коллекция данных, в которой присутствуют 1-й, 2-й, 3-й элементы и т.д. В массиве элементы перечисляются через запятую, все они заключены в общие квадратные скобки.

2. С какого порядкового номера начинаются массивы?

С нуля.

3. Сколько значений может иметь массив?

Сколько угодно.

4. Как можно получить значение текстового поля из данной формы? (Форма одна)

text=document.fld.field.value
text=document.forms[0].field.value

```jsx
<form action="start.php" method="post" name="fld">
	<input type="text" name="field" value="Text field">
	<input type="submit" value="Старт" name="btn">
</form>

```

5. Какой результат работы данного скрипта?

   ```jsx
   let mas = new Array(2); // создает массив длиной 2 элемента, но пустой, без значений
   mas[3] = 5; // добавляет третий пустой и четвертый со значением 5 элементы
   console.log(mas[3]); // выводит в косоль число 5
   ```

6. Какой результат работы данного скрипта?

   ```jsx
   let mas = new Array(2); // создает массив длиной 2 элемента, но пустой, без значений
   mas[3] = 5; // добавляет третий пустой и четвертый со значением 5 элементы
   console.log(mas3); // ошибка, т.к. переменной mas3 не существует
   ```

7. Что делает строка let mas = new Array()?

Объявляет переменную mas как массив

8. Может ли массив состоять из элементов разных типов?

Да.

9. Укажите длину массива после исполнения следующего кода:

2 также, мы просто присвоили второй элемент, который теперь null, а не пустой.

```jsx
let a = new Array(2);
a[1] = null;
```

10. Что выведет консоль?

Ошибку, потому что разные открывающие и закрывающие кавычки используются в значениях

    ```jsx
    const students = [“Lena", “Olya", "Ylia", "Roma" ,  "Vova" ];
    console.log(students[3]);
    ```

11. Что выведет третья строка?

"Яблоко", "Лимон", "Ананас"

    ```jsx
    const fruits = ["Груша", "Яблоко", "Лимон", "Ананас"];
    console.log(fruits.shift());
    console.log(fruits);
    ```
