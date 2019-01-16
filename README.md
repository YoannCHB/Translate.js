# Translate.js

 > In first you need to define the key into the code !
 
-  Get your api key --> https://tech.yandex.com/translate/
-  XMLHttpRequest Method --> https://github.com/YoannCHB/Break

 <img alt="Translate Image" title="Translate" src="icon.png" width="50%"/>
 
 ----------------------------------
Just translate your page in any languages in a few minutes ! It's simple just look the code and put them in your website, it will go to translate your homepage in english, french, chines, spanish ... Or in the language of user.
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

Language	| Code	Language	| Code
--------------------------------
Azerbaijan	az	Malayalam	ml
Albanian	sq	Maltese	mt
Amharic	am	Macedonian	mk
English	en	Maori	mi
Arabic	ar	Marathi	mr
Armenian	hy	Mari	mhr
Afrikaans	af	Mongolian	mn
Basque	eu	German	de
Bashkir	ba	Nepali	ne
Belarusian	be	Norwegian	no
Bengali	bn	Punjabi	pa
Burmese	my	Papiamento	pap
Bulgarian	bg	Persian	fa
Bosnian	bs	Polish	pl
Welsh	cy	Portuguese	pt
Hungarian	hu	Romanian	ro
Vietnamese	vi	Russian	ru
Haitian (Creole)	ht	Cebuano	ceb
Galician	gl	Serbian	sr
Dutch	nl	Sinhala	si
Hill Mari	mrj	Slovakian	sk
Greek	el	Slovenian	sl
Georgian	ka	Swahili	sw
Gujarati	gu	Sundanese	su
Danish	da	Tajik	tg
Hebrew	he	Thai	th
Yiddish	yi	Tagalog	tl
Indonesian	id	Tamil	ta
Irish	ga	Tatar	tt
Italian	it	Telugu	te
Icelandic	is	Turkish	tr
Spanish	es	Udmurt	udm
Kazakh	kk	Uzbek	uz
Kannada	kn	Ukrainian	uk
Catalan	ca	Urdu	ur
Kyrgyz	ky	Finnish	fi
Chinese	zh	French	fr
Korean	ko	Hindi	hi
Xhosa	xh	Croatian	hr
Khmer	km	Czech	cs
Laotian	lo	Swedish	sv
Latin	la	Scottish	gd
Latvian	lv	Estonian	et
Lithuanian	lt	Esperanto	eo
Luxembourgish	lb	Javanese	jv
Malagasy	mg	Japanese	ja
Malay	ms		
