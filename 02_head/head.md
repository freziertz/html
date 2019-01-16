# *Head* ni nini? metadata kwenye *html*

`<head>` *element* ni sehemu mahususi kwa *metadata (data about data)* na inakaa kati ya  `<html>` *tag* na `<body>` *tag*.

sehemu hii aionekani kwenye *web browser* wakati kurasa yako ikiwa *loaded* au inaonekana kwenye *display* ya mtumiaji.

*Head* ina vitu vifuatavyo `<title>, <style>, <meta>, <link>, <script>, and <base>`. Usiwe na hofu ndugu yangu leo nitapitia yote hayo na mengine mengi we jiweke tayari kupokea madini.

# Nini unatakiwa ujue kabla ya kujifunza *HTML Head*
Unatakiwa ujue *Mafunzo ya awali ya HTML*

# Lengo ni nini?
Kujifunza *HTML Head*, dhumuni lake, vitu gani muhimu ambavyo unaweza kuviweka kwenye *head* na mwisho tutaangalia matokeo yake.

# *HTML head* ni nini hasa?

Ngoja tuangalie ile  *html yetu ya kwzanza* hapa chini

```html
<!DOCTYPE html>
<html>
 **<head>
    <meta charset="utf-8">
    <title>My test page</title>
  </head>**
  <body>
    <p>This is my page</p>
  </body>
</html>
```

Kama nilivyosema sehemu hii ya `<head>` na `</head>` haionekani kwenye maudhui ya *browser* ya mtumiaji. sehemu iyayoonekana kwa mtumiaji ni  hiyo sehemui iliyo kati ya `<body>` na `</body>`.

`<head>` yetu kwenye huu mfano wetu ina vitu vichache sana lakini ukienda kuangalia `<head>` ya page kama ya google.com utashangaa jinsi ilivyo kuwa ina vitu vingi. lakini usihofu kwanza inabidi uelewe kisha utakua ukielewa hivyo vitu vingine kadiri unavyo weka muda wako kwenye *HTML*.
  
```html
<head>
  <meta charset="utf-8">
  <title>My test page</title>
</head>
```

Unaweza kufananisha majina ya kurasa ya magazeti na *title* kwenye *html* maana kila kurasa inakua na jina lake kutokana na maudhui yake. kwa mfano kwenye gazeti utakuta kuna habari za kitaifa, makala, habari za kimataifa na michezo. Kwenye kila kurasa title ni moja tu. ila kila kurasa inaweza ikawa na *title* yake. 

## title

`<title>` ni jina la kurasa yako ambayo hoenekana juu kwenye *title bar* ya *browser* yako. pia inaonekena kwenye *tab* au kwenye *bookmark/ favorite* kwa hiyo chochote unacho andika kati ya `<title>` na `</title>` ndio kinakua jina la kurasa yako. Pia kinatumika kwenye matokeo ya *search*

Tengeneza hii kurasa hapa chini halafu tupia macho kwenye *title bar* au kwenye *tab*, pia jaribu ku *bookmark*

**index.html** 

```html
<!DOCTYPE html>
<html>
 <head>
    <meta charset="utf-8">
    <title>Hii ni sehemu ya title yako</title>
  </head>
  <body>
    <p>This is my page</p>
  </body>
</html>
```

## style 
`<style>` *element* inatumika kuweka taarifa za mitindo au nakishi *(style)* kwenye ndani ya kurasa. Kumbuka kuna aina tatu za kuweka nakishi moja ni ndani ya kurasa kwenya *tag* husika. yapili ndio hii ya kuweka nakishi kwenye `<head>` na ya tatu ni kuweka nje ya kurasa ila kutumia *link* kuweka mahusiano kati ya kurasa yako na *CSS* yako.

Jaribu kuweka hii kwenya page yetu

```html
<style>
  body {background-color: powderblue;}
  h1 {color: red;}
  p {color: blue;}
</style>
```
itakua inaonekana hivi
**index.html** 

```html
<!DOCTYPE html>
<html>
 <head>
    <meta charset="utf-8">
    <title>Hii ni sehemu ya title yako</title>
    <style>
        body {background-color: powderblue;}
        h1 {color: red;}
        p {color: blue;}
    </style>
  </head>
  <body>
    <h1>Hiki ndio kichwa cha hapbari</>
    <p>Hii ndio aya yetu. Aya inaweka kwa kutumia tag ya p ikimaanisha <strong>paragraph</strong></p>
  </body>
</html>
```

## link
`<link>` *element* inatumika kuweka nakishi *(style sheet)* ya nje

```html
<link rel="stylesheet" href="stylesheet_ya_nje.css">
```
Tengeneza nakishi ya nje kisha iunganishe na kurasa yako

**stylesheet_ya_nje.css**
```css
        body {background-color: powderblue;}
        h1 {color: red;}
        p {color: blue;}

```
Itaonekana kama hivi
**index.html** 
```html
<!DOCTYPE html>
<html>
 <head>
    <meta charset="utf-8">
    <title>Hii ni sehemu ya title yako</title>
    <link rel="stylesheet" href="stylesheet_ya_nje.css">
  </head>
  <body>
    <h1>Hiki ndio kichwa cha habari</>
    <p>Hii ndio aya yetu. Aya inaweka kwa kutumia tag ya p ikimaanisha <strong>paragraph</strong></p>
  </body>
</html>
```
## favicon
Hiki ni kifupi cha *favorites icon* kutokana na vile inavyotumika kwenye *favorites* au orodha ya *bookmarks* kwenye *browsers*

kwa kawaida favicons ni picha ndogo inayo onekana kwenye *tab* ya *browser* kwenye kila kurasa iliyo funguliwa na pia inaonekana kwenye orodah ya *bookmarks*

Ukubwa wake ni *16-pixel square*


### Jinsi ya kuweka favicon
1. Weka *favicon* yako sehemu uliyo weka kurasa yako ya *index*. Iweke kwenye *format* ya *.ico* ingawa *format* nyingine kama *.gif* and *.png* zinakubalika ila sio kwenye browser zote, Ila *.ico* inatambulika kwenye *browser* zote.

2. Weka hii link kwenye sehemu ya `<head>` ya kurasa yako ili kuweza kuinganisha *favicon* yako na kurasa yako.

```html
<link rel="shortcut icon" href="favicon.ico" type="image/x-icon">
```

## script
`<script>` Hii inatumika kuweka *JavaScripts* kwenye kurasa yako. utajifunza zaidi kuhusiana na *JavaScripts* kwenye somo lingine.
mfano wetu hapa chini unaandika "Karibu Mtandaoni!" kwenye HTML element yenye id="mafano". Kwa sasa usijali vitu ambavyo uvielewi utavielewa pole pole.

**main.js**
```js
<script>
function functionYangu {
  document.getElementById("mfano").innerHTML = "Karibu Mtandaoni!";
}
</script>

```
**index.html**
```html
<!DOCTYPE html>
<html>
 <head>
    <meta charset="utf-8">
    <title>Hii ni sehemu ya title yako</title>
    <link rel="stylesheet" href="stylesheet_ya_nje.css">
  </head>
  <body>
    <h1 id="mfano">Hiki ndio kichwa cha habari</>    
    <p>Hii ndio aya yetu. Aya inaweka kwa kutumia tag ya p ikimaanisha <strong>paragraph</strong></p>
  </body>
</html>
```

## base
The <base> element specifies the base URL and base target for all relative URLs in a page:
`<base>` hii inatambulisha shina la *URL* na pia *link* ifungukaje kama hauja sema kwenye *html code* zako

```html
<base href="https://www.w3schools.com/images/" target="_blank">
```
**mfano**

**index.html**
```html
<!DOCTYPE html>
<html>
<head>
  <title>Jina la Kurasa yangu</title>
  <base href="https://www.brainy.com/images/" target="_blank">
</head>
<body>

<img src="html5.gif">
<p>Kwa kuwa tumeshaiambia kurasa yetu shina la URL yetu, *browser* itaangalia *image* "html5.gif" kwenye "https://www.brainy.com/images/html5.gif"</p>

<p><a href="https://www.brainy.com">Brainy link</a></p>
<p>The link hapo juu itafunguka kwenye *window* nyingine. Hii inatokana na ukweli kwamba tulishapanga ifungekeje kwenye base yetu. Kumbuka tulipanga "_blank" maana yake ifungue kurasa nyingine mpya.</p>

</body>
</html>
```

## Metadata: `<meta>` *element* ni ya nini?
*Metadata* ni *data* ambazo zinatoa taarifa zaidi kuhusu *data*
*HTML* ina tag maalumu kwa ajili ya kuweka maelezo kuhusu page usika tag hiyo ni `<meta>`
haya maelezo huwa ayaonekani kwa mtumiaji wa kawaida ila yana umuhimu sana kama nitakavyo waonyesha hapa chini wakati tukipitia baadhi yao.

### character set (character encoding)

Kwenye mfano wetu kuna hii line
```html
<meta charset="utf-8">
```
Hii inaeleza juu herufi zipi zinakubalika kwenye hii kurasa. kama unavyojua duniani kuna herufi mbali mbali zikiwemo za kilatini, kiarabu, kichina, kiindi na lunga nyingine hivyo basi komputer inatumia mbinu za kimahesabu kuzifanya hizo herufi kitaalamu inaitwa *character encoding*  au *character set* ambazo kurasa husika inaruhusiwa kutumia.

*utf-8* ni moja ya hizo *character set* na hii ndio inaitwa *universal character set* ambayo inaruhusu karibu herufi za lugha za binadumu zote duniani kutumika kwenye hiyo kurasa. Kwa sasa kurasa nyingi zinatumia hii aina.

Hii ina maana ukitumia hiyo kurasa yako itaweza kudisplay herufi au neno kutoka lungha yeyote duniani. kwa mfano kurasa yako itaweza kudisplay kiswahi, kingereza, kichina na kiarabu bila matatizo yeyote.

Jaribu kuweka maneno ya kichina kwenye kurasa yako halafu kisha badilisha weka latini character ser `ISO-8859-1` 

mfano wa wa kiarabu
`<p>Mfano Saudi Arabia kwa kiarabu: العربية السعودية </p>`


ila kwa dunia ya leo kuna baadhi ya browser zinabadilisha *character encoding* juu kwa juu hata kama umekose zinyewe zitadisplay vizuri.

`<meta>` *element* nyingi zinaudwa na *name* na *content attributes*

*name* inawakilisha aina gani ya *meta element*. Aina gani ya taarifa inayo
*content* inawakilisha taarifa yenyewe.

### author
unaweza ukatambulisha nani ametengeneza hiyo kurasa kwa kuweka mwandishi *author* kwenye *<meta>* kama ifuatavyo

```html
<meta name="author" content="Yahaya Frezier">
```

### description
*description* haya ni maelezo mafupi yenye maneno muhimu *keywords* kuhusu kurasa yako. Haya maelezo ni muhimu sana maana search engine yanatumia ili kuipaisha kurasa yako wakati watu wakitafuta kurasa zenye maudhui yanayo fanana na yako. hii kitaalamu inaitwa *Search Engine Optimization (SEO)*

```html
<meta name="description" content="Mafunzo ya HTML kwa lugha ya kiswahili">
```

### refresh
Hii inawezeha kurasa kuanza upya yenyewe *refresh* kila baada ya sekunde kadhaa. kwa mfano mara baada ya kurasa yako ku load kwa mara ya kwanza itakua ina anza upya kila baada ya sekunde ishirini. 

```html
<meta http-equiv="refresh" content="20">
```

### keywords
```html
<meta name="keywords" content="HTML, CSS, JavaScript">
```

### viewport

*viewport* ni sehemu ile ya kurasa yako inayo onekana kwa mtumiaji. Ukubwa wake hutofautiana kulingana na kifaa kinachotumika, inakua ndogo kwenye simu janja, inakuwa ya wastani kwenye *tablet* na inakuwa kubwa kwenye komputa.

`<meta>` *viewport element* kazi yake ni kutoa maelezo ya vipimo na kiwango kwa kurasa yako kwa browser ili iweze kuonekana kwa uzuri kulingana na ukubwa wa screen ya kifaa cha mtumiaji.

```html
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```

`width=device-width`  sehemu hii inaweka kipimo cha upana (*width*) wa kurasa yako kulingana na upana wa kifaa cha mtumiaji.

`initial-scale=1.0` sehemu hii inaweka kipimo cha kuanzia kukuza (*zoom level*) pale kurasa yako inapo funguka kwenye *browser* ya mtumiaji kwa mara ya kwanza.

## language
Hii ni muhimu kuweka, maana inatumiwa na *search engine* pamoja na *screen reader* kwa wale walemavu wa macho.
Uwekaji wake ni kuongeza lang attribute kwenye html tag kama inavyo onekana hapa chini

```html
<html lang="sw">
```
languahe code
https://www.w3schools.com/tags/ref_language_codes.asp

Kwa ujumla kurasa yetu sasa inaonekana kama ifuatavyo
**index.html**
```html
<!DOCTYPE html>
<html lang="sw">
<head>
  <title>Jina la Kurasa yangu</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="refresh" content="20">
  <meta name="description" content="Mafunzo ya HTML kwa lugha ya kiswahili">
  <meta name="keywords" content="HTML, CSS, JavaScript">
  <meta name="author" content="Yahaya Frezier">
  <base href="https://www.brainy.com/images/" target="_blank">
  <link rel="shortcut icon" href="favicon.ico" type="image/x-icon">
  <link rel="stylesheet" href="stylesheet_ya_nje.css">
   <script src="main.js"></script>
</head>
<body>

<img src="html5.gif">
<p>Kwa kuwa tumeshaiambia kurasa yetu shina la URL yetu, *browser* itaangalia *image* "html5.gif" kwenye "https://www.brainy.com/images/html5.gif"</p>

<p><a href="https://www.brainy.com">Brainy link</a></p>
<p>The link hapo juu itafunguka kwenye *window* nyingine. Hii inatokana na ukweli kwamba tulishapanga ifungekeje kwenye base yetu. Kumbuka tulipanga "_blank" maana yake ifungue kurasa nyingine mpya.</p>

</body>
</html>
```























