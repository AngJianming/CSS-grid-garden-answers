CSS Grid Garden Answers
=======

Grid Garden is a game for learning CSS grid layouts. Check it out at https://cssgridgarden.com.

Question Answer Level 1.
```css
#garden {
    display: grid;
    grid-template-columns: 20% 20% 20% 20% 20%;
    grid-template-rows: 20% 20% 20% 20% 20%;
}

#water {
    grid-column-start: 3;
}
```

</br>

Question Answer Level 2.
```css
#garden {
    display: grid;
    grid-template-columns: 20% 20% 20% 20% 20%;
    grid-template-rows: 20% 20% 20% 20% 20%;
}

#poison {
    grid-column-start: 5;
}
```

</br>

Question Answer Level 3.
```css
#garden {
    display: grid;
    grid-template-columns: 20% 20% 20% 20% 20%;
    grid-template-rows: 20% 20% 20% 20% 20%;
}

#water {
    grid-column-start: 1;
    grid-column-end: 4;
}
```

</br>

Question Answer Level 4.
```css
#garden {
    display: grid;
    grid-template-columns: 20% 20% 20% 20% 20%;
    grid-template-rows: 20% 20% 20% 20% 20%;
}

#water {
    grid-column-start: 1;
    grid-column-end: 2;
}
```

</br>

Question Answer Level 5.
```css
#garden {
    display: grid;
    grid-template-columns: 20% 20% 20% 20% 20%;
    grid-template-rows: 20% 20% 20% 20% 20%;
}
  
#water {
    grid-column-start: 1;
    grid-column-end: -2;
}
```

</br>

Question Answer Level 6.
```css
#garden {
    display: grid;
    grid-template-columns: 20% 20% 20% 20% 20%;
    grid-template-rows: 20% 20% 20% 20% 20%;
}
  
#poison {
    grid-column-start : -3;
}
```

</br>

Question Answer Level 7.
```css
#garden {
    display: grid;
    grid-template-columns: 20% 20% 20% 20% 20%;
    grid-template-rows: 20% 20% 20% 20% 20%;
}
  
#water {
    grid-column-start: 2;
    grid-column-end: span 2;
}
```

</br>

Question Answer Level 8.
```css
#garden {
    display: grid;
    grid-template-columns: 20% 20% 20% 20% 20%;
    grid-template-rows: 20% 20% 20% 20% 20%;
}
  
#water {
    grid-column-start: 1;
    grid-column-end: apan 5;
}

```

</br>

Question Answer Level 9.
```css
#garden {
    display: grid;
    grid-template-columns: 20% 20% 20% 20% 20%;
    grid-template-rows: 20% 20% 20% 20% 20%;
}

#water {
    grid-column-start: span 3;
    grid-column-end: 6;
}
```

</br>

Question Answer Level 10.
```css
#garden {
    display: grid;
    grid-template-columns: 20% 20% 20% 20% 20%;
    grid-template-rows: 20% 20% 20% 20% 20%;
}

#water {
    grid-column: 4/6;
}
```

</br>

Question Answer Level 11.
```css
#garden {
    display: grid;
    grid-template-columns: 20% 20% 20% 20% 20%;
    grid-template-rows: 20% 20% 20% 20% 20%;
}

#water {
    grid-column: span 3/5
}
```

</br>

Question Answer Level 12.
```css
#garden {
    display: grid;
    grid-template-columns: 20% 20% 20% 20% 20%;
    grid-template-rows: 20% 20% 20% 20% 20%;
}

#water {
    grid-row-start: 3;
}
```

</br>

Question Answer Level 13.
```css
#garden {
    display: grid;
    grid-template-columns: 20% 20% 20% 20% 20%;
    grid-template-rows: 20% 20% 20% 20% 20%;
}

#water { 
    grid-row: span 3/6;
}
```

</br>

Question Answer Level 14.
```css
#garden {
    display: grid;
    grid-template-columns: 20% 20% 20% 20% 20%;
    grid-template-rows: 20% 20% 20% 20% 20%;
}

#poison {
    grid-row: 5;
    grid-column: 2;
}
```

</br>

Question Answer Level 15.
```css
#garden {
    display: grid;
    grid-template-columns: 20% 20% 20% 20% 20%;
    grid-template-rows: 20% 20% 20% 20% 20%;
}

#water { /* Answer */
    grid-column: span 4/6;
    grid-row: span 5/6;
}
```

</br>

Question Answer Level 16.
```css
#garden {
    display: grid;
    grid-template-columns: 20% 20% 20% 20% 20%;
    grid-template-rows: 20% 20% 20% 20% 20%;
}

#water {
    grid-area: 1/2/4/6;
}
```

</br>

Question Answer Level 17.
```css
#garden {
    display: grid;
    grid-template-columns: 20% 20% 20% 20% 20%;
    grid-template-rows: 20% 20% 20% 20% 20%;
}

#water-1 {
    grid-area: 1 / 4 / 6 / 5;
}

#water-2 {
    grid-area: 2/3/5/6;
}
```

</br>

Question Answer Level 18.
```css
#garden {
    display: grid;
    grid-template-columns: 20% 20% 20% 20% 20%;
    grid-template-rows: 20% 20% 20% 20% 20%;
}

.water {
    order: 0;
}

#poison {
    order: 1;
}
```

</br>

Question Answer Level 19.
```css
#garden {
    display: grid;
    grid-template-columns: 20% 20% 20% 20% 20%;
    grid-template-rows: 20% 20% 20% 20% 20%;
}

.water {
    order: 0;
}

.poison {
    order: -1;
}
```

</br>

Question Answer Level 20.
```css
#garden {
    display: grid;
    grid-template-columns: 50%;
    grid-template-rows: 20% 20% 20% 20% 20%;
}

#water {
    grid-column: 1;
    grid-row: 1;
}
```

</br>

Question Answer Level 21.
```css
#garden {
    display: grid;
    grid-template-columns: 12.5%;
    grid-template-rows: 20% 20% 20% 20% 20%;
}

#water {
    grid-column: 1;
    grid-row: 1;
}
```

</br>

Question Answer Level 22.
```css
#garden {
    display: grid;
    grid-template-columns: 100px 3em 40%;
    grid-template-rows: 20% 20% 20% 20% 20%;
}
```

</br>

Question Answer Level 23.
```css
#garden {
    display: grid;
    grid-template-columns: 1fr 5fr;
    grid-template-rows: 20% 20% 20% 20% 20%;
}
```

</br>

Question Answer Level 24.
```css
#garden {
    display: grid;
    grid-template-columns: 50px 1fr 1fr 1fr 50px;
    grid-template-rows: 20% 20% 20% 20% 20%;
}

#water {
    grid-area: 1 / 1 / 6 / 2;
}

#poison {
    grid-area: 1 / 5 / 6 / 6;
}
```

</br>

Question Answer Level 25.
```css
#garden {
    display: grid;
    grid-template-columns: 75px 3fr 2fr;
    grid-template-rows: 100%;
}
```

</br>

Question Answer Level 26.
```css
#garden {
    display: grid;
    grid-template-columns: 20% 20% 20% 20% 20%;
    grid-template-rows: repeat(4, 12.5px);
}

#water {
    grid-column: 1 / 6;
    grid-row: 5 / 6;
}
```

</br>

Question Answer Level 27.
```css
#garden {
    display: grid;
    grid-template: 60% 60% / 200px;
}

#water {
    grid-column: 1;
    grid-row: 1;
}
```

</br>

Question Answer Level 28.
```css
#garden {
  display: grid;
  grid-template: 1fr 50px / 20% 80%;
}
```




![Grid Garden screenshot](./images/screenshot.png)

## Author

Thomas Park

* (https://twitter.com/thomashpark)
* (https://thomaspark.co)
* (https://github.com/thomaspark)

## Translators

My gratitude to these contributors for their translations.

* Albanian by [Enea Muskaj](https://github.com/eneamuskaj)
* Arabic by [Basel Akasha](https://github.com/baselakasha)
* Azerbaijani by [jalalbmnf](https://github.com/jalalbmnf)
* Bengali by [Mohammad Mahid Alam](https://github.com/mahidsec)
* Bulgarian by [radoAngelov](https://github.com/radoAngelov)
* Catalan by [Xavier Gaya](https://github.com/xavigaya)
* Chinese Simplified by [Jin](https://github.com/winar-jin)
* Chinese Traditional by [Joy Shan-Chun Kuo](https://github.com/joykuotw)
* Dutch by [Wietse Neven](https://github.com/wietseneven)
* Estonian by [Sten Leinasaar](https://github.com/StenLeinasaar)
* Farsi by [leonine90](https://github.com/leonine90)
* French by [Forresst](https://github.com/forresst)
* Finnish by [Minna N.](https://github.com/minna-xD)
* German by [Rafael Schwemmer](https://github.com/schwemmer)
* Greek by [lmintmate](https://github.com/lmintmate)
* Hindi by [Ayush Chauhan](https://github.com/ayushchauhan101)
* Hungarian by [Krisztian Papp](https://github.com/pehsa)
* Indonesia by [I Putu Cahya Adi Ganesha](https://github.com/Ipcagr1d)
* Italian by [sirLisko](https://github.com/sirLisko)
* Japanese by [shuuji3](https://github.com/shuuji3)
* Korean by [YunHak Kwon](https://github.com/tienne)
* Latvian by [Arturs Kirtovskis](https://github.com/Akirtovskis)
* Norwegian by [Victoria Bergquist](https://github.com/vicbergquist)
* Polish by [Jawa the Cat](https://github.com/jaworek)
* Portuguese (Brazil) by [Gabriel](https://github.com/gcacars)
* Portuguese (Portugal) by [João Bagio](https://github.com/jbagio)
* Romanian by [Vlad](https://github.com/pckltr)
* Russian by [Zaurbek Zhakupov](https://github.com/zzhakupov)
* Slovak by [Joe Henthorn](https://github.com/jjhen99)
* Spanish by [Ezequiel Pequeño Calvar](https://github.com/Remohir)
* Swedish by [Johannes Holmberg](https://github.com/johannesholmberg)
* Tagalog by [goriio](https://github.com/goriio)
* Tamil by [Thamizh](https://github.com/ThisisThamizh)
* Thai by [Anurat Chapanond](https://github.com/anurat)
* Turkish by [serdar](https://github.com/yigitserdar)
* Ukrainian by [Igor Klimchuk](mailto:igor.klimchuk@tstechpro.com)
* Urdu by [Asfandiyar Khan](https://github.com/asfand-dev)
* Pashto by [Muhammad Shafiq](https://github.com/shafiq-techmentors)
* Vietnamese by [Duy Phan](https://github.com/duyphanz)
* Yoruba by [Koleaje Olayinka](https://github.com/koleajeolayinka)

Don't see your language on the list? Add it!

Text to be translated is found in `docs.js`, `levels.js`, and `messages.js`.

Fork the [repo](https://github.com/thomaspark/gridgarden/), add your translations, and submit a pull request.

## Copyright and License

Copyright 2017 Thomas Park. Code released under [the MIT License](https://github.com/thomaspark/gridgarden/blob/gh-pages/LICENSE). Images released under [Creative Commons](https://creativecommons.org/licenses/by/3.0/legalcode.txt).
