# Anza kujifunza mtandao

## Utangulizi

Ndugu yangu bila kukuchosha nitakupa maelezo mafungu ya vitu vya msingi ampavyo inakupasa ujue kabla sijakuonyesha jinsi ya kutengeneza kurasa za mtandao

# Nini unapaswa kuwa unajua kabla ya kupata huu utangulizi
* Ujue kusoma na kuandika
* Ujue kutumia komputa, kuperuzi mtandao, kutengeneza, kutunza na kufungua *file* kwenye komputa yako

# Vifaa unavyopaswa kuwa navyo
komputa yeyote ile inayoweza kutengeneza, kutunza na kufungua *file* kwenye komputa yako. 

## Lengo ni nini
Lengo nataka ujue kutengeneza kurasa za mtandao. hivyo basi ukimaliza tu kusoma na kufanya kile nitakachokwambia utaweza kufanikiwa kutengeneza kurasa yako ya mtandao. Hata kama unataka kuwa *professional* inakupasa uanze chini, pole pole ukipanda, cha msingi unatakiwa uelewe mambo ya msingi kisha uyashike kama vile kunywa maji. Ukweli yanapaswa yawe ndani ya damu.

# Mambo ya msingi ya HTML 
*Hypertext Markup Language (HTML)* ni lugha ya komputa inayotumia *tag* kutengeza muundo wa kurasa za mtandao ili zilete maana na kufikisha ujumbe uliokusudiwa kwa ufanisi. 

Unajua mitandao mingi inatumika kutoa habasi kama ilivyo magazeti, lakini mtandao ni zaidi ya gazeti maana unaweza kuweka picha, video, sauti na pia inatumika kwenye application mbali mbali kwenye kukusanya data na kuweza kutoa ripoti. kwa hivyo unaweza kurasa ya mtandao inaweza ikawa na kichwa cha habari *(heading)*, aya *(paragraph)*, orodha *(list)*, Picha, video, sauti, fomu, jedwali na mengineo.

Hivyo kazi kubwa ya *HTML* ni kuweka hivyo vitu kwenye mpangiliao unaofaa ili *browser* iweze kuwasilisha kwa yule anayetembelea kurasa hiyo

Hivyo basi *HTML* ndio lugha mama kwenye mtandao, yaani Duniani hakuna mtandao wowote uliotengenezwa bile HTML. ambavyo kama tutakavyoweza kuona.

Kitu cha msingi ni kwamba *HTML* sio programing languaje ni markup language. HTML inatumia alama kuzipa maana na mantiki sehemu za kurasa. hii inawezesha sehemu fulani ya kurasa kuonekana tofauti na nyingine.

# HTML Element
*HTML element* ni alama ambazo zinatumika kueleza na kupanga maudhui yako. Mara nyingi zinakua zimefungia maudhui yako yaani kunakua na alama ya kuanzia *start tag* na alama ya kufungia *end tag*

kwa mfano ukitaka kutengeneza kicha cha habari kwenye *html* unaaandika hivi

```html
<h1>Maajabu Ngorongoro<h1>
```
na aya *paragraph* unaandika hivi

```html
<p>Ngorongoro ni moja ya vivutio vikubwa sana nchini kutokana na maajabu yake</p>
```

hivyo utaona kwamba *element* ina sehemu kuu nne
1. *Opening tag* hii ni alama ya kuanzia kwenye mfano wetu wa *paragraph* hapo juu `<p>` ndio alama ya kuanzia. Kwa maneno mengine kila unapotaka kuandika aya lazima uanze na `<p>`. Kitu cha kuangalia ni kwamba kila alama ya kuanzia lazima iwe ndani ya `<>`
2. *closing tag* hii ni alama ya kufungia, kwenye mfano wetu wa *paragraph* hapo juu </p>. Vile vile kila aya ni lazima imalizikie na `</p>`. Angalia kwa makini alama ya kufungia inatakiwa iwe ndani ya `</>`.
3. *Content* Aya ni maudhui *content* ya *element* kwa mfano wetu wa *paragraph* ni maelezo ya maandishi tu *'Ngorongoro ni moja ya vivutio vikubwa sana nchini kutokana na maajabu yake'*.
4. *The element* alama ya kuanzia, alama ya kufungia pamoja na maelezo yaliyo ndani yako ndio yanafanya element

Tuache maneno mengi twende kwenye kutengeneza kurasa *code* 

# Kurasa yako ya kwanza
1. Fungua notepad kwenye komputa yako, fungua *file* jipya *copy code* hizi hapa chini kisha *paste* kwenye *file* lako kwa jina hili **index.html**



```html

<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>Kurasa yanngu ya kwanza</title>
  </head>
  <body>
    <h1>Kurasa yangu</h1>
    <p>Leo nina furaha sana maana nimeweza kutengeneza kurasa yangu ya kwanza ya mtandao.
      shida kubwa sijui mtandao wangu nitauitaje? halafu sijui watu watawezaji kuufikia
    </p>
    
    <p>Ila mwalimu amenitoa shaka ya kwamba atatuelekeza hayo yote huko mbele.
    Yaani nikimaliza kitabu hiki najua A to Z</p>
    <img src="images/firefox-icon.png" alt="My test image">
  </body>
</html>
```
Hapa, kuna vitu vifuatavyo vya msingi ambavyo vinaunda hii kurasa

*HTML* sio programming language ni markup langauge ni lugha 

All HTML documents must start with a document type declaration: <!DOCTYPE html>.

The HTML document itself begins with <html> and ends with </html>.

The visible part of the HTML document is between <body> and </body>.

* `<!DOCTYPE html>` - Hii inakaa kwenye mstari wa kwanza kabisa kabla ya vitu vingine vyote, yenyewe inaonyesha kanuni zipi za *HTML* ulizotumia kutengeneza kurasa yako. Mfano hii yetu ni *HTML5*.

* `<html></html>` —  `<html>` *element*. huu ni mzizi wa *element* zote *(root element)*. Kurasa zote za mtandao lazima zianze na  `<html>` na kumalizikia na `</html>`.

