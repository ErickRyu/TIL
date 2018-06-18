# Javascript

* IE 에서는 ES6 문법이 동작하지 않는다.
  * 해결책 : ES5로 작성하거나 [babel](https://babeljs.io/)같은 것을 사용한다.


## Method

* scrollIntoView

```javacript
var elmnt = document.getElementById("content");
elmnt.scrollIntoView();
```

## Insert JQuery using console

```javascript
var jq = document.createElement('script');
jq.src = 'https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js';
document.getElementsByTagName('head')[0].appendChild(jq);
```
[출처](https://stackoverflow.com/questions/7474354/include-jquery-in-the-javascript-console)