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

Unajua mitandao mingi inatumika kutoa habari mbali mbali kama ilivyo magazeti, lakini mtandao ni zaidi ya gazeti, maana inaweza kutoa habari kwa maandishi, picha, video, sauti na pia inatumika kwenye mifumo *application* mbali mbali kwenye kukusanya *data* na kuweza kuzikata na kutoa taarifa. Hivyo basi kurasa ya mtandao inaweza ikawa na vichwa vya habari *(heading)*, aya *(paragraph)*, orodha *(list)*, Picha, video, sauti, fomu za kukusanya taarifa, jedwali na mengineo.

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
2. *Closing tag* hii ni alama ya kufungia, kwenye mfano wetu wa *paragraph* hapo juu `</p>` ndio alama ya kufungia. Vile vile kila aya ni lazima imalizikie na `</p>`. Angalia kwa makini alama ya kufungia inatakiwa iwe ndani ya `</>`.
3. *Content* aya ni maudhui *content* ya *element* kwa mfano wetu wa *paragraph* ni maelezo ya maandishi tu *'Ngorongoro ni moja ya vivutio vikubwa sana nchini kutokana na maajabu yake'*.
4. *The element* alama ya kuanzia, alama ya kufungia pamoja na maelezo yaliyo ndani yako ndio yanafanya element

Tuache maneno mengi twende kwenye kutengeneza kurasa *code* 

# Kurasa yako ya kwanza
1. Fungua notepad kwenye komputa yako, fungua *file* jipya 
2. *copy html code* hizi hapa chini kisha 
3. *paste* kwenye *file* lako ulilofungua 
4. sevu kwa jina hili **index.html**
5. Kisha fungua ilo file kwenye browser yako unayoipenda
6. Utaona imeonyesha ifuatayo

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
Jitahidi ufuate maelezo haya chini uweze kutengeneza kurasa yako ya kwanza
1. Copy the HTML page example listed above.
2. Create a new file in your text editor.
3. Paste the code into the new text file.
4. Save the file as index.html.
5. 
Hapa, kuna vitu vifuatavyo vya msingi ambavyo vinaunda hii kurasa

*HTML* sio programming language ni markup langauge ni lugha 

All HTML documents must start with a document type declaration: <!DOCTYPE html>.

The HTML document itself begins with <html> and ends with </html>.

The visible part of the HTML document is between <body> and </body>.

1 `<!DOCTYPE html>` - Hii inakaa kwenye mstari wa kwanza kabisa kabla ya vitu vingine vyote, yenyewe inaonyesha kanuni zipi za *HTML* ulizotumia kutengeneza kurasa yako. Mfano hii yetu ni *HTML5* ambayo ndio teknolojia mpya kabisa inayo tumika hivi sasa.

2 `<html></html>` —  `<html>` *element*. huu ni mzizi wa *element* zote *(root element)*. Kurasa zote za mtandao lazima zianze na  `<html>` na kumalizikia na `</html>`.
3 `<head></head>`. Hii ni ` <head>` *element*. Hii ni sehemu ambayo unaitumia kuweka vitu vyote ambavyo sio sehemu ya maudhui yako. au vila ambavyo vinatakiwa kwenye kurasa yako lakini mtumiaji wa mtandao hatakiwi kiviona. Hivi ni vitu kama vile *keywords* ambavyo vinaitajika kwenye *search engine* kama google, *CSS* kwa ajili ya kulemba na kuipa mwonekano mzuri kurasa zako. hivi ni vitu ambavyo utajifunza baadae.
3 `<meta charset="utf-8">`. Hii inahitajika ili kuzitaarifu *browser* za watumiaji wako kwamba kurasa yako inaelewa lugha karibu zote za duniani yaani zikiwemo kingereza, kifansa, kiswahili, kiyahudi, kichina na kiarabu. usipoiweka hii maandishi yako yanaweza yasionekane vizuri. anagalia uchawi wako hapa ni `charset="utf-8"`
4 `<title></title>`. Hii `<title>` *element* inaweka jina la kurasa yako. jina ili linatumika kwenye *tab* na *bookmark/favorite*
5 `<body></body>` Hii `<body>` *element*  ni sehemu ambayo unajimwaga. unaweka vitu vyote ambavyo unataka mtumiaji wako avione. vitu kama vile vichwa vya habari, *link*, aya, video, gemu, orodha, jedwali, sauti, picha na mengineyo. Kwenye waraka huu nitakueleza yote hayo unayawekaje


