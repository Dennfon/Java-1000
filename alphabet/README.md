<h1 class="title">Алфавит (25%)</h1>
<p><b>Время: 1 сек.<br>Память: 16 Мб<br>Сложность: 25%</b></p>
<p>Воспитательница Галя работает в детском саду. Кроме детских игр в этом детском саду проходят занятия. Вот уже неделю ребята изучают буквы английского алфавита. Каждое утро воспитательница выстраивает всех своих подопечных в ряд и они играют в игру.</p>
<p>Первый ребенок в ряду громко называет первую букву алфавита – A. Второй должен назвать B, третий – C и так далее. По счастливому стечению обстоятельств всего в группе 26 детей и столько же сколько и букв в английском алфавите.</p>
<p>Если каждый ребенок без ошибки назовет свою букву, то группа отпразднует знание английского алфавита и ребята по этому случаю съедят большой торт. Однако, пока что группе не удается правильно назвать все 26 букв и каждое утро то один, то другой называет свою букву неправильно и игра на этом заканчивается.</p>
<p>Ребята учат буквы подряд и каждый из них знает первые несколько букв алфавита и не может назвать остальные. Поэтому возможность выиграть напрямую зависит от их расстановки. К примеру, если последним в ряду окажется ребенок, знающий английский алфавит только до буквы D, то букву Z он назвать не сможет и группа не выиграет независимо от того, насколько хорошо выучили алфавит остальные ребята.</p>
<p>Галя считает, что группа в целом уже достаточно хорошо знает алфавит и хочет помочь своим ребятам выиграть. Для этого ей нужно всего лишь расставить их так, чтобы первый ребенок в ряду знал алфавит хотя бы до буквы A, второй хотя бы до буквы B и так далее, последний в ряду должен знать все буквы.</p>
<p>Помогите Гале решить: в каком порядке расставить ребят, чтобы они смогли выиграть или выясните, что это пока невозможно.</p>
<h2>Формат ввода</h2>
<p>Входной файл input.txt содержит строку, состоящую из 26 букв английского алфавита, записанных слитно; i-я из этих букв говорит о том, до какой буквы знает алфавит i-й ребенок.</p>
<h2>Формат вывода</h2>
<p>В первой строке выходного файла output.txt выведите YES, если воспитательнице удастся выстроить своих детей в ряд так, чтобы они выиграли и NO, если им для этого еще надо поучиться. Если расстановка возможна, во второй строке выведите перестановку из 26 чисел от 1 до 26 через пробел – порядок детей в ряду. Если решений несколько, можно вывести любое.</p>
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
        <td>ABCDEFGHIJKLMNOPQRSTUVWXYZ</td>
        <td>YES<br>
            1 2 3 4 5 6 7 8 9 10 11 12 13 14 15 16 17 18 19 20 21 22 23 24 25 26</td>
     </tr>
     <tr>
         <td>BCARTYXYZZYZZYXYXYZZYZZYXV</td>
         <td>YES<br>
             3 1 2 4 5 26 6 7 8 9 10 11 12 13 14 15 16 17 18 19 20 21 22 25 24 23</td>
     </tr>
      <tr>
          <td>AAZZZZZZZZZZZZZZZZZZZZZZZZ</td>
          <td>NO</td>
      </tr>
  </tbody>
</table>