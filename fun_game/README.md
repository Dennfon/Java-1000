<h1 class="title">Забавная игра (30%)</h1>
<p><a href="https://acmp.ru/index.asp?main=task&id_task=208" target="_blank">Ссылка на задачу</a></p>
<p><b>Время: 1 сек.<br>Память: 16 Мб<br>Сложность: 30%</b></p>
<p>Легендарный учитель математики Юрий Петрович придумал забавную игру с числами. А именно, взяв произвольное целое число, он переводит его в двоичную систему счисления, получая некоторую последовательность из нулей и единиц, начинающуюся с единицы. (Например, десятичное число 19<sub>10</sub> = 1*2<sup>4</sup>+0*2<sup>3</sup>+0*2<sup>2</sup>+1*2<sup>1</sup>+1*2<sup>0</sup> в двоичной системе запишется как 100112.) Затем учитель начинает сдвигать цифры полученного двоичного числа по циклу (так, что последняя цифра становится первой, а все остальные сдвигаются на одну позицию вправо), выписывая образующиеся при этом последовательности из нулей и единиц в столбик — он подметил, что независимо от выбора исходного числа получающиеся последовательности начинают с некоторого момента повторяться. И, наконец, Юрий Петрович отыскивает максимальное из выписанных чисел и переводит его обратно в десятичную систему счисления, считая это число результатом проделанных манипуляций. Так, для числа 19 список последовательностей будет таким:</p>
<p>10011<br>
11001<br>
11100<br>
01110<br>
00111<br>
10011<br>
…</p>
<p>и результатом игры, следовательно, окажется число 1*2<sup>4</sup>+1*2<sup>3</sup>+1*2<sup>2</sup>+0*2<sup>1</sup>+0*2<sup>0</sup> = 28.</p>
<p>Поскольку придуманная игра с числами все больше занимает воображение учителя, отвлекая тем самым его от работы с ну очень одаренными школьниками, Вас просят написать программу, которая бы помогла Юрию Петровичу получать результат игры без утомительных ручных вычислений.</p>
<h2>Формат ввода</h2>
<p>Входной файл input.txt содержит одно целое число N (0 ≤ N ≤ 32767).</p>
<h2>Формат вывода</h2>
<p>Ваша программа должна вывести в выходной файл output.txt одно целое число, равное результату игры.</p>
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
        <td>19</td>
        <td>28</td>
     </tr>
     <tr>
        <td>1212</td>
        <td>1938</td>
     </tr>
  </tbody>
</table>