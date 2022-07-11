# Valeri Andeev
---
Frontend Developer
***
## Contacts
---
__*Phone:__ +7-999-443-07-60
__*Email:__ valerande@gmail.com
__*Github:__ @AVEValeri
__*Telegram:__ @valerande
---
## About Me 
---
I'm 28 years old. I'm an electrical engeneer by education. I managed ti work both in the restaurant business and in a mining enterprise. At my current job, being a technical support employee, I was offered to retrain as a front-end developer to create a company service.  At the moment, I am a front-end developer in the company, but I feel thet the technical knowledge is not enough to perform quite difficult tasks. For this reason, I decicec to take a course at th RS School in order to fill in the gaps in kniwledge.
---
## Skills and Proficiency:
---
* HTML5
* CSS3 (SASS/SCSS)
* JS Basic (ES5, ES6+)
* jQuery
* Git/GitHub
* Figma/Photoshop
---
## Code Examples:
--- 
```
function tableSearch(table, input) {

  input.addEventListener('keyup', () => {
    let regPhrase = new RegExp(input.value, 'i');
    let flag = false;

    for (let i = 1; i < table.rows.length; i++) {
      flag = false;

      for (let j = table.rows[i].cells.length - 1; j >= 0; j--) {
        flag = regPhrase.test(table.rows[i].cells[j].innerHTML);
        if (flag) break;
      }

      (flag) ? table.rows[i].classList.remove('is-hidden') : table.rows[i].classList.add('is-hidden')
    }
  });
}
```
***
## Educaton
---
* Siberian Federal University
    + Mining engeneer
---
## Languages
* __Russian__ - Native
* __English__ - A2