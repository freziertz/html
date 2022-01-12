
CHAPTER 

# Week 1 - Content

**1.1 Introduction:** A video that introduces the content of Week 1.

**1.2 The big three:** Learn about the basic tools you will use to code for the Web including hypertext and Web browsers.

**1.3 Elements, tags and attributes:** Here you will begin learning about the functions of the different types of code.

**1.4 Character encoding:** To make you familiarized with international features.

**1.5 Best practices, the wisdom:** Studying other peoples mistakes is a great way to avoid the same pitfalls.

**1.6 More on tags:** Review of the tags we have just learned about and get started on your course project.

**1.7 Test your knowledge:** Try out these quizzes on all the things that you have learned in week one.

the proposal was created by Sir Tim Berners-Lee and was sent to his boss Mike Sendall, who described it as 'vague but exciting'.

Sir Tim Berners-Lee’s vision for universality enabled the development of a high-level network of content that allows any document to link to any other documents

The World Wide Web was initially created to make it easier to share research papers. It is a system of interlinked ‘hypertext’ documents that are accessed via the Internet; in essence, an information space. While he did not invent hypertext systems, Berners-Lee proposed using them 'to link and access information of various kinds as a web of nodes in which the user can browse at will.'

His breakthrough was to link hypertext to the Internet and he used three technologies to do this:

- HyperText Transfer Protocol (HTTP) is the foundation of data communication for the Web.
- HyperText Markup Language (HTML) is the main mark-up language for creating Web pages and information that can be displayed on a Web browser.
- Web addresses or a Uniform Resource Locator (URL) are used to reference a Web page.

In the following pages, we present HTML through what is usually called the big 3 (HTML5, CSS and JavaScript), the hypertext concept and the browser that is an application program that provides a way to look at and interact with all the information on the World Wide Web.

## What is HTML5?

## What is CSS?

## What is JS?

# Hypertext

Chanzo cha msingi cha Wavuti zote Ulimwenguni ni dhana ya *Hypertext* . Hypertext imejengwa juu ya wazo la kuunganisha taarifa pamoja, haitofautiani sana na kutumia *footnotes*, isipokuwa iwe rahisi zaidi. Wazo lilikuwa "Kuweka alama" taarifa yako na viunganishi na ufafanuzi wa jinsi ya kuigawanya katika sehemu mbali mbali (sura, sehemu, aya, jedwali, takwimu, n.k.)

Ndio sababu, mnamo 1989, Tim Berners-Lee alianza kuunda ufafanuzi wa *HTML: Hypertext Markup Language*, ili kupata njia rahisi, na sawia ya kuingiza Hyperlink kwenye taarifa za maandishi.

# The browser

Browser ni programu ambayo inatumika kwenye kuperuzi mtandao. Kazi kubwa ya browser ni kutafsiri na kuwakilisha kile kilichoandikwa kwenye kurasa ya HTML. Kuna aina mbali mbali ya browser ambazo ni Microsoft Internet Explorer, Google's Chrome, Mozilla Firefox, Apple's Safari, na Opera

Kama ilivyo ada, huwa unakutana na misamiati mipya kila unapojifunza kitu kipya lakini kila muda unavyokwenda na unavyozidi kuitumia ndio unaizoea. Hii haina tofauti kwenye *HTML* kuna misamiati mingi lakini ni vyema tukianza na misamiati mitatu muhimu ambayo ni *elements, tags na attributes*

# Elements

*Elements* au Vipengele ni alama ambazo hufafanua muundo na aina ya kitu kilichomo ndani ya ukurasa. *element* ndio zinaeleza kichwa cha hapari ni kipi, jina la kurasa, chumba kwenye kurasa, aya, picha na mengineyo ambayo tutajifunza. Element nyingi zinaweza kubeba element nyingine ndani yake kwa mfano kurasa yenyewe inaitwa body inaweza kuwa na heading element zaidi ya moja na inakuwa na aya picha na mengineyo

baadhi ya vipengele ambavyo vinatumika mara nyingi vinajumuisha vipingele vinavyo husu kichwa cha habari kuanzia h1 mpaka h6, kipengele cha aya p na kinacho husu chumba div.

# Tags

Utaigundua element kwa kuona ipo ndani ya alama hii `<>` yaani ndogo kuliko na kubwa kuliko  zikitazamana zikiwa zimezunguka jina la kipengele `<p>`. Ambayo inaunda kitu kinachoitwa *tags* au unaweza kuita lebo.

lebo ya kufungulia inaonyesha mwanzo wa kipengele, hii ina inaudwa na alama ya ndogo kuliko ikifuatiwa na jina la kipengele na ikimalizikia na alama ya kubwa kuliko. Kwa mfano `<p>`

lebo ya kufungia inaonyesha mwisho wa kipengele. yenyewe inaundwa na alama ya ndogo kulikwa ikifuatiwa  mkwaju wa mbele kisha jina la kipengele na kumalizia na alama ya kubwa kuliko `</p>`

Kile kilichopo kati ya lebo ya kufungulia na kufungia ndio maudhui ya kipengele. Kwa mfano aya inakua na lepo ya kufungulia `<p>` na lebo ya kufungia `</p>` na kile kilichopo kati kati ya lebo hizo ndio maudhui ya kipengele cha hii aya.



![Diagram of an element](https://courses.edx.org/assets/courseware/v1/9df11f203d18addb831da2f379cb49a5/asset-v1:W3Cx+HTML5.0x+2T_2016+type@asset+block/tags.png)

Tag nyingi zina lebo ya kufungulia na lebo ya kufungia, lakini kuna baadhi ya lebo za ajabu ambazo hazina lebo ya kufungia. kwa kawaida zinaitwa lebo zinazojifunga zenyewe *(self closing tag)*. Kwa kawaida hizo lebo zinawakilisha vipengele vile ambavyo vitu vyake vyote vinabebwa na vielezi yaani *attributes*. kwa mfano lebo kwa ajili ya kuweka picha yenyewe haina lebo ya kufungia ila kuna lugha mkato / mwishoni ambayo inawakilisha lebo ya kufungia. Pia kuna lebo nyingine hazina kabisa hata hiyo lebo mkato ya kufungia

`<img src="mlima_kilimanjaro.png" alt="mlima kilimanjaro"/>`

# Comments

Vitu vyote unavyoandika kwenye HTML yanasomwa na kutafsiriwa na komputer. Lakini wakati mwingine unahitaji kitu fulani kisifanyiwe kazi na komputa au unataka kuweka kumbukumbu yako mwenyewe na wasomaji wengine wa faili lako. Hapo ndio comments zinapoingia na zinawekwa kwa kutumia labe hii hapa 

```html
<!-- Hii ni comments -->
```

Unaweza kuona comments tags inaanza na `<!--` na kumalizikia na ` -->` hivyo basi chochote kilichopo  kinarukwa na komputa maana yake hakifanyiwi kazi kabisa

# Attributes

Attribute ni kielezi, kinaelezea zaidi kuhusu hiko kipengere. Kwa mfano id attribute kazi yake kubwa ni kukipa kipengele  utambulisho wa kipekee kwenye kurasa. na attribute ya daraja yaani class kazi yake kubwa kutambulisha hiki kipengele kipo kwenye daraja gani lakini kwa sasa usijali tutaona huko mbele matumizi yake zaidi.

`<p id = "kwanza" class ="kawaida"> Hii ni aya yenye id  ya kwanza </p>`

Angalia kwa makini utaona kila attribute ina vitu viwili vya kuzingatia yaani jina la attribute mfano id na class , pia kuna kielezi chenyewe yaani attribute value

# Angalizo!

Kitu kikubwa cha kuchunga kwnye HTML au lugha yeyote ya kumpyuta ni kufuata weledi wa hiyo lugha inavyotaka kwa maana kompyuta inafuata maelekezo bila kupindisha wala haina uwezo wa kufikiria na kurekebisha makosa yako. HTML inataka <p> iwe na mwanzo wake ambayo ni </p> . Sasa unaweza kutumia kam hivi na kompyuta ikaelewa

```htm	
<p>Hii itasomeka vizuri sana kama kawaida
<p> Hii pia itasomeka vizuri, ila sasa
<p> ukitaka kuweka kitu kingine katikati ndio <a href=""> shida inapoanza </a> hapo kompyuta haijui p imeisha ndio ikaanza a au a iko ndani ya p
<p>pia usichanganye vitu kama iko ndani weka ndani <em> sio </p> </em> hii sio sahini
<p>Kwa hivyo utaona ni vyyema kutumia <em>lebo ya kufungi</em></p> kila wakati
```



Lakini kuna kitu kingine cha kuzingatia. Kwa mfano, pale *browser* inapopokea *file* inaweza kutambua kwamba imepokea *HTML file* , lakini haitajua *version* gani ya *HTML* iliyotumika maana hiyo *version* ni muhimu sana. Ndio maana kitu cha kwanza kinacho hitajika kwenye *HTML file* yeyote ile ni tag ambayo itaeleza ni aina gani ya HTML file*:-

```html
<!DOCTYPE html>
```



# Character encoding

A **character set** is a collection of characters (letters and symbols) in a writing system.

A **character set** ni mkusanyiko wa herufi na alama kwenye mfumo wa uandishi.

Kila herufi au alama inapewa namba ambayo inaitwa *code point*. Hizo *code point* zinahifadhiwa kwenye *memory* ya kompyuta kwenye umbo la *bytes* (kipimo cha *data* kwenye *memory* ya komputa). Kwa lugha ya kitaalamu tunasema herufi zimesimbwa kwa kutumia *byte* moja au zaidi.

Kimsingi, herufi na alama zote zimehifadhiwa katika lugha ya kompyuta na **character encoding** ni kamusi ya ajabu ambayo inatusaidia kutafsiri lugha hii ya kompyuta kuwa kitu tunachoweza kuelewa. Kiufundi, ni kile kinachotumika kama rejeleo la kutoka *code point* kwenye umbo la *bytes* ili zihifadhiwe kwenyed kumbukumbu ya komputa na pia kuzisoma tena kutoka kwenye *bytes* kuzileta kwenye HTML yako kwenye herufi za kawaida.

Mifano ya *character encoding* ni pamoja na:

- ASCII: imejumuisha herufi na  alama chache na vituo zinazotumika kwenye lugha ya kiingereza
- Windows-1252 (Latin1): hii inajumuisha herufi tofauti tofauti  256 za *code points*
- ISO-8859-6: zinajumuisha herufi na alama zinazopatikana kwenye lugha ya kiarabu
- Unicode: hii ina jumuisha herufi na maandish ya lugha karibu zote zilizo hai kwenye hii dunia 

wakati una code kwenye HTML unatakiwa kubainisha encoding ambayo unataka kwenye kurasa yako. Inashauliwa kila wakati tumia Unicode ambayo ndio *UTF-8* kwenye kurasa zako. pia jiepushe na encoding nyingine ikiwemo *UTF-16*.

Ni vyema ieleweke kwamba kubainisha encoding kwenye kurasa yako peke yaka haitoshi. Pia unatakiwa uhakikishe kwamba editor unayotumia inahifadhi faili la kurasa yako kwenye UTF-8.

Read an [Introduction to character sets and encodings here](https://www.w3.org/International/getting-started/characters).

## The meta tag

Unatumi meta element pamoja na attribute ya charset kwenye kurasa yako ya HTML kuimbia browser yako herufi gani itakua inatumika kwenye kurasa yako

1. <meta charset="utf-8">

Vilevile unaweza kutumia *http-equiv* na *content attributes*. 

1. <meta http-equiv="Content-Type" content="text/html; charset=utf-8">

Inapendekezwa itumike ile ya kwanza kwa sababu ni haina mambo mengi pia ni vyema utumie `utf-8` wakati wote

## Wapi pa kuweka meta?

Tamko la meta inatakiwa liwe ndani kipengele cha head, na inatakiwa litajwe ndani ya 1024 bytes za mwanzoni mwa kurasa. Hivyo ikitajwa mapema ni vizuri zaidi. W3C wanashauri iwekwe mara tu baada ya lebo ya kufungulia ya head 

1. <!DOCTYPE html>
2. <html lang="en">
3.  <head>
4.   <meta charset="utf-8">
5.   ...
6.  </head>
7. </html>

# HTML character references

## Why we need character references

Before we learn what HTML character references are, let's look at how the need for them came about. 

Try the following file in your HTML:

1. <p>Welcome to the Introduction to HTML 5. The first tag we will be learning about is  the <html> tag.</p>

If you want to use a named character reference in your source code, use an ampersand symbol '&', followed by the name and a semi-colon. Names are case sensitive. For example, the following represents a no-break space:



# Anza kujifunza mtandao


## Utangulizi


Ndugu yangu bila kukupotezea muda nitakupa maelezo mafupi ya vitu vya msingi ampavyo inakupasa ujue kabla sijakuonyesha jinsi ya kutengeneza kurasa za mtandao


### Nini Unapaswa Kujua Kabla ya Kupata Huu Utangulizi
* Ujue kusoma na kuandika
* Ujue kutumia kompyuta, kuperuzi mtandao, kutengeneza, kutunza na kufungua *file* kwenye kompyuta yako



## Mtandao unafanyaje kazi

Unapoperuzi mtandao, tambua kwamba komputer iliyobebe kurasa unazozitumia inaweza kuwa sehemu yeyote ile kwenye hii dunia. Inaweza ikawa Arusha, Dar es salaam, Marekani au China tena hata huko ilipo inamilikiwa na mtu, kampuni au taasisi fulani.

Ili uweze kufika mahali server ilipo komputa yako inabidi iunganishwe na server nyingine ambayo inaitwa DNS server, Hii server ni kama vile phonebook ya komputer maana kwenye phone book kuna majina na namba za simu vile vile kwenye komputer kila server yenye mtandao ina namba ambayo inaitwa IP address. Kwa vichwa vyetu sisi binadamu ni ngumu sana kukumbuka numba badala yake kila namba inapewa jina na sisi kazi yetu kukumbuka jina. Hivyo kazi ya DNS ni kuhifadhi hayo majina na namba ya komputa mbalimbali. Hivyo wewe unapoingiza google.com yenyewe inatafuta number ya google.com na kutafuta kwenye mtandao kwa kutumia namba.

Pale unapojiunga kwenye mtandao unaunganishwa kwa msaada wa kampuni inayotoa huduma za mtandao yaani Internet Service Provider (ISP). Hizi kampuni zinaweza kuwa mitandao ya simu au makampuni yenye leseni ya kufanya  biashara hiyo. Hawa ndio wanaomiliki hizo DNS Server hivyo basi kwanza unajiunga kwao kisha wao ndio wanakuunganisha na Server nyingine duniani kama hizo kulingana na wapi unakwenda mpaka anafikiwa ISP aliyeunganisha na server yenye numba unayo hiitaji. Kuna michakato mingi ya kitaalamu hapo katikati lakini kwa lugha rahisi hii inakua kama ukupokezana vijiti ISP akiona hana hiyo server anamuuliza anamtupia mwenzake nae kama hana anamtupia mwenzake kwa kasi ya ajabu sana mpaka anapatikana.

Komputa yako inaunganishwa na server ambayo inaitwa DNS. Ambazo ziko kama phone books. Zinaiambia komputa au simu yako IP addresss ya jina la domaini ulilo andika. IP address ni namba yenye tarakimu 12 zilizotenganishwa na nukta kwenye mafungu manne ya tarakimu tatu kama hivi 123.234.134.154. Kila kifaa kilichounganishwa kwenye mtandao numba ya IP ya pekee ni kama numba ya simu ya komputa.

Cambridge
LONDON
The unique number that the
DNS server returns to your
computer allows your browser
to contact the web server
that hosts the website you
requested. A web server is a
computer that is constantly
connected to the web, and is set
up especially to send web pages
to users.

## Mantiki au Semantic

Ni utaratibu wa kuvipa vipengele maana na muundo kwa kutumia kipengele mahususi. Mantiki ya kipengele inaelezea thamani ya kipengele hicho kwenye kurasa bila kuangalia mtindo au mwonekano wa maudhui. Kuna faida mbalimbali za kutumia vipengele vinavyoleta maana zikiwemo kuwezesha komputa, *screen reader, search engine* na vifaa vingine kuweza kusoma na kuelewa maudhui ya kurasa husika. Vile vile HTML yenye vipengele vyenye maana inarahisisha kuifanyia kazi. Kwa sababu inaonyeshwa kwa uwazi kila kipengele kina maana gani. Kwenye HTML kuna baadhi ya vipengele kama div na span havileti mantikki yeyote ya kimaud isipokuwa vinatumika kwa ajili ya mtindo na kuremba kurasa.



# Mambo ya msingi ya HTML 
***Hypertext Markup Language (HTML)* **ni lugha ya komputa inayotumia *tag* kutengeza muundo wa kurasa za mtandao ili zilete maana na kufikisha ujumbe uliokusudiwa kwa ufanisi. 

Unajua sio siri, utoaji wa habari umeamia kwenye mitandao, mitandao mingi inatumika kutoa habari mbali mbali kama ilivyo magazeti, lakini mtandao ni zaidi ya gazeti, maana inaweza kutoa habari kwa maandishi, picha, video, sauti na pia inatumika kwenye mifumo *application* mbali mbali kwenye kukusanya *data* na kuweza kuzikata na kutoa taarifa. Hivyo basi kurasa ya mtandao inaweza ikawa na vichwa vya habari *(heading)*, aya *(paragraph)*, orodha *(list)*, Picha, video, sauti, fomu za kukusanya taarifa, jedwali na mengineo.


### Vifaa Unavyopaswa Kuwa Navyo
Kimsingi ni kifaa kimoja tu ambacho ni Kompyuta basi. Ni kompyuta yeyote ile yenye uwezo wa kutengeneza, kutunza na kufungua *file*. 

### Lengo ni Nini
Lengo nataka ujue kutengeneza kurasa za mtandao. Hivyo basi ukimaliza tu kusoma na kufanya kile nitakachokwambia utaweza kufanikiwa kutengeneza kurasa yako ya mtandao. Hata kama unataka kuwa *professional* inakupasa uanze chini, pole pole ukipanda, cha msingi unatakiwa uelewe mambo ya msingi kisha uyashike, ukiyashika yanakua kama vile kunywa maji. Ukweli mambo ya msingi yanapaswa yawe ndani ya damu.

### Mambo ya Msingi ya HTML 
*HTML* ni nini?
HTML ni kifupi cha maneno *Hypertext Markup Language* ni lugha ya kompyuta inayotumia *tag* kutengeza muundo wa kurasa za mtandao ili zilete maana na kufikisha ujumbe uliokusudiwa kwa ufanisi. 

Unajua mitandao mingi inatumika kutoa habari mbali mbali kama ilivyo magazeti, lakini mtandao ni zaidi ya gazeti, maana inaweza kutoa habari kwa maandishi, picha, video, sauti na pia inatumika kwenye mifumo *application* mbali mbali kwenye kukusanya *data* na kuweza kuzichakata na kutoa taarifa. Hivyo basi kurasa ya mtandao inaweza ikawa na vichwa vya habari *(heading)*, aya *(paragraph)*, orodha *(list)*, Picha, video, sauti, fomu za kukusanya taarifa, jedwali na mengineo.


Hivyo kazi kubwa ya *HTML* ni kuweka hivyo vitu kwenye mpangiliao unaofaa ili *browser* iweze kuwasilisha kwa yule anayetembelea kurasa hiyo.

Hivyo basi *HTML* ndio lugha mama kwenye mtandao, yaani Duniani hakuna mtandao wowote uliotengenezwa bila ya kutumia  HTML. ambavyo kama tutakavyoweza kuona.

Kitu cha msingi ni kwamba *HTML* sio *programing language* yaani sio lugha inayotumika kuipa maelekezo Kompyuta. Hii ni *markup language* ni lugha ya alama ambazo zinaweza kutafsiriwa na *browser*. HTML inatumia alama kuzipa maana na mantiki sehemu za kurasa. hii inawezesha sehemu fulani ya kurasa kuonekana tofauti na nyingine.


# HTML Element
Kwenye maisha yetu ya kila siku tunakutana na *documents* mbalimbali kama vile magazeti, fomu mbalimbali, risiti, mikataba, vitabu na majarida mengine. Pia tuna kutana na taarifa zilizo kuwa kwenye mfumo wa sauti kama miziki, hotuba na kumbukumbu mbalimbali, tunakutana na video zilizobeba movies na kumbukumbu mbalimbali na wakati mwingine matukio mubashara.

Hivyo basi tovuti nyingi ni kama toleo la kidigitali za hivyo vitu vilivyotajwa hapo juu, maana yake unaweza ukasoma magazeti habari zilezile kwenye mtandao kama vile zilivyo kwenye gazeti au ukaangalia movie kama kwenye deki au kusikiliza muziki kama kwenye radio au unaweza kujaza form ya maombi ya mkopo kama vile unavyojaza fomu kwenye kaunta ya benki. 

Swali kubwa linakuja tunatengenezaje hivyo vitu mbali mbali, tunatumia nini kutengeneza, tunajuaje hii ni haya, hii ni video, hiki ni kichwa cha habari hapa ndio tunakutana HTML element mbalimbali.



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


# Kurasa yako ya kwanza
HTML documents ni file la kawaida lenye maneno yaani *plain text* ambalo linahifadhiwa kwa kikoho cha .html badala ya .txt. Unahitaji programu ya kuandikia maneno *plaint text editor* ambayo umezoea kutumia kama vile notepad na notepad++. Mimi hapa nitatumia notepad na wale wanaotumia Mac wanaweza kutumia TextWrangler. Tafadhali usitumie Microsoft Words kwa kuwa yenyewe ina vitu ambavyo siyo rafiki kwa HTML au programming ya aina yeyote.




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
    <!-- Hii ni comments inaweza kukaa sehemu yeyote -->
    
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
      <!-- 
       Hii ni comments inaweza 
       kukaa sehemu yeyote 
       -->
    
    <p>Ila mwalimu amenitoa shaka ya kwamba atatuelekeza hayo yote huko mbele.

    Yaani nikimaliza mafunzo haya nitakua najua A to Z</p>
    <img src="images/firefox-icon.png" alt="My test image">

  </body>
</html>
```
Hongera sana kwa kutengeneza kurasa yako ya kwanza lakini naona unashangaa sana kuhusu alama ambazo uzielewi ila baada ya muda mfupi utaelewa hivyo vyote. Hapa, kuna vitu vifuatavyo vya msingi ambavyo vinaunda hii kurasa. Uzuri ni kwamba kurasa zote duniani zina hivi vitu vya msingi.

## Maelezo Kuhusu Element Zilizotumika

1. `<!DOCTYPE html>` - Kwa kawaida pale *browser* inapopokea faili la HTML haijui  limeundwa na toleo gani la HTML . Hivyo ni vyema kuiambia browser toleo lilotumika kuunda ilo faili kwa kuweka `<!DOCTYPE html>` kwenye mstari wa kwanza kabisa kabla ya vitu vingine vyote, yenyewe inaonyesha kanuni zipi za *HTML* ulizotumia kutengeneza kurasa yako. Mfano hii yetu ni *HTML5* ambayo ndio teknolojia mpya kabisa inayo tumika hivi sasa.

   Ukiangalia kurasa za zamani utaona kitu kama hiki lakini usitumie kwa sasa nimekuonyesha ili uweze kujua maana yake nini pale unaposoma HTML iliyotengene zamani
   ```html 
   <!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01//EN" "http://www.w3.org/TR/html4/strict.dtd"> ```
   ```



2. `<html></html>` —  `<html>` *element*. huu ni mzizi wa *element* zote *(root element)*. Kurasa zote za mtandao lazima zianze na  `<html>` na kumalizikia na `</html>`.


3. Karibu kila kurasa ya HTML ina sehemu mbili. *body* ndio maudhui kuu ya ukurasa, hii ndio sehemu inayoonekana na mtumiaji, ndio inayobeba maandishi, picha, majedwali na kadhalika. *head* huja kabla ya 'mwili' (juu?). Hapo ndipo unaweka habari juu ya kurasa yako ambapo haviendi mwilini na vichache sana mtumiaji anaviona, hii aka yake ni 'meta-'. Vitu kama ni aina gani ya mkusanyiko wa herufi, habari za mitindo inayotumika na jina la hii kurasa kama inavyosomeka na browser. Tutaangalia kwa undani head na body ndani yake zinabeba nini.

4. `<head></head>`. Hii ni ` <head>` *element*. Hii ni sehemu ambayo unaitumia kuweka vitu vyote ambavyo sio sehemu ya maudhui yako. au vile ambavyo vinatakiwa kwenye kurasa yako lakini mtumiaji wa mtandao hatakiwi kiviona. Hivi ni vitu kama vile *keywords* ambavyo vinaitajika kwenye *search engine* kama google, *CSS* kwa ajili ya kulemba na kuipa mwonekano mzuri kurasa zako. hivi ni vitu ambavyo utajifunza baadae.

5. `<meta charset="utf-8">`. Hii inakaa ndani ya *head* unaona kwamba unatumia meta element pamoja na charset attribute ili kuiambia browser umetumia herufi za kundi gani. Hii inahitajika ili kuzitaarifu *browser* za watumiaji wako kwamba kurasa yako inaelewa lugha karibu zote za duniani yaani zikiwemo kingereza, kifansa, kiswahili, kiyahudi, kichina na kiarabu. usipoiweka hii maandishi yako yanaweza yasionekane vizuri. anagalia uchawi wako hapa ni `charset="utf-8"`. Ingawa kuna makundi mengi ya *charset* inashauliwa wakati wote utumie `utf-8`. vilevile unaweza ukaiweka kama hivi  ` <meta http-equiv="Content-Type" content="text/html; charset=utf-8">`

6. `<title></title>`. Hii `<title>` *element* inaweka jina la kurasa yako. Jina ili linatumika kwenye *tab* na *bookmark/favorite*

   Kuna vitu vingine vingi muhimu vinaingia hapo ambapo tutaviona huko mbele.

7. `<body></body>` Hii `<body>` *element*  ni sehemu ambayo unajimwaga. unaweka vitu vyote ambavyo unataka mtumiaji wako avione. vitu kama vile vichwa vya habari, *link*, aya, video, gemu, orodha, jedwali, sauti, picha na mengineyo. Kwenye waraka huu nitakueleza yote hayo unayawekaje.

8. `<h1></h1>` Kila habari ni lazima iwe na kichwa cha habari hivyo hii inatumika kuweka kichwa cha habari kwenye taarifa yako

9. `<p></p>`  habari inakua imepangika kwenye haya mbali mbali 

10. Lebo ya `<img>` hutumiwa kuweka picha kwenye ukurasa wa HTML.

Bonasi

How to choose Domain 

how to by hosting

how to choose SSL



