# hyperlink

hyperlink ndio inafanya mtandao (*web*) uitwe mtandao (*web*). 

Hii ndio inayoruhusu kuunganisha kurasa moja na nyingine au sehemu moja na nyingeine kwenye kurasara hiyohiyo au kuunganisha na vitu vingine kama picha, muziki na video zinazohusiana na kurasa zetu ikiwemo mitandao mingine au kuunganisha ni mfumo mwingine au file jingine au kitu chochote kinacho ishi kwenye ulimwengu wa mtandao au kupakua file fulani. Kama *web browser* itashindwa kufungua ilo *file* basi itakuuliza ili uchague programu gani ufungulie. au itajalibu kulipakua *download* ili uweze kulishughulikia hapo baadae.

sehemu  yeyote ya mtandao  inaweza kubadilishwa na kuwa kiunganishi (*link*) ambapo inawezesha pale unapo bofya inafanya web browser ikupeleke kwenye anuani ya mtandoa mwingine.

Kurasa ya mtandao inaweza ikawa na viunganishi vingi kuelekea kwenye kurasa nyingine kwenye huo mtandao au kwenda kwenye mitandao mingine


## Nini unatakiwa ujue kabla ya kujifunza *HTML Head*
Unatakiwa ujue *Mafunzo ya awali ya HTML* na msingi wa *HTML text*

## Lengo ni nini?
Kujifunza *HTML hyperlink*, dhumuni lake, vitu gani ambavyo vinaweza kuwa hyperlink na hatimaye utajua kuunganisha mafaili mengi pamoja.

## Undani wa *link*
A basic link is created by wrapping the text (or other content, see Block level links) you want to turn into a link inside an <a> element, and giving it an href attribute (also known as a Hypertext Reference , or target) that will contain the web address you want the link to point to.

Kimsingi unatengeneza *link* kwa kuweka maandishi au sehemu unayotaka kuifanya *link* ndani ya `<a>` *element* kisha unatumia *href attribute* ambayo inajulikana kama *Hypertext Reference , or target* ambayo ndio itakua na anuani unayotaka kurasa yako ionyeshe. mfano ni kwenye hii page hap chini

**index.html** 
```html
<!DOCTYPE html>
<html>
 <head>
    <meta charset="utf-8">
    <title>Hii ni sehemu ya title yako</title>
    
  </head>
  <body>
    <h1>Hiki ndio kichwa cha habari</>
    <a href=""http://www.tanzaniaparks.go.tz/">Tanzania National Park</a>
    <p>Hii ndio aya yetu. Aya inaweka kwa kutumia tag ya p ikimaanisha <strong>paragraph</strong></p>
    
  </body>
</html>
```
  
*Attribute* nyingine ambayo unaweza kutumia kwenye link ni *title* hii inakuwa na maelezo ya ziada kuhusiana na hiyo *link* ambapo mtumiaji akiweka kasa kwenye hiyo link atapata hayo maelezo kama *Tooltip*.

**index.html** 
```html
<!DOCTYPE html>
<html>
 <head>
    <meta charset="utf-8">
    <title>Hii ni sehemu ya title yako</title>
    
  </head>
  <body>
    <h1>Hiki ndio kichwa cha habari</>
    <a href="http://www.tanzaniaparks.go.tz/" title="Sehemu muafaka kutafuta hapari kuhusina na hifadhi za wanyama tanzania">Tanzania National Park</a>
    <p>Hii ndio aya yetu. Aya inaweka kwa kutumia tag ya p ikimaanisha <strong>paragraph</strong></p>
    
  </body>
</html>
```
### block level link
Unaweza kuweka link kwenye *block level element* kama vile *image* kwa kuiweka katikati ya `<a></a>` *tags*

**index.html** 
```html
<!DOCTYPE html>
<html>
 <head>
    <meta charset="utf-8">
    <title>Hii ni sehemu ya title yako</title>
    
  </head>
  <body>
    <h1>Hiki ndio kichwa cha habari</>
     <a href="http://www.tanzaniaparks.go.tz//">
  <img src="twiga.png" alt="pichwa ya twiga ikiwakilisha mbuga zetu">
</a>
    <a href=""http://www.tanzaniaparks.go.tz/" title="Sehemu muafaka kutafuta hapari kuhusina na hifadhi za wanyama tanzania">Tanzania National Park</a>
    <p>Hii ndio aya yetu. Aya inaweka kwa kutumia tag ya p ikimaanisha <strong>paragraph</strong></p>
    
  </body>
</html>
```
## URLs na paths
Ukitaka kuelewa vizuri kuhusiana na link ni vyema ukajua maana ya url

### URL
*A URL, or Uniform Resource Locator* ni maneno yanayo tambulisha au fafanua kitu fulani kinapatikana wapi kwenye mtandao. 
kwa mfano mtandao wa Tanapa unapatika kwa anuani hii http://www.tanzaniaparks.go.tz

### Path
Paths inataja file lile unaloliitaji liko wapi kwenye filesystem yaani kwenye komputa au server  

### Kanuni za kutengeneza *link*
* Tumia mananeo yanayo eleweka kwa mfano *screen reader* inatumia link kutoka sehemu moja kwenda sehemu nyingine
* *Search engine* inatumia *link* kuanisha au kubainisha *to index* file inazokutana nazo. hivyo ni vyema kutumia maneno muhimu *keywords* kwenye link ili kubainisha nini ulicho link
  




