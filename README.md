# group_project
### Наш проект посвящен функционированию слов с суффиксом "-изм-" на материалах докладов съездов ЦК КПСС 1939-1966х гг. Мы решили взять именно этот суффикс, потому что ключевые понятия советсой идеологии имеют именно его.
### Перед началом составления и анализа корпуса мы рассмотрели частоту употребления этих слов на протяжении всего советского периода. Выбранный нами временной промежуток, кажется особо интересным в рамках советской истории. Мы хотели посмотреть, как использовались слова с -измами, изменялись их значения и употребление в достаточно напряженное для СССР время : в ходе Второй мировой войны и первые годы послесталинского периода.Как видно по графам из НКРЯ и Ngrams, в расматриваемый нами период не был обнаружен пик употребления какого-либо из этих слов. 
![Слайд 1](https://github.com/angelinakrivova/group_project/blob/master/%D0%9D%D0%BA%D1%80%D1%8F%201(1).PNG)
![Слайд 2](https://github.com/angelinakrivova/group_project/blob/master/%D0%9D%D0%BA%D1%80%D1%8F%202.PNG)
![Слайд 3](https://github.com/angelinakrivova/group_project/blob/master/Ngrams.PNG)
### Чтобы посмотреть на общую картину ассоциаций с самыми распространенными "-изм"ми, используем программу "Rusvectores" и в результате подтверждается догадка о том, что все "-изм"ы связаны и вписаны в общий контекст, который мы и рассмотрим.
![Слайд 4](https://github.com/angelinakrivova/group_project/blob/master/ruwikiruscorpora_upos_skipgram_300_2_2019_d24bf8dcd78e7d34ee765c6e74e5c74d.png)
![Слайд 5](https://github.com/angelinakrivova/group_project/blob/master/%D0%B1%D0%BE%D0%BB%D1%8C%D1%88%D0%B5%D0%B2%D0%B8%D0%B7%D0%BC.jpg)
![Слайд 6](https://github.com/angelinakrivova/group_project/blob/master/%D0%BA%D0%B0%D0%BB%D1%8C%D0%BA%D1%83%D0%BB%D1%8F%D1%82%D0%BE%D1%80.jpg)
![Слайд 7](https://github.com/angelinakrivova/group_project/blob/master/%D0%BA%D0%B0%D0%BF%D0%B8%D1%82%D0%B0%D0%BB%D0%B8%D0%B7%D0%BC.jpg)
![Слайд 8](https://github.com/angelinakrivova/group_project/blob/master/%D0%BA%D0%BE%D0%BC%D0%BC%D1%83%D0%BD%D0%B8%D0%B7%D0%BC.jpg)
![Слайд 9](https://github.com/angelinakrivova/group_project/blob/master/%D0%BB%D0%B5%D0%BD%D0%B8%D0%BD%D0%B8%D0%B7%D0%BC.jpg)
![Слайд 10](https://github.com/angelinakrivova/group_project/blob/master/%D0%BF%D0%B0%D1%80%D1%82%D0%B8%D1%8F.jpg)
![Слайд 11](https://github.com/angelinakrivova/group_project/blob/master/%D1%81%D0%B5%D0%BC%D0%B1%D0%BB%D0%B8%D0%B7.jpg)
![Слайд 12](https://github.com/angelinakrivova/group_project/blob/master/%D1%81%D1%82%D0%B0%D0%BB%D0%B8%D0%BD%D0%B8%D0%B7%D0%BC.jpg)
![Слайд 13](https://github.com/angelinakrivova/group_project/blob/master/%D1%82%D1%80%D0%BE%D1%86%D0%BA%D0%B8%D0%B7%D0%BC.jpg)
### Мы использовали собранные данные для создания корпуса текстов. Затем мы преобразовали его в формат тхт, чтобы лемматизировать тектсы в Mystem. После мы загрузили корпус и стоп-слова в AntConc, там мы провели работу с ворд-листом и сделали collacates c ограничением частоты в 30 и отсортированы по признаку stat. Их границы - от пяти слов слева до пяти слов справа. Но если коллакэйтс было удобно анализирвать с леммами, то рассматривать контекст было затруднительно. Поэтому мы провели ту же работу с нелемматизированным текстом и с помощью н-грамм проанализировали контекст. Мы пришли к выводу, что слова с -измами употребляются с ярко окрашенной стилиистически лексикой, и уже с использованием контекста в три-пять слов видно коннотацию употребленных слов.
![Слайд 14](https://github.com/angelinakrivova/group_project/blob/master/1-%D0%B4%D0%B5%D0%BB%D0%B0%D0%B5%D0%BC%20txt%20%D1%87%D0%B5%D1%80%D0%B5%D0%B7%20sublime.png)
![Слайд 15](https://github.com/angelinakrivova/group_project/blob/master/2-%D1%83%D1%80%D0%B0%20%D0%BF%D0%BE%D0%BB%D1%83%D1%87%D0%B8%D0%BB%D0%BE%D1%81%D1%8C.png)
![Слайд 16](https://github.com/angelinakrivova/group_project/blob/master/3-%D0%BB%D0%B5%D0%BC%D0%BC%D0%B0%D1%82%D0%B8%D0%B7%D0%B8%D1%80%D1%83%D0%B5%D0%BC%20%D1%87%D0%B5%D1%80%D0%B5%D0%B7%20mystem.jpg)
![Слайд 17](https://github.com/angelinakrivova/group_project/blob/master/4-%20%D0%B2%D1%81%D0%B5%20%D0%B5%D1%89%D0%B5%20%D0%BB%D0%B5%D0%BC%D0%BC%D0%B0%D1%82%D0%B8%D0%B7%D0%B8%D1%80%D1%83%D0%B5%D0%BC%20%D1%87%D0%B5%D1%80%D0%B5%D0%B7%20mystem.jpg)
![Слайд 18](https://github.com/angelinakrivova/group_project/blob/master/5-%D1%83%D0%B1%D0%B8%D1%80%D0%B0%D0%B5%D0%BC%20%D1%81%D0%BA%D0%BE%D0%B1%D0%BE%D1%87%D0%BA%D0%B8.jpg)
![Слайд 19](https://github.com/angelinakrivova/group_project/blob/master/6-%20%D1%82%D0%BE%D0%B6%D0%B5%20%D1%83%D0%B1%D0%B8%D1%80%D0%B0%D0%B5%D0%BC%20%D1%81%D0%BA%D0%BE%D0%B1%D0%BE%D1%87%D0%BA%D0%B8.jpg)
![Слайд 20](https://github.com/angelinakrivova/group_project/blob/master/7-%D0%B7%D0%B0%D0%B3%D1%80%D1%83%D0%B6%D0%B0%D0%B5%D0%BC%20%D0%B2%20%D0%B0%D0%BD%D1%82%D0%BA%D0%BE%D0%BD%D0%BA%20%D0%B8%20%D1%81%D1%82%D1%80%D0%BE%D0%B8%D0%BC%20%D0%B2%D0%BE%D1%80%D0%B4%D0%BB%D0%B8%D1%81%D1%82%20(%D1%85%D0%B7%20%D0%B7%D0%B0%D1%87%D0%B5%D0%BC%20%D0%BA%D1%81%D1%82%D0%B0).png)
![Слайд 21](https://github.com/angelinakrivova/group_project/blob/master/8-%D0%B4%D0%BE%D0%B1%D0%B0%D0%B2%D0%BB%D1%8F%D0%B5%D0%BC%20%D1%81%D1%82%D0%BE%D0%BF%20%D1%81%D0%BB%D0%BE%D0%B2%D0%B0.png)
![Слайд 22](https://github.com/angelinakrivova/group_project/blob/master/9-%D1%81%D1%82%D1%80%D0%BE%D0%B8%D0%BC%20%D0%B2%D0%BE%D1%80%D0%B4%D0%BB%D0%B8%D1%81%D1%82%20%D0%B1%D0%B5%D0%B7%20%D1%83%D1%87%D0%B5%D1%82%D0%B0%20%D1%81%D1%82%D0%BE%D0%BF%20%D1%81%D0%BB%D0%BE%D0%B2.png)
![Слайд 23](https://github.com/angelinakrivova/group_project/blob/master/10-%D1%81%D1%82%D1%80%D0%BE%D0%B8%D0%BC%20%D0%BD%D0%B0%20%D0%BE%D1%81%D0%BD%D0%BE%D0%B2%D0%B5%20%D0%B2%D0%BE%D1%80%D0%B4%D0%BB%D0%B8%D1%81%D1%82%D0%B0%20%D1%81%20%D0%BF%D0%BE%D0%BC%D0%BE%D1%89%D1%8C%D1%8E%20%D1%80%D0%B5%D0%B3%D1%83%D0%BB%D1%8F%D1%80%D0%BD%D0%BE%D0%B3%D0%BE%20%D0%B2%D1%8B%D1%80%D0%B0%D0%B6%D0%B5%D0%BD%D0%B8%D1%8F%20%D1%81%D0%BF%D0%B8%D1%81%D0%BE%D0%BA%20%D0%BA%D0%BE%D0%BB%D0%BE%D0%BA%D0%B5%D0%B9%D1%82%D0%BE%D0%B2.png)
![Слайд 24](https://github.com/angelinakrivova/group_project/blob/master/11-%D1%83%D0%B6%D0%B5%20%D0%BF%D0%BE%D1%81%D0%BB%D0%B5%20%D1%82%D0%BE%D0%B3%D0%BE%20%D0%BA%D0%B0%D0%BA%20%D0%BF%D0%BE%D0%BD%D1%8F%D0%BB%D0%B8%20%D1%87%D1%82%D0%BE%20%D0%BB%D0%B5%D0%BC%D0%BC%D0%B0%D1%82%D0%B8%D0%B7%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D1%8B%D0%B5%20%D1%82%D0%B5%D0%BA%D1%81%D1%82%D1%8B%20%D0%BD%D0%B5%20%D0%BE%D1%87%2C%20%D0%BD%D0%B0%20%D0%BE%D1%81%D0%BD%D0%BE%D0%B2%D0%B5%20%D0%BD%D0%B5%D0%BB%D0%B5%D0%BC%D0%BC%D0%B0%D1%82%D0%B8%D0%B7%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%BD%D1%8B%D1%85%20%D1%81%D0%B4%D0%B5%D0%BB%D0%B0%D0%BB%D0%B8%20%D0%B5%D1%89%D0%B5%20%D1%80%D0%B0%D0%B7%20%D0%BA%D0%BE%D0%BB%D0%BE%D0%BA%D0%B5%D0%B9%D1%82%D1%8B.png)
![Слайд 24](https://github.com/angelinakrivova/group_project/blob/master/12-%20%D0%B8%20N-%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D1%8B.png.png)
### Затем мы использовали Voyant Tools, чтобы проследить количество и плотность употреблений главных "-изм-"ов. Мы проанализировали как каждый текст в отдельности, так и, создав общий документ из всех материалов, проанализировали его. Таким образом, мы обнаружили в какой из периодов какие "-измы-" употреблялись чаще, это помогло выделить ключевые слова для определенного периода.
![Слайд 25](https://github.com/angelinakrivova/group_project/blob/master/18..docx)
![Слайд 26](https://github.com/angelinakrivova/group_project/blob/master/19..docx)
![Слайд 27](https://github.com/angelinakrivova/group_project/blob/master/20-1..docx)
![Слайд 28](https://github.com/angelinakrivova/group_project/blob/master/20-2..docx)
![Слайд 29](https://github.com/angelinakrivova/group_project/blob/master/21-1..docx)
![Слайд 30](https://github.com/angelinakrivova/group_project/blob/master/21-2..docx)
![Слайд 31](https://github.com/angelinakrivova/group_project/blob/master/22..docx)
![Слайд 32](https://github.com/angelinakrivova/group_project/blob/master/23-1..docx)
![Слайд 33](https://github.com/angelinakrivova/group_project/blob/master/23-2..docx)
![Слайд 34](https://github.com/angelinakrivova/group_project/blob/master/%D0%9E%D0%B1%D1%89%D0%B8%D0%B9_2..docx)
### Выводы: 
### 1. Мы рассмотрели распространенность существительных с суффиксом "–изм-" во время существования СССР.
 ### 2. Наиболее распространенные слова с "–изм-"ами в 40-60е гг. – политические термины, подразумевающие ряд идеологических, философских, исторических процессов.
### 3. Наиболее распространенные слова с "–изм-"ами по смысловой смежности можно объединить в тематическую группу.
 ### 4. Слова с "–изм-"ами имели особое значение для советских граждан. Неслучайно, «коммунизмом» заканчивались доклады и после этого слова следовали аплодисменты (конечно же, бурные и продолжительные), что говорит о наличии яркой стиллистической окраски у этого слова в рассматриваемый период.
### 5. Часто слова с "–изм-"ами были расположены рядом, что также должно было с большей силой влиять на слушателей, вызывать у них определенные ассоциации.
### 6. Слова с "–изм-"ами (социализм, коммунизм) – явления для советского человека всеобъемлющие. Они «в нашем сознании», «стране», «во всем».
 ### 7. Слова с "–изм-"ами играли ключевую роль в распространении советской идеологии, укреплении её силы в сознании граждан.
### 8. Наиболее частым по употреблению словом является «социализм», понятие, харктеризующее цель советской идеологии и объединяющее другие «идеологические» слова с "–изм"ами.
### 9. Редкие по употреблению - сталинизм, фашизм. Так, мы можем судить, что эти понятия не являлись опорными при докладах, как это может показаться
###    10. Также на сопоставлении частотности употреблений "-изм-"ов мы можем выявить главный конфликт истории нашей страны в 20-м веке: борьбу капитализма и социализма!

