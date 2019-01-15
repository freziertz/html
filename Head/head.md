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
**stylesheet_ya_nje.css**
```css
        body {background-color: powderblue;}
        h1 {color: red;}
        p {color: blue;}

```

Tengeneza nakishi ya nje kisha iunganishe na kurasa yako


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
    <h1>Hiki ndio kichwa cha hapbari</>
    <p>Hii ndio aya yetu. Aya inaweka kwa kutumia tag ya p ikimaanisha <strong>paragraph</strong></p>
  </body>
</html>
```

## script

## base

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














