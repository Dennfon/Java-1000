<h1 class="title">Перестановка (24%)</h1>
<p><b>Время: 1 сек.<br>Память: 16 Мб<br>Сложность: 24%</b></p>
<p>Если Вы читали Гарри Поттера, то знаете, что повелитель зла, Лорд Волдеморт создал свое имя путем перестановки букв в своем настоящем имени. Так из имени «Tom Marvolo Riddle» он получил «I am Lord Voldemort».</p>
<p>Напишите программу, которая проверяет, можно ли получить из одного имени другое путем перестановки его букв. При этом регистром букв нужно пренебречь.</p>
<h2>Формат ввода</h2>
<p>В первой строке входного файла input.txt записаны два слова, разделенные единственным в строке пробелом. Слова содержат только символы английского алфавита. Длина слов больше 0 и не превышает 50 символов.</p>
<h2>Формат вывода</h2>
<p>В выходной файл output.txt выведите «Yes», если возможно получить из одного имени другое, и «No» в противном случае.</p>
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
        <td>TomMarvoloRiddle IamLordVoldemort</td>
        <td>Yes</td>
     </tr>
     <tr>
         <td>stop pots</td>
         <td>Yes</td>
     </tr>
     <tr>
          <td>abbc bac</td>
          <td>No</td>
      </tr>
  </tbody>
</table>