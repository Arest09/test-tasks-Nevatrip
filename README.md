<h3> Задание № 2 на верстку</h3>


-----------------------------
1. :ghost: [Верстка страницы](https://github.com/Arest09/Nevatrip-page); [githubpages](https://arest09.github.io/Nevatrip-page/)
  
1. :alien: Устранить скролл

Решить проблему со скролом можно разными способами:
+ для правильного расчета размера элементов я добавил свойство __"border-box"__ для всех css элементов,прописав __box-sizing:border-box__ 
+ Один из вариантов как можно адаптировать таблицу и избавиться от горизонтального скролла - обернуть таблицу,допустим div`ом,и прописать данной обертке __overflow-x: auto__; 
В это случае скролл будет не у страницы, а у таблицы
ссылка на [pencode](https://codepen.io/Arest09/pen/RwymmKv) 
+ Tакже можно добавить медиа запрос,в котором мы уменьшим шрифт контента таблицы, при появлении  [скролла](https://codepen.io/Arest09/pen/mdLYYBY)  
+ Другой [способ](https://codepen.io/Arest09/pen/ZEoNNMX) адаптировать таблицу - задать строкам и ячейкам (tr,td) display:block,width:100%;в этом случае контент будет выходить за границы ячеек,поэтому надо изменить height на min-height


-----------------------------

<h3>Задание № 3 js </h3>

+ [Билеты на событие](https://docs.google.com/spreadsheets/d/1m0vJuWw2pQTQ_b1RRWxqBw_VCO5rBv7sfb0afx5Rw2k/edit#gid=0)
 <br>

+ [Время из A в B](https://github.com/Arest09/-A-B)
[Здесь](https://nevatrip.herokuapp.com/) страница лежит на хостинге;
