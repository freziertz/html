# hyperlink

Kwa hakika *hyperlink* ndio inafanya mtandao (*web*) uitwe mtandao (*web*). 

Hii ndio inayoruhusu kuunganisha kurasa moja na nyingine au sehemu moja na nyingeine kwenye kurasara hiyohiyo au kuunganisha na vitu vingine kama picha, muziki na video zinazohusiana na kurasa zetu. Pia ikiwemo mitandao mingine au kuunganisha ni mfumo mwingine au file jingine au kitu chochote kinacho ishi kwenye ulimwengu wa mtandao au kupakua file fulani. Kama *web browser* itashindwa kufungua ilo *file* basi itakuuliza ili uchague programu gani ufungulie. au itajalibu kulipakua *download* ili uweze kulishughulikia hapo baadae.

sehemu  yeyote ya mtandao  inaweza kubadilishwa na kuwa kiunganishi (*link*) ambapo inawezesha pale unapo bofya inafanya web browser ikupeleke kwenye anuani ya mtandoa mwingine.

Kurasa ya mtandao inaweza ikawa na viunganishi vingi kuelekea kwenye kurasa nyingine kwenye huo mtandao au kwenda kwenye mitandao mingine

## Nini unatakiwa ujue kabla ya kujifunza *HTML Hyperlink*

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

*Paths* Jina linalowakilisha mahala ya lile *file* unaloliitaji liko wapi kwenye *filesystem* yaani kwenye komputa au *server*

Kwa kawaida *URL* inatumia *path* kupata file. Hii ndio inataja file lako liko wapi kwenye ndanio ya mafaili ya komputa.

### Mfano

Ukiwa unatengeneza mtandao ndani ya komputa yako *(locally)* basi utakuwa na folder moja ambalo ndani yake kutakua na mafaili na mafoda mengine. Hili foda linalobeba mafoda mengine tunaita root folder . Miongoni mwa mafaili yatakayo kuwepo kutakuwa na faili moja ambalo linaitwa *index.html* . Hii *index.html* inakua ndio kurasa yetu ya mbele *(home page/ landing page)*. Hii pia inaweza kutumika kama sehemu ya kutua wakati unaingia kwenye sehemu nyingine *(section)* ya mtandao. 



URLs use paths to find files. Paths specify where in the filesystem the file you are interested in is located. Let's look at a simple example of a directory structure (see the [creating-hyperlinks](https://github.com/mdn/learning-area/tree/master/html/introduction-to-html/creating-hyperlinks) directory.)

![A simple directory structure. The parent directory is called creating-hyperlinks and contains two files called index.html and contacts.html, and two directories called projects and pdfs, which contain an index.html and a project-brief.pdf file, respectively](https://mdn.mozillademos.org/files/12409/simple-directory.png)

The **root** of this directory structure is called `creating-hyperlinks`. When working locally with a web site, you will have one directory that the whole site goes inside. Inside the root, we have an `index.html` file and a `contacts.html`. In a real website, `index.html` would be our home page or landing page (a web page that serves as the entry point for a website or a particular section of a website.).

There are also two directories inside our root — `pdfs` and `projects`. These each have a single file inside them — a PDF (`project-brief.pdf`) and an `index.html` file, respectively. Note how you can quite happily have two `index.html` files in one project as long as they are in different locations in the filesystem. Many web sites do. The second `index.html`would perhaps be the main landing page for project-related information.

- **Same directory**: If you wanted to include a hyperlink inside `index.html` (the top level `index.html`) pointing to `contacts.html`, you would just need to specify the filename of the file you want to link to, as it is in the same directory as the current file. So the URL you would use is `contacts.html`:

  ```html
  <p>Want to contact a specific staff member?
  Find details on our <a href="contacts.html">contacts page</a>.</p>
  ```

- **Moving down into subdirectories**: If you wanted to include a hyperlink inside `index.html` (the top level `index.html`) pointing to `projects/index.html`, you would need to go down into the `projects` directory before indicating the file you want to link to. This is done by specifying the directory's name, then a forward slash, then the name of the file. so the URL you would use is `projects/index.html`:

  ```html
  <p>Visit my <a href="projects/index.html">project homepage</a>.</p>
  ```

- **Moving back up into parent directories**: If you wanted to include a hyperlink inside `projects/index.html` pointing to `pdfs/project-brief.pdf`, you'd have to go up a directory level, then back down into the `pdf` directory. "Go up a directory" is indicated using two dots — `..` — so the URL you would use is `../pdfs/project-brief.pdf`:

  ```html
  <p>A link to my <a href="../pdfs/project-brief.pdf">project brief</a>.</p>
  ```

**Note**: You can combine multiple instances of these features into complex URLs, if needed, e.g. `../../../complex/path/to/my/file.html`.

### Document fragments[Section](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Creating_hyperlinks#Document_fragments)

It is possible to link to a specific part of an HTML document (known as a **document fragment**), rather than just to the top of the document. To do this you first have to assign an `id` attribute to the element you want to link to. It normally makes sense to link to a specific heading, so this would look something like the following:

```html
<h2 id="Mailing_address">Mailing address</h2>
```

Then to link to that specific `id`, you'd include it at the end of the URL, preceded by a hash/pound symbol, for example:

```html
<p>Want to write us a letter? Use our <a href="contacts.html#Mailing_address">mailing address</a>.</p>
```

You can even use the document fragment reference on its own to link to *another part of the same document*:

```html
<p>The <a href="#Mailing_address">company mailing address</a> can be found at the bottom of this page.</p>
```

### Absolute versus relative URLs[Section](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Creating_hyperlinks#Absolute_versus_relative_URLs)

Two terms you'll come across on the Web are **absolute URL** and **relative URL:**

**absolute URL**: Points to a location defined by its absolute location on the web, including [protocol](https://developer.mozilla.org/en-US/docs/Glossary/protocol) and [domain name](https://developer.mozilla.org/en-US/docs/Glossary/domain_name). So for example, if an `index.html` page is uploaded to a directory called `projects` that sits inside the root of a web server, and the web site's domain is `http://www.example.com`, the page would be available at `http://www.example.com/projects/index.html` (or even just `http://www.example.com/projects/`, as most web servers just look for a landing page such as `index.html` to load if it is not specified in the URL.)

An absolute URL will always point to the same location, no matter where it is used.

**relative URL**: Points to a location that is *relative* to the file you are linking from, more like what we looked at in the previous section. For example, if we wanted to link from our example file at `http://www.example.com/projects/index.html` to a PDF file in the same directory, the URL would just be the filename — e.g. `project-brief.pdf` — no extra information needed. If the PDF was available in a subdirectory inside `projects` called `pdfs`, the relative link would be `pdfs/project-brief.pdf` (the equivalent absolute URL would be `http://www.example.com/projects/pdfs/project-brief.pdf`.)

A relative URL will point to different places depending on where the file it is used inside is located — for example if we moved our `index.html` file out of the `projects` directory and into the root of the web site (the top level, not in any directories), the `pdfs/project-brief.pdf` relative URL link inside it would now point to a file located at `http://www.example.com/pdfs/project-brief.pdf`, not a file located at `http://www.example.com/projects/pdfs/project-brief.pdf`.

Of course, the location of the `project-brief.pdf` file and `pdfs` folder won't suddenly change because you moved the `index.html` file — this would make your link point to the wrong place, so it wouldn't work if clicked on. You need to be careful!

## Link best practices[Section](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Creating_hyperlinks#Link_best_practices)

There are some best practices to follow when writing links. Let's look at these now.

### Kanuni za kutengeneza *link*

- Tumia mananeo yanayo eleweka kwa mfano *screen reader* inatumia link kutoka sehemu moja kwenda sehemu nyingine

- *Search engine* inatumia *link* kuanisha au kubainisha *to index* file inazokutana nazo. hivyo ni vyema kutumia maneno muhimu *keywords* kwenye link ili kubainisha nini ulicho link

- Maneno ya link yanatakiwa yajieleze yenyewe

  ***Maneno mazuri:* [Download Firefox](https://firefox.com/)

```html
<p><a href="https://firefox.com/">
  Download Firefox
</a></p>
```

  ***Maneno mabya:* [Click here](https://firefox.com/) to download Firefox

```html
<p><a href="https://firefox.com/">
  Click here
</a>
to download Firefox</p>
```

- Kamwe usirudie maneno ya URL kama sehemu ya link.  Maana haipendezi kuon screen reader inasoma herufi kwa herufi.
- Usitaje neno *link* kwenye maneno yanaunda *link*. Hii haina maana 
- Maneno yawe mafupi kadiri iwezekanavyo ila yawe yamebeba maana
- Hakikisha unatumiza matumizi ya maneno tofauti yanayo kwenda sehemu moja

## Matumizi ya *Relative link*

Tumia relative link ndani ya mtandao wako na tumia absulute link pale unapotaka kulink mtandao au kurasa yako na website nnyingine. 

Kuna gharama ya kutumia absolute link maana mzunguko wake ni mkubwa kwa sababu komputa inaanza kuangalia DNS ya domain kisha ndio inaangalia faili wakati *relative url* haina hizo yenyewe inakwenda moja kwa moja kwenye file.

## Link Ambazo Zinakwenda Kwenye Vitu Ambavyo Sio HTML

Ni vyema kutoa maelezo ya ziada pale unapokwenda kwenye link ambazo sio html ambazo *browser* itataka ku-*download* au kuzi-*stream* kama vile video na muziki. Maana hizi zinatumia sana *bandwith* na kuleta hasara ua kupunguza kazi ya mtandao.

```html
<p><a href="http://www.example.com/large-report.pdf">
  Download the sales report (PDF, 10MB)
</a></p>

<p><a href="http://www.example.com/video-stream/" target="_blank">
  Watch the video (stream opens in separate tab, HD quality)
</a></p>

<p><a href="http://www.example.com/car-game">
  Play the car game (requires Flash)
</a></p>
```

Tumia `download attribute` ambayo inakuwezesha kuweka *default file name* wakati mtumiaji anapo *download*

```html
<a href="https://download.mozilla.org/?product=firefox-latest-ssl&os=win64&lang=en-US"
   download="firefox-latest-64bit-installer.exe">
  Download Latest Firefox for Windows (64-bit) (English, US)
</a>
```

## Active learning: creating a navigation menu[Section](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Creating_hyperlinks#Active_learning_creating_a_navigation_menu)

For this exercise, we'd like you to link some pages together with a navigation menu to create a multi-page website. This is one common way in which a website is created — the same page structure is used on every page, including the same navigation menu, so when links are clicked it gives the impression that you are staying in the same place, and different content is being brought up.

You'll need to make local copies of the following four pages, all in the same directory (see also the [navigation-menu-start](https://github.com/mdn/learning-area/tree/master/html/introduction-to-html/navigation-menu-start) directory for a full file listing):

- [index.html](https://github.com/mdn/learning-area/blob/master/html/introduction-to-html/navigation-menu-start/index.html)
- [projects.html](https://github.com/mdn/learning-area/blob/master/html/introduction-to-html/navigation-menu-start/projects.html)
- [pictures.html](https://github.com/mdn/learning-area/blob/master/html/introduction-to-html/navigation-menu-start/pictures.html)
- [social.html](https://github.com/mdn/learning-area/blob/master/html/introduction-to-html/navigation-menu-start/social.html)

You should:

1. Add an unordered list in the indicated place on one page, containing the names of the pages to link to. A navigation menu is usually just a list of links, so this is semantically ok.
2. Turn each page name into a link to that page.
3. Copy the navigation menu across to each page.
4. On each page, remove just the link to that same page — it is confusing and pointless for a page to include a link to itself, and the lack of a link acts a good visual reminder of what page you are currently on.

The finished example should end up looking something like this:

![An example of a simple HTML navigation menu, with home, pictures, projects, and social menu items](https://mdn.mozillademos.org/files/12411/navigation-example.png)

## Linki ya Barua Pepe *(E-mail links)*

Linki ya barua pepe inaundwa na `<a>` na `mailto:` atribute. Mtumiaji aki-*click* hiyo linki inafungua kurasa ya kutuma *eamil*

```html
<a href="mailto:nowhere@mozilla.org">Send email to nowhere</a>
```

ila unaweza ukaacha wazi sehemu ya email, mtumiaji atajaza anuani ya parua pepe pale anapotaka kutuma



