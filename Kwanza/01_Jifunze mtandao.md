# Anza Kujifunza Mtandao

## Utangulizi

Ndugu yangu bila kukupotezea muda nitakupa maelezo mafupi ya vitu vya msingi ampavyo inakupasa ujue kabla sijakuonyesha jinsi ya kutengeneza kurasa za mtandao

### Nini Unapaswa Kujua Kabla ya Kupata Huu Utangulizi
* Ujue kusoma na kuandika
* Ujue kutumia kompyuta, kuperuzi mtandao, kutengeneza, kutunza na kufungua *file* kwenye kompyuta yako

### Vifaa Unavyopaswa Kuwa Navyo
Kimsingi ni kifaa kimoja tu ambacho ni Kompyuta basi. Ni kompyuta yeyote ile yenye uwezo wa kutengeneza, kutunza na kufungua *file*. 

### Lengo ni Nini
Lengo nataka ujue kutengeneza kurasa za mtandao. Hivyo basi ukimaliza tu kusoma na kufanya kile nitakachokwambia utaweza kufanikiwa kutengeneza kurasa yako ya mtandao. Hata kama unataka kuwa *professional* inakupasa uanze chini, pole pole ukipanda, cha msingi unatakiwa uelewe mambo ya msingi kisha uyashike, ukiyashika yanakua kama vile kunywa maji. Ukweli mambo ya msingi yanapaswa yawe ndani ya damu.

### Mambo ya Msingi ya HTML 
*HTML* ni nini?
HTML ni kifupi cha maneno *Hypertext Markup Language* ni lugha ya kompyuta inayotumia *tag* kutengeza muundo wa kurasa za mtandao ili zilete maana na kufikisha ujumbe uliokusudiwa kwa ufanisi. 

Unajua mitandao mingi inatumika kutoa habari mbali mbali kama ilivyo magazeti, lakini mtandao ni zaidi ya gazeti, maana inaweza kutoa habari kwa maandishi, picha, video, sauti na pia inatumika kwenye mifumo *application* mbali mbali kwenye kukusanya *data* na kuweza kuzichakata na kutoa taarifa. Hivyo basi kurasa ya mtandao inaweza ikawa na vichwa vya habari *(heading)*, aya *(paragraph)*, orodha *(list)*, Picha, video, sauti, fomu za kukusanya taarifa, jedwali na mengineo.

Hivyo kazi kubwa ya *HTML* ni kuweka hivyo vitu kwenye mpangiliao unaofaa ili *browser* iweze kuwasilisha kwa yule anayetembelea kurasa hiyo.

Hivyo basi *HTML* ndio lugha mama kwenye mtandao, yaani Duniani hakuna mtandao wowote uliotengenezwa bile HTML. ambavyo kama tutakavyoweza kuona.

Kitu cha msingi ni kwamba *HTML* sio *programing language* yaani sio lugha inayotumika kuipa maelekezo Kompyuta. Hii ni *markup language* ni lugha ya alama ambazo zinaweza kutafsiriwa na *browser*. HTML inatumia alama kuzipa maana na mantiki sehemu za kurasa. hii inawezesha sehemu fulani ya kurasa kuonekana tofauti na nyingine.

## HTML Element
*HTML element* ni alama ambazo zinatumika kueleza na kupanga maudhui yako. Mara nyingi zinakua zimefungia maudhui yako yaani kunakua na alama ya kuanzia *start tag* na alama ya kufungia *end tag* kama inavyoonyesha kwenye mchoro hapo chini.

kwa mfano ukitaka kutengeneza kichwa cha habari kikuu kwenye *html* unaaandika hivi

```html
<h1>Ngorongoro na maajabu yake<h1>
```
na aya *paragraph* unaandika hivi

```html
<p>Ngorongoro ni moja ya ya maajabu ya Dunia</p>
```
![HTML Element](https://github.com/freziertz/html/blob/master/Kwanza/grumpy-cat-small.png)


Ukichunguza kwa makini hiyo picha ya *element* hapo juu utaona kwamba *element* ina sehemu kuu nne
1. *Opening tag* hii ni alama ya kuanzia kwenye mfano wetu wa *paragraph* hapo juu `<p>` ndio alama ya kuanzia. Kwa maneno mengine kila unapotaka kuandika aya lazima uanze na `<p>`. Kitu cha kuangalia ni kwamba kila alama ya kuanzia lazima iwe ndani ya `<>`
2. *Closing tag* hii ni alama ya kufungia, kwenye mfano wetu wa *paragraph* hapo juu `</p>` ndio alama ya kufungia. Vile vile kila aya ni lazima imalizikie na `</p>`. Angalia kwa makini alama ya kufungia inatakiwa iwe ndani ya `</>`.
3. *Content* aya ni maudhui *content* ya *element* kwa mfano wetu wa *paragraph* ni maelezo ya maandishi tu *'Ngorongoro ni moja ya ya maajabu ya Dunia'*.
4. *Element* alama ya kuanzia, alama ya kufungia pamoja na maelezo yaliyo ndani yake ndio yanafanya element

**Kumbuka**
*html element* unaweza ukaziandika kwa herufi kubwa `<BODY></BODY>` au `<BODY></Body>` au `<body></body>`. hizo zote zina maana sawa ila inashariwa uandike zote kwa herufi ndogo ili ziwe zinafanana na zisomeke vizuri,

Tuache maneno mengi twende kwenye kutengeneza kurasa yaani *coding* 

# Kurasa Yako ya Kwanza
Baada ya kupata utangulizi sasa leo utatengeneza kurasa yako ya kwanza kama ifuatavyo. Washa kopyuta yako kisha
1. Kama unatumia windows fungua Notepad au Mac fungua TextEdit kwenye komputa yako, fungua *file* jipya 
2. *copy html code* hizi hapa chini kisha 
3. *paste* kwenye *file* lako ulilofungua 
4. *save as* kwa jina hili **index.html**
5. Kisha double click ili kufungua ilo file kwenye browser yako unayoipenda au unaweza kufanya right click na kuchagua browser
6. Utaona imeonyesha ifuatayo

```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>ngorongoro na maajabu yake</title>
  </head>
  <body>
    <h1>Ngorongoro na maajabu yake</h1>
    <p>Leo nina furaha sana maana nimeweza kutengeneza kurasa yangu ya kwanza ya mtandao.
      shida kubwa sijui mtandao wangu nitauitaje? halafu sijui watu watawezaji kuufikia 
      ila ninachojua ni kwamba nimeweza kutengeneza Ngorongoro na maajabu yake.
    </p>
    
    <p>Ila mwalimu amenitoa shaka ya kwamba atatuelekeza hayo yote huko mbele.
    Yaani nikimaliza mafunzo haya nitakua najua A to Z</p>
    <img src="images/firefox-icon.png" alt="My test image">
  </body>
</html>
```
Hongera sana kwa kutengeneza kurasa yako ya kwanza lakini naona unashangaa sana kuhusu alama ambazo uzielewi ila baada ya muda mfupi utaelewa hivyo vyote. Hapa, kuna vitu vifuatavyo vya msingi ambavyo vinaunda hii kurasa. Uzuri ni kwamba kurasa zote duniani zina hivi vitu vya msingi.

## Maelezo Kuhusu Element Zilizotumika

1. `<!DOCTYPE html>` - Hii inakaa kwenye mstari wa kwanza kabisa kabla ya vitu vingine vyote, yenyewe inaonyesha kanuni zipi za *HTML* ulizotumia kutengeneza kurasa yako. Mfano hii yetu ni *HTML5* ambayo ndio teknolojia mpya kabisa inayo tumika hivi sasa.

2. `<html></html>` —  `<html>` *element*. huu ni mzizi wa *element* zote *(root element)*. Kurasa zote za mtandao lazima zianze na  `<html>` na kumalizikia na `</html>`.
3. `<head></head>`. Hii ni ` <head>` *element*. Hii ni sehemu ambayo unaitumia kuweka vitu vyote ambavyo sio sehemu ya maudhui yako. Vitu vile ambavyo vinatakiwa kwenye kurasa yako lakini mtumiaji wa mtandao hatakiwi kiviona. Hivi ni vitu kama vile *keywords* ambavyo vinaitajika kwenye *search engine* kama google, *CSS* kwa ajili ya kulemba na kuipa mwonekano mzuri kurasa zako. Hivi ni vitu ambavyo nitakuelekeza baadae.
4. `<meta charset="utf-8">`. Hii inahitajika ili kuzitaarifu *browser* za watumiaji wako kwamba kurasa yako inaelewa lugha karibu zote za duniani yaani zikiwemo kingereza, kifansa, kiswahili, kiyahudi, kichina na kiarabu. usipoiweka hii maandishi yako yanaweza yasionekane au kusomeka vizuri. Anagalia sana, uchawi wako hapa ni `charset="utf-8"`
5. `<title></title>`. Hii `<title>` *element* inaweka jina la kurasa yako. jina ili linatumika kwenye *tab* na *bookmark/favorite* pia inatumiwa na *search engine*
6. `<body></body>` Hii `<body>` *element*  ni sehemu ambayo unajimwaga. Unaweka vitu vyote ambavyo unataka mtumiaji wako avione. vitu kama vile vichwa vya habari, *link*, aya, video, gemu, orodha, jedwali, sauti, picha na mengineyo. Kwenye waraka huu nitakueleza yote hayo unayawekaje


