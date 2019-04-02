# Muundo*(Structure)* wa Kurasa na Tovuti

Kurasa ina zana zinazowezesha kutengeneza  sehemu mbalimbali za kurasa au tovuti yako. sehemu hizo ni kama vile sehemu ya juu kabisa *(header)* , menyu *(menu bar)*, sehemu ya pembeni *(side bar)* , sehemu ya katikati ambayo ndio ya habari yenyewe *(main)* na sehemu ya chini *(footer)*.

## Lengo 

ni kujifunza jinsi ya kujenga sehemu mbalimbali za mtandao kwa kutumia *tags* zenye kuleta maana. na jinsi gani ya kutengeneza muundo kamili wa kurasa ya kawaida.

# Sehemu za Msingi za Kurasa 

Kwa kawaida kurasa nyingi zinaonekana tofauti, tofauti kwa macho ya mtumiaji lakini karibu zote zina muundo unaofanana

## Sehemu ya Juu *Header*

Hii ni kipande cha juu kabisa kwenye kurasa ambacho maranyingi kinakua na kichwa cha habari kikubwa na nembo. Maranyingi seehemu hii inakuwa na muonekano sawa kwenye kurasa zote.

## Menyu *Navigation Bar*

Menyu ni sehemu inayobemba linki kuu za mtandao wako. Hii ni sehemu ambayo  inakuwa sawa kwenye kurasa zote. Sio vyema kuweka linki zinazotofautina kwenye kurasa tofauti, pia inawezekana sehemu hii na ile ya *header* zikawa majo ila nayo sio vizuri inapendeza *header* na  menyu zikiwa tofauti.

## Taarifa Yenyewe *(Main Content)*

Hii ni sehemu ile kubwa ya katikati ambayo inabeba maudhui ya kurasa yako. Hapa ndio unapoweka habari, picha na video na kadhalika. hii ni sehemu ya kurasa ambayo kwa hakika inabadilika kulingana na kurasa husika.

Sehemu ya pembeni

Sehemu hii ya pembeni inaweza ikawa upande wa kulia, kushoto au pande zote mbili yaani kulia na kushoto. Mara nyingi sehemu hii inategemea zaidi na maudhui ya kurasa lakini wakati mwingine kwenye baadhi ya tuvuti utakuta inalingana kwenye kila kurasa.

Sehemu ya chini *(Footer)*

Hii ni sehemu ya chini kabisa ya kurasa maranyingi inakuwa na maneno madogomadogo, haki miliki *(copyright notices)* au mawasiliano, na taarifa za ziada kuhusu taasisi yanye hiyo tovuti. Pia linki kwa ajili ya kwnda kwenye kurasa za mitandao ya kijamii na taarifa zingine zihusuyo hiyo taasisi.

A "typical website" could be laid out something like this:

![a simple website structure example featuring a main heading, navigation menu, main content, side bar, and footer.](https://mdn.mozillademos.org/files/12417/sample-website.png)

## HTML kwa muundo wa tovuti

Ikumbukwe kwamba HTML ni kwa ajili ya kutengeneza muundo wa tovuti. Ingawa inawezekana kkwa kutumia CSS ukafanikiwa kutengeneza muundo au muonekano wa mtandao wako ila ilo halikubaliki ni muhimu kutumia alama za HTML zinazoleta maana. Hii ni kwa sababu kwa kuangalia tu  upati habali kamili kumbuka watumiaji wa komputa wako walemavu wa macho ambao hawajui hii rangi gani vile vile machine ambazo zeneyewe hazijali muonekano zinachojali ni maudhui.

HTML ina *element* ambazo zinaleta maana kwenye kurasa alama hizo ni kama zifuatazo

* header: `<header>`.
* navigation bar: `<nav>`.
* main content: `<main>`, with various content subsections represented by `<article>`, `<section>`, and `<div>` elements.
* sidebar: `<aside>`; often placed inside `<main>`.
* footer:`<footer>`

Mfano

```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">

    <title>My page title</title>
    <link href="https://fonts.googleapis.com/css?family=Open+Sans+Condensed:300|Sonsie+One" rel="stylesheet" type="text/css">
    <link rel="stylesheet" href="style.css">

    <!-- the below three lines are a fix to get HTML5 semantic elements working in old versions of Internet Explorer-->
    <!--[if lt IE 9]>
      <script src="https://cdnjs.cloudflare.com/ajax/libs/html5shiv/3.7.3/html5shiv.js"></script>
    <![endif]-->
  </head>

  <body>
    <!-- Here is our main header that is used across all the pages of our website -->

    <header>
      <h1>Header</h1>
    </header>

    <nav>
      <ul>
        <li><a href="#">Home</a></li>
        <li><a href="#">Our team</a></li>
        <li><a href="#">Projects</a></li>
        <li><a href="#">Contact</a></li>
      </ul>

       <!-- A Search form is another commmon non-linear way to navigate through a website. -->

       <form>
         <input type="search" name="q" placeholder="Search query">
         <input type="submit" value="Go!">
       </form>
     </nav>

    <!-- Here is our page's main content -->
    <main>

      <!-- It contains an article -->
      <article>
        <h2>Article heading</h2>

        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Donec a diam lectus. Set sit amet ipsum mauris. Maecenas congue ligula as quam viverra nec consectetur ant hendrerit. Donec et mollis dolor. Praesent et diam eget libero egestas mattis sit amet vitae augue. Nam tincidunt congue enim, ut porta lorem lacinia consectetur.</p>

        <h3>subsection</h3>

        <p>Donec ut librero sed accu vehicula ultricies a non tortor. Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aenean ut gravida lorem. Ut turpis felis, pulvinar a semper sed, adipiscing id dolor.</p>

        <p>Pelientesque auctor nisi id magna consequat sagittis. Curabitur dapibus, enim sit amet elit pharetra tincidunt feugiat nist imperdiet. Ut convallis libero in urna ultrices accumsan. Donec sed odio eros.</p>

        <h3>Another subsection</h3>

        <p>Donec viverra mi quis quam pulvinar at malesuada arcu rhoncus. Cum soclis natoque penatibus et manis dis parturient montes, nascetur ridiculus mus. In rutrum accumsan ultricies. Mauris vitae nisi at sem facilisis semper ac in est.</p>

        <p>Vivamus fermentum semper porta. Nunc diam velit, adipscing ut tristique vitae sagittis vel odio. Maecenas convallis ullamcorper ultricied. Curabitur ornare, ligula semper consectetur sagittis, nisi diam iaculis velit, is fringille sem nunc vet mi.</p>
      </article>

      <!-- the aside content can also be nested within the main content -->
      <aside>
        <h2>Related</h2>

        <ul>
          <li><a href="#">Oh I do like to be beside the seaside</a></li>
          <li><a href="#">Oh I do like to be beside the sea</a></li>
          <li><a href="#">Although in the North of England</a></li>
          <li><a href="#">It never stops raining</a></li>
          <li><a href="#">Oh well...</a></li>
        </ul>
      </aside>

    </main>

    <!-- And here is our main footer that is used across all the pages of our website -->

    <footer>
      <p>©Copyright 2050 by nobody. All rights reversed.</p>
    </footer>

  </body>
</html>
```

- `<main>` Hii iweke moja kwenye kila kurasa, inatakiwa iwekwe mara baada ya `<body>`. Kimsingi haitakiwa kuwekwa ndani ya *element* nyingine.

- `<article>` Hii unazungushia sehemu zile zenye maudhui yanayo husiana ambayo yanaleta maana kamili bila kushirikisha vitu vingine kwenye kurasa. Mfano blog post moja.

- `<section>` Hii inafanana na `<article>` tofauti yake ni kwamba hii inatumika kugawa sehemu moja ya kurasa maudhui yenye kazi moja kwa mfano vichwa vya hapari na ufupisho wake. Ni vyema kuanza kila `<section>` na kichwa cha habari kipya. Vilevile unaweza kuvunja `<article>` kwenye `<section>`  tofauti au `<section>` kwenye `<article>` tofauti kulingana na aina ya maudhui.

- `<header>` ni sehemu ya kichwa cha habari; kama ikiwa ndani ya `<body>` basi hicho kitakua kichwa cha habari kikukuu na ikiwa ndani ya `<section>` au `<article>` hicho kitakua kichwa cha habari cha kidogo kwenye kurasa. Usichanganya hii ni titles na headings

- `<nav>`  *navigation area* :- hii ni sehemu ambayo inuweka link zinazokwenda kwenye kurasa zako sile za msingi. lakini sekondari link hazitakiwi kuwa ndani <nav>. Mara nyingi sehemu hii inafanana

- `<footer>` hii inabeba maudhui yaliyo chini au mwisho wa kurasa yako. sehemu hii mara nyingi inafanana kutoka kurasa na nyingine

## Non Semantic Wrapper

Wakati mwingine unaweza ukawa unahitaji kugawa au kuweka vitu kwenye kundi  fulani kwenye kurasa yako ili uweze kutumia CSS au JavaScript kuboresha kurasa yako lakini ukaona hakuna *element* yeyote yenye kuleta maana unayoweza kutumia. Hivyo *HTML* ina *element* ambazo zinatukima kwenye sehemu hizo. Maeneo kama hayo kuna `<div>` na `<span>` ambazo zinatumika

`<div>`  hii ni block level element ambayo haileti maana yeyote pale inapotumika ila inatumiwa na CSS na JavaScript kwenye kuboresha kurasa yako. Block element  ikiwa inamaana kwamba inatengeneza boksi lenye ulefu na upana

```html
<div class="shopping-cart">
  <h2>Shopping cart</h2>
  <ul>
    <li>
      <p><a href=""><strong>Silver earrings</strong></a>: $99.95.</p>
      <img src="../products/3333-0985/thumb.png" alt="Silver earrings">
    </li>
    <li>
      ...
    </li>
  </ul>
  <p>Total cost: $237.89</p>
</div>
```



`<span>` hii nayo haina maana yeyote pale inapotumika kwenye kurasa yako ila utaitumia kwenye CSS au JavaScript kwenye kuboresha kurasa yako. Hii inaitwa inline element kwa sababu inawekwa kwenye mstari haiko kama boksi maana haina upana au ulefu.

```html
<p>The King walked drunkenly back to his room at 01:00, the beer doing nothing to aid
him as he staggered through the door <span class="editor-note">[Editor's note: At this point in the
play, the lights should be down low]</span>.</p>
```



## Line breaks and horizontal rules

`<br>` Hii unapaswa kuitumia pale unapotaka kutengeneza ufupisho wa sentensi yako kwenye paragraph au pale unapotaka kuluka mstari.

```html
<p>There once was a man named O'Dell<br>
Who loved to write HTML<br>
But his structure was bad, his semantics were sad<br>
and his markup didn't read very well.</p>
```

`<hr>`Hii inatengeneza horizontal rule kwenye kurasa ikimaanisha ni mwisho wa kitu fulani na mwanzo wa kitu kingine. Lakini kwa macho huonekana kama mstari vile.

```html
<p>Ron was backed into a corner by the marauding netherbeasts. Scared, but determined to protect his friends, he raised his wand and prepared to do battle, hoping that his distress call had made it through.</p>
<hr>
<p>Meanwhile, Harry was sitting at home, staring at his royalty statement and pondering when the next spin off series would come out, when an enchanted distress letter flew through his window and landed in his lap. He read it hazily and sighed; "better get back to work then", he mused.</p>
```

Mazoezi

Tengeneza site map yako