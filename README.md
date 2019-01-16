# Translate.js

 > In first you need to define the key into the code !
 
-  Get your api key --> https://tech.yandex.com/translate/
-  XMLHttpRequest Method --> https://github.com/YoannCHB/Break

 <img alt="Translate Image" title="Translate" src="icon.png" width="50%"/>
 
 ----------------------------------
Just translate your page in any languages in a few minutes ! It's simple just look the code and put them in your website, it will go to translate your homepage in english, french, chines, spanish ...
----------------------------------

# Version-Beta
- [x] When you put your api key you can start !

```js
  key = "trnsl.1.1.20190116T140121R.00f8ae71621er1e0.eaefcd93daec53e594f1c0ce8527a69005b1b74e" //Your api key - Here it is an example
  data.to = "en" //Translate to english ('fr' French ...)
  type.push(tag("a")) //Push a new tag to translate (default: p, span, pre, i)
  Translate() //Launch the translation
```
# Translate automatically the page in the language of user

```js
window.onload = function(){
 //type.push("any item")
 Translate();
}
```
