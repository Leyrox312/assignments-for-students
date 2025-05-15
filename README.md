# assignments-for-students
1. Четные буквы в верхний регистр (императивный подход)
Напиши функцию capitalizeEvenLetters, которая принимает строку и возвращает новую строку, где каждая четная буква (по индексу) становится заглавной. Используй цикл for.
```JavaScript
function capitalizeEvenLetters(word) {
  // твой код здесь
}

console.log(capitalizeEvenLetters("javascript")); // "jAvAsCrIpT"
```
2.  Фильтрация массива (функция filter)
Напиши функцию filterPositiveNumbers, которая принимает массив чисел и возвращает новый массив только с положительными числами, используя метод filter.
```JavaScript
function filterPositiveNumbers(numbers) {
  // твой код здесь
}

console.log(filterPositiveNumbers([-2, 5, 0, 10, -3])); // [5, 10]
```
3. Изменение элементов массива (функция map)
Напиши функцию doubleNumbers, которая принимает массив чисел и возвращает новый массив, где каждое число умножено на 2. Используй метод map.
```JavaScript
function doubleNumbers(numbers) {
  // твой код здесь
}

console.log(doubleNumbers([1, 2, 3])); // [2, 4, 6]
```

4. Простое ООП с this
Создай объект person с свойствами name и age, а также методом introduce, который выводит в консоль:
"Привет, меня зовут [name] и мне [age] лет." (используй this).
```JavaScript
const person = {
  name: "Иван",
  age: 25,
  introduce() {
    // твой код здесь
  }
};

person.introduce(); // "Привет, меня зовут Иван и мне 25 лет."
```

5. Проверка на палиндром
Напиши функцию isPalindrome, которая проверяет, является ли слово палиндромом (читается одинаково слева направо и справа налево, например: "топот"). Функция должна возвращать true или false.
```JavaScript
function isPalindrome(word) {
  // твой код здесь
}

console.log(isPalindrome("топот")); // true
console.log(isPalindrome("привет")); // false
```

