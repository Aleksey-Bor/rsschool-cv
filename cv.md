# Aliaksei Barkouski
Telephone: **+37529 147-18-34.** E-mail: **aborki@gmail.com**

*I am job seeker for junior web developer/ Frontend*

*I am persistent in achieving my goal.*

**My skils:** 
* Knowledge of **Html**
* Knowledge of **CSS**
* Knowledge of **JS**


**My last code**(Game Puzl)**:**

[Puzle](http://fe.it-academy.by/Sites/0031003/puzl.html)


**Code:**
```JavaScript
"use strict";

window.addEventListener('load', posElem, false);
function posElem(EO) {
  EO = EO || window.event;
  var elems = document.getElementsByTagName('img');

  for (var i = elems.length - 1; i >= 0; i--) {
    var elem = elems[i];

    elem.style.top = elem.offsetTop + 'px';
    elem.style.left = elem.offsetLeft + 'px';
    elem.style.position = 'absolute';
    elem.onmousedown = imgMouseDown;
    elem.onmouseup = imgMouseUp;
  };


  function imgMouseDown(EO) {
    EO = EO || window.event;
    EO.preventDefault();
    console.log('Нажал на пазл');

    var dounShiftCoordX = EO.pageX - EO.target.offsetLeft;
    var dounShiftCoordY = EO.pageY - EO.target.offsetTop;

    var cont = document.getElementById('box');
    var pict = EO.target;
    cont.appendChild(pict);


    window.onmousemove = imgMouseMove;
    function imgMouseMove(EO) {
      EO = EO || window.event;
      EO.preventDefault();
      console.log('Тащу пазл');

      pict.style.top = (EO.pageY - dounShiftCoordY) + 'px';
      pict.style.left = (EO.pageX - dounShiftCoordX) + 'px';

    }
  }

  function imgMouseUp(EO) {
    EO.preventDefault();
    console.log('Отпустил пазл');

    window.onmousemove = null;

  }
};

```

**My last code**(Perpetual calendar)**:**

[Perpetual calendar](https://eternal-calendar.alieksieiborko1.repl.co/)

**Code:**
```JavaScript
'use strict'
// "Вечный" календарь. Работает с  100 г.н.э. по 275760 г.н.э. Введете интересующий год, месяц и число - календарь рассчитает какой это день недели.
let year = prompt("Введите интересующий вас год в формате ХХХХ");
console.log(year);

let month =  prompt("Введите порядковый номер интересующего вас месяца (если это январь - 1, февраль - 2, .... декабрь - 12)") - 1;
console.log(month);


let day = prompt("Введите интересующую вас дату (1-ый день месяца: 1; 2-ой день месяца: 2; 10-ый день месяца: 10 и т.д.");
console.log(day);

let dat = new Date(year, month, day);
console.log(dat);
console.log(dat.getFullYear());

function getWeekDay2(dat) {
  let days = ['ВОСКРЕСЕНЬЕ', 'ПОНЕДЕЛЬНИК', 'ВТОРНИК', 'СРЕДА', 'ЧЕТВЕРГ', 'ПЯТНИЦА', 'СУББОТА'];

  return days[dat.getDay()];
}

getWeekDay2(dat);
alert(`Интересующий вас день: ${getWeekDay2(dat)}`);
```

**My last works:**

[RETOART](http://retoart.ru)

[Нow to travel online](http://fe.it-academy.by/Sites/0031003/index.html)

**My teachers:**
1. Сourses **"Website development using HTML in KSS"** by **IT- Academy** in 2019.
1. Сourses **"Development of web applications on Java Script"** by **IT- Academy** in 2020.
1. I studied Java Script on my own in an online tutorial  **learn.javascript.ru**

**My English:**
My English A1 level. :confused:
I recently completed the program **"Polyglot: English in 16 hours"** by **Channel Russia Culture**. 

I need an effective English improvement program.

**Academic education:** Belarusian State Pedagogical University in 2000.

