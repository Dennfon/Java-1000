<h1 class="title">Простые числа - 2 (28%)</h1>
<p><b>Время: 1 сек.<br>Память: 16 Мб<br>Сложность: 28%</b></p>
<p>Знаете ли вы, что такое простое число? Простое число – это натуральное число, имеющее ровно два различных натуральных делителя: единицу и самого себя. Все остальные числа, кроме единицы, называются составными. Например, числа 2, 3, 5, 7, 11 являются простыми. А числа 4, 6, 10 – составными.</p>
<p>Требуется из заданного набора чисел выбрать одно, имеющее максимальное количество простых делителей. Например, 30 имеет три простых делителя (2, 3 и 5), а 40 – только два (2 и 5).</p>
<h2>Формат ввода</h2>
<p>Первая строка входного файла input.txt содержит число N – количество чисел в наборе. Во второй строке теста содержится N чисел, разделенных пробелом. Все числа во входных данных целые, принимающие значения от 2 до 1024.</p>
<h2>Формат вывода</h2>
<p>В выходной файл output.txt выведите число с максимальным количеством простых делителей. Если таких чисел несколько, выведите наименьшее из них.</p>
<h3>Примеры</h3>
<table class="sample-tests">
  <thead>
     <tr>
        <th>Ввод</th>
        <th>Вывод</th>
     </tr>
  </thead>
  <tbody>
     <tr>
        <td>10<br>
            3 5 7 9 11 13 15 17 19 21</td>
        <td>15</td>
     </tr>
     <tr>
         <td>11<br>
             2 4 6 8 10 13 39 105 200 201 143</td>
         <td>105</td>
     </tr>
  </tbody>
</table>