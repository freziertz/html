# Mambo ya msingi ya *HTML text*

Moja ya kazi kubwa ya HTML ni kuyapa muundo na maana maandishi ili browser iweze kuyawasilisha kwa usahihi. Leo nitakueleza vile ambavyo HTML inaweza kutumika kuzipa muundo maandishi kwa kuweka vichwa vya habari  (*headings*), aya (*paragraphs*), kuyapa msisitizo maneno  (*emphasis*), kutengeneza orodha (*lists*) na mengine mengi.

# Nini unatakiwa ujue kabla ya kujifunza *HTML Head*
Unatakiwa ujue Mafunzo ya awali ya *HTML*

paragraphs, headings, lists, emphasis, and quotations

# Lengo ni nini?
Kujifunza jinsi gani unaweza kutumia *HTML text element*, kuzipa muundo na maana sehemu mbalimbali za kura yako kama vile vichwa vya habari (*headings*), aya (*paragraphs*), orodha (*lists*), nukuhu (*quotations*) na msisitizo (*emphasis*).

## Headings - Vichwa vya habari
Kicha cha habari kinatakiwa kiwe ndani ya h element 
```html
<h1>Mimi ni kichwa cha habari.</h1>
```
Kuna *heading element* sita kwenye *HTML* ambazo ni `<h1>`, `<h2>`, `<h3>`, `<h4>`, `<h5>`na `<h6>` kila moja inawakilisha aina tofauti ya kichwa cha habari.

```html
<!DOCTYPE html>
<html lang="sw">
  <head>
    <title>Aina za vichwa vya habari vya HTML<title>
     <meta name="author" content="Yahaya Frezier">
     <meta name="description" content="Aina za vicha vya habari">
  </head>
  <body>
  <h1>Hiki ni kichwa cha habari kikubwa kabisa.</h1>
  <h2>Hiki ni kichwa cha habari kidogo.</h2>
  <h3>Hiki ni kichwa cha habari kidogo ukilinganisah na kichwa cha habari cha h2.</h3>
  <h4>Hiki ni kichwa cha habari kidogo ukilinganisah na kichwa cha habari cha h3.</h4>
  <h5>Hiki ni kichwa cha habari kidogo ukilinganisah na kichwa cha habari cha h4.</h5>
  <h3>Hiki ni kichwa cha habari kidogo kuliko sana kuliko vyote.</h3>
  </body>
</html>
```
vidokezo vya kutumia vichwa vya habari
1. Ni vyema kutumia `<h1>` moja kwenye kurasa yako, kisha chini yake ukatumia `<h2>` na chaini yake tena ukatumia `<h3>`.
2. Hakikisha unatumia vichwa vya habari kwenye mpangilio mzuri. Usichanganyecahnganye kwa mfano usiweke `<h1>` chini ya `<h2>` au `<h3>` maana utaichanganya *search engine* na kurasa yako haitakua na matokeo mazuri.

## paragraph - Aya
Kwenye HTML aya ni lazima kiwe ndani ya p element
```html
<p>kwenye *html* hii ni haya iliyo kamilika.</p>
```

Kitu cha msingi cha kukumbuka kwenye HTML huwezi kubadilisha muonekano au muudo kwa kuongeza space au kuruka mstari, ua kutumia enter au tab maana browser inaondoa space yeyote itakayo ongezeka kati ya neno na neno. Hizi hapa paragraph zote mbili zitaonyesha matekeo yanayofanana kwenye browser yako.

```html
<p>kwenye *html* hii ni haya iliyo kamilika.</p>

<p>kwenye     *html*   hii 
  ni haya iliyo
  kamilika.</p>
```

## Kwa nini tunahitaji muundo (structure)
Kujibu hilo ngoja tuangalie mfano hapa chini ambao hakuna *markup* yeyote iliyowekwa. Utaona inavyoonekana vipaya kwenye *screen* yako. 
Hii ni kwasababu hakuna *HTML element* yeyote ya kuipa muundo kurasa yako. Maana yake nini *browser* haijui kichwa cha habari ni kipi, aya ni ipi, orodha ni ipi? vilevile 
1. mtumiajia anatumia muda mchache sana kutafuta taarifa anazohitaji sana sana anasoma vichwa vy habari kama haoni kicha cha habari kama haoni kitu kinachomfaa ndani ya sekunde chache anaondoka mara moja.
2. *Search engine* zina pitia kurasa zako na kuhifadhi taarifa za muhimu. hivyo vicha vya habari ni muhimu sana kwa *search engine* kwenye kuiweka juu kurasa yako. Bila vichwa vya habari itakua ngumu sana kurasa yako kuonekana kupitia *search engine*
3. Kwa watu wenye ulemavu wa macho wanatumia programu fulani inaitwa *screen reader* yenyewe inasoma vichwa vya habari kwa sauti kabla ya mtumiaji kuchagua habari anayo itaka. Kama hakuna vichwa vya habari itabidi isome neno kwa neno kuanzia mwanzo mpaka mwisho wa kurasa yako. Itakuaje ngumu?
4. *JavaScript* na *CSS* zinatumia *HTML* tag na *HTML attributes* kuongeza nakishi na kuipa uhai kurasa yako bila hizo *tag*. Huwezi ukatumia zana zingine kama *Javascript* na *CSS*

Kwa hivyo basi tunahitaji kuzipa kurasa zetu muundo kwa kweka *HTML tag*

## Kwa nini tunahitaji maana (Semantics)
Tunahitaji maana ili kuipa uwezo *browser* kujua maana ya *tag* husika. Kwa mfano `<h1>` ni kichwa cha habari kikubwa hivyo basi browser itayafanya maandishi yake yawe makubwa na yalio kolea zaidi kuliko maandishi mengine kwenye kurasa yako. Ingawa kuna njia nyingine ya kufanya maandishi yawa makubwa na kukorea kwa kutumia *CSS*. Lakinia ukitumia `<h1>` maana yake ni tofauti kwa maana uzito wa wake ni mubwa mno hta seach engine na screen reader zinaelewa kwamba kwenye hii kurasa kichwa cha habari kilichobeba ujumbe wa hii kurahi ni kile kilicho ndani `<h1></h1>`

**index.html**

```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>Quick hummus recipe</title>
  </head>
  <body>
    Quick hummus recipe

    This recipe makes quick, tasty hummus, with no messing. It has been adapted from a number of different recipes that I have read over the years.

    Hummus is a delicious thick paste used heavily in Greek and Middle Eastern dishes. It is very tasty with salad, grilled meats and pitta breads.

    Ingredients

    1 can (400g) of chick peas (garbanzo beans)
    175g of tahini
    6 sundried tomatoes
    Half a red pepper
    A pinch of cayenne pepper
    1 clove of garlic
    A dash of olive oil

    Instructions

    Remove the skin from the garlic, and chop coarsely
    Remove all the seeds and stalk from the pepper, and chop coarsely
    Add all the ingredients into a food processor
    Process all the ingredients into a paste.
    If you want a coarse "chunky" hummus, process it for a short time
    If you want a smooth hummus, process it for a longer time

    For a different flavour, you could try blending in a small measure of lemon and coriander, chili pepper, lime and chipotle, harissa and mint, or spinach and feta cheese. Experiment and see what works for you.

    Storage

    Refrigerate the finished hummus in a sealed container. You should be able to use it for about a week after you've made it. If it starts to become fizzy, you should definitely discard it.

    Hummus is suitable for freezing; you should thaw it and use it within a couple of months.


  </body>
</html>

```

## orodha (*Lists*)
Mara nyingi tunatumia orodha pale tunapo taja Orodha ya vitu vya kununua, kwenye maswala ya ujenzi, kwenye biashara, kwenye  maelekezo na sehemu zingine nyingi. Na kwenye mtandao pia orodha inatumika sana.

Kuna aina mbili za list
1. Orodha isiyofuata mpangilio *unordered list*
2. Orodha inayofuata mpangilio *oredered list*
3. Orodha ndani ya orodha nyingine *nested list*

### Orodha isiyofata mpangilio *unordered list*
Hii ni orodha ambayo mpangilio wa vitu sio muhimu. Mfano wake ni kama orodha ya bidhaa, 
* Swala
* Chui
* Simba
* Faru
* Tembo

Kutengeneza orodha kama hiyo unahitaji  iwe ndani ya `<ul></ul>` ambazo zina wakilisha *unordered list* kicha ndani ya hizo ndio unaweka orodha yako *list* kwa kutumia *HTML element* `<li></li>`

**index.html**
```html
<!DOCTYPE html>
<html lang="sw">
  <head>
    <title>Serengeti<title>
     <meta name="author" content="Yahaya Frezier">
     <meta name="description" content="Wannyama wanaopatika serengeti">
  </head>
  <body>

<h1>Wanyama wanaopatika serengeti</h1>

<p>Baadhi ya wanyama wanao patikana kwenye mbuga ya senerengiti ni hawa</p>

<ul>
  <li>Swala</li>
  <li>Chui</li>
  <li>Simba</li>
  <li>Faru</li>
  <li>Tembo</li>
</ul>
</body>
</html>
````
### Orodha inayofuata mpangilio *ordered*
Kwa mfano angalia maelekezo yafuatayo. Ili ufike mbuga nzuri ya serengeti unatakiwa maelekezo yafuatayo
* Nenda mpaka mwisho wa hii barabara 
* Kish kata kulia 
* Nenda moja kwa moja mpaka utakuta kibanda cha mkaa
* Baada ya kibanda cha mkaa utakuta kuna barabara mbili kata kulia
* Ukianda mbele kidogo tu utaona jengo la ghorofa mbili hapa ndio kuna ofisi za utalii

Ili kuiweka kwenye orodha iliyo na mpangilio tunabadilisha kidogo ule mfano wetu
**index.html**
```html
<!DOCTYPE html>
<html lang="sw">
  <head>
    <title>Serengeti<title>
     <meta name="author" content="Yahaya Frezier">
     <meta name="description" content="Wannyama wanaopatika serengeti">
  </head>
  <body>

<h1>Wanyama wanaopatika serengeti</h1>

<p>Baadhi ya wanyama wanao patikana kwenye mbuga ya senerengiti ni hawa</p>

<ol>
 <li>Nenda mpaka mwisho wa hii barabara</li> 
 <li>Kish kata kulia </li> 
 <li>Nenda moja kwa moja mpaka utakuta soko pale soko la mambo ya utalii  </li> 
 <li>Baada ya soko utakuta kuna barabara mbili kata kulia </li> 
 <li>Ukianda mbele kidogo tu utaona jengo la ghorofa mbili hapa ndio kuna ofisi za utalii </li> 
</ol>
</body>
</html>
````

### Orodha iliyo ndani ya nyingine *nested ordered*
Orodha hii inakua ndani ya orodha nyingine. haijalishi orodha gani itakua ndani au itakua nje. Maana orodha isiyo na mpangilio inaweza kuwa ndani ya isiyo kuwa na mpangilio mwezake au ndani ya iliyo na mpangilio, pia na kinyume chake inakubalika pia.

**index.html**
```html
<!DOCTYPE html>
<html lang="sw">
  <head>
    <title>Serengeti<title>
     <meta name="author" content="Yahaya Frezier">
     <meta name="description" content="Wannyama wanaopatika serengeti">
  </head>
  <body>

<h1>Wanyama wanaopatika serengeti</h1>

<p>Baadhi ya wanyama wanao patikana kwenye mbuga ya senerengiti ni hawa</p>

<ol>
 <li>Nenda mpaka mwisho wa hii barabara</li> 
 <li>Kish kata kulia </li> 
 <li>Nenda moja kwa moja mpaka utakuta soko pale soko la mambo ya utalii unaweza ukanunua vitu kama vile </li>
      <ul>
        <li>vinyago</li>
        <li>fulana</li>
        <li>urembo</li>  
      </ul>  
 <li>Baada ya soko utakuta kuna barabara mbili kata kulia </li> 
 <li>Ukianda mbele kidogo tu utaona jengo la ghorofa mbili hapa ndio kuna ofisi za utalii </li> 
</ol>
</body>
</html>
````
## Msisitizo au mkazo (*Emphasis*)
Wakati mwingine tunapoandika au kuongea tunaonyesha msisitizo au mkazo kwenye maneno fulani. Vile vile *HTML* kuna jinsi ambavyo inaweka msisitiozo kwenye maudhui. 

Kwenye HTML msisitizo unawekwa kwa kutumia `<em></em>`. *Browser* inawlionyesha neno kwa mlazo (*italic*). Vile vile *screen reader* inakua na uwezo wa kusoma kwa sauti tofauti ili kuonyesha msisitizo.

```html
<!DOCTYPE html>
<html lang="sw">
  <head>
    <title>Serengeti<title>
     <meta name="author" content="Yahaya Frezier">
     <meta name="description" content="Wannyama wanaopatika serengeti">
  </head>
  <body>

<p>Ukiwa mbugani ni marufuku kutupa  <em>takataka</em> faini yake ni <em>TZS 300,000</em>.</p>

</body>
</html>

```

*Angalizo*
Tafadhali usitumie `<em></em>` kama nia yako ni kulaza maandishi ila tumia `<i></i>` au `<span></span>` na kisha tumia CSS kulaza maandishi
  
## Muhimu (*Important*)
Kuweka mkazo kwenye maneno fulani tunatamka kwa kuweka mkazo na wakati wa kuandika tuna yafanya yaonekane makali zaidi (*bold*)
kwa mfano 

Nakutegemea kwenye kikao chetu cha leo **Usichelewe**

Kwenye *HTML* tunatumia `<strong>` *element* kuyakoleza mananeno yake muhimu. Vilevile kwa wale walemavu wa macho zile scrren reader zina kuwezo wa kutoa sauti ya msisitizo kwenye maneno yote yaliyo ndani ya tag hii `<strong></strong>`

*Angalizo*
Tafadhali usitumie `<strong>` kama nia yako ni kukoleza maandishi ila tumia `<b></b>` au `<span></span>` na kisha tumia CSS kukoleza maandishi

```html
<p>Pombe hii ni <strong>Kali sana</strong>.</p>

<p>Nakuamini. <strong>Usinywe</strong> sana!</p>

```

