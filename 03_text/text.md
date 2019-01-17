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


