<h1 class="title">Стрелок (28%)</h1>
<p><a href="https://acmp.ru/index.asp?main=task&id_task=298" target="_blank">Ссылка на задачу</a></p>
<p><b>Время: 1 сек.<br>Память: 16 Мб<br>Сложность: 28%</b></p>
<p>Стрелок стоит в центре стрельбища. На стрельбище несколько мишеней. Пули стрелка пробивают мишени насквозь, не теряя скорости, и могут поразить все мишени, стоящие на одной линии.</p>
<p>Будем считать, что стрелок стоит в центре начала координат. Известны координаты всех мишеней (для простоты будем считать их геометрические размеры пренебрежимо малыми). Определите минимальное число выстрелов, необходимых стрелку для поражения всех мишеней.</p>
<h2>Формат ввода</h2>
<p>Первая строка входного файла input.txt содержит натуральное число N – количество мишеней (N ≤ 20). Далее идет N строк с информацией о координатах каждой мишени, при этом в каждой строке указывается два целых числа через пробел X и Y (-10 ≤ X, Y ≤ 10).</p>
<h2>Формат вывода</h2>
<p>В выходной файл output.txt выведите одно целое число – наименьшее количество выстрелов, необходимых для поражения всех мишеней.</p>
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
        <td>4<br>
            2 2<br>
            -2 2<br>
            -2 -2<br>
            2 -2</td>
        <td>4</td>
     </tr>
     <tr>
        <td>6<br>
            2 2<br>
            -2 2<br>
            -2 -2<br>
            2 -2<br>
            1 1<br>
            -1 3</td>
        <td>5</td>
     </tr>
  </tbody>
</table>