# **Artem Sushko**


## Contacts:
E-mail: sushkoartem85@yandex.by

GitHub: [TeMagic85](https://github.com/TeMagic85)

Discrd: TeMagic85#7743
***

## About myself:
When I first discovered the world of IT, I realized that I really like writing code and constantly learning something new, improving. Maybe I'm too responsible. "The harder it is, the more interesting it is!" - such a motto in the learning process)
***
## Skills:
* HTML
* CSS(SCSS)
* JavaScript (Functional Programming, DOM, OOP, MVC, SPA, Asynchronous JavaScript, Canvas, SVG, JSON, AJAX, ES6+)
* Git/Github
* Figma
* Editors: Sublime, VSCode
***
## Code examples:
```JavaScript
Array.prototype.filter = function(callback, thisArg) {
  const arr = [];
  const _length = this.length;
  for (let i=0; i<_length; i++) {
    !(i in this) ? null : callback.call(thisArg, this[i], i, this) ? arr.push(this[i]) : null;
  }
  return arr;
};
------------------------------------------------------------
function numberOfPairs(gloves)
{
  let count = 0;
  let clone = [...gloves];
  while(clone.length) {
      clone.indexOf(clone[0],1)>0 ? (count++, clone.splice(clone.indexOf(clone[0],1),1), clone.shift()) : clone.shift();
  }
  return count;
};
```
***

## Education:
* IT-Academy: website development with HTML/CSS & JavaScript
* IT-Academy: WEB development with JavaScript
***
## Language:
English level - Intermediate(B1)