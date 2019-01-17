
# Vidokezo vya kuandika kurasa ya HTML inayo pakua (*loading*) kwa haraka

https://developer.mozilla.org/en-US/docs/Learn/HTML/Howto/Author_fast-loading_HTML_pages

Videkezo hivi vimetokana na ujuzi wa kawaida na majaribio




An optimized web page not only provides for a more responsive site for your visitors but also reduces the load on your web servers and Internet connection. This can be crucial for high volume sites or sites which have a spike in traffic due to unusual circumstances such as breaking news stories.

Optimizing page load performance is not just for content which will be viewed by narrowband dial-up or mobile device visitors. It is just as important for broadband content and can lead to dramatic improvements even for your visitors with the fastest connections.

TipsEditSection
Reduce page weightSection
Page weight is by far the most important factor in page-load performance.

Reducing page weight through the elimination of unnecessary whitespace and comments, commonly known as minimization, and by moving inline script and CSS into external files, can improve download performance with minimal need for other changes in the page structure.

Tools such as HTML Tidy can automatically strip leading whitespace and extra blank lines from valid HTML source. Other tools can "compress" JavaScript by reformatting the source or by obfuscating the source and replacing long identifiers with shorter versions.

Minimize the number of filesSection
Reducing the number of files referenced in a web page lowers the number of HTTP connections required to download a page, thereby reducing the time for these requests to be sent, and for their responses to be received.

Depending on a browser's cache settings, it may send a request with the If-Modified-Since header for each referenced file, asking whether the file has been modified since the last time it was downloaded. Too much time spent querying the last modified time of the referenced files can delay the initial display of the web page, since the browser must check the modification time for each of these files, before rendering the page.

If you use background images a lot in your CSS, you can reduce the number of HTTP lookups needed by combining the images into one, known as an image sprite. Then you just apply the same image each time you need it for a background and adjust the x/y coordinates appropriately. This technique works best with elements that will have limited dimensions, and will not work for every use of a background image. However, the fewer HTTP requests and single image caching can help reduce page-load time.

Use a Content Delivery Network (CDN)Section
For the purposes of this article, a CDN is a means to reduce the physical distance between your server and your visitor. As the distance between your server origin and visitor increases, the load times will increase. Suppose your website server is located in the United States and it has a visitor from India; the page load time will be much higher for the Indian visitor compared to a visitor from the US.

A CDN is a geographically distributed network of servers that work together to shorten the distance between the user and your website. CDNs store cached versions of your website and serve them to visitors via the network node closest to the user, thereby reducing latency.

Further reading:

Understanding CDNs
Reduce domain lookupsSection
Since each separate domain costs time in a DNS lookup, the page load time will grow along with the number of separate domains appearing in CSS link(s) and JavaScript and image src(es).

This may not always be practical; however, you should always take care to use only the minimum necessary number of different domains in your pages.

Cache reused contentSection
Make sure that any content that can be cached, is cached, and with appropriate expiration times.

In particular, pay attention to the Last-Modified header. It allows for efficient page caching; by means of this header, information is conveyed to the user agent about the file it wants to load, such as when it was last modified. Most web servers automatically append the Last-Modified header to static pages (e.g. .html, .css), based on the last-modified date stored in the file system. With dynamic pages (e.g. .php, .aspx), this, of course, can't be done, and the header is not sent.

So, in particular, for pages which are generated dynamically, a little research on this subject is beneficial. It can be somewhat involved, but it will save a lot in page requests on pages which would normally not be cacheable.

More information:

HTTP Conditional Get for RSS Hackers
HTTP 304: Not Modified
HTTP ETag on Wikipedia
Caching in HTTP
Optimally order the components of the pageSection
Download page content first, along with any CSS or JavaScript that may be required for its initial display, so that the user gets the quickest apparent response during the page loading. This content is typically text, and can, therefore, benefit from text compression in transit, thus providing an even quicker response to the user.

Any dynamic features that require the page to complete loading before being used, should be initially disabled, and then only enabled after the page has loaded. This will cause the JavaScript to be loaded after the page contents, which will improve the overall appearance of the page load.

Reduce the number of inline scriptsSection
Inline scripts can be expensive for page loading since the parser must assume that an inline script could modify the page structure while parsing is in progress. Reducing the use of inline scripts in general, and reducing the use of document.write() to output content in particular, can improve overall page loading. Use modern AJAX methods to manipulate page content for modern browsers, rather than the older approaches based on document.write().

Use modern CSS and valid markupSection
Use of modern CSS reduces the amount of markup, can reduce the need for (spacer) images, in terms of layout, and can very often replace images of stylized text -- that "cost" much more than the equivalent text-and-CSS.

Using valid markup has other advantages. First, browsers will have no need to perform error-correction when parsing the HTML (this is aside from the philosophical issue of whether to allow format variation in user input and then programmatically "correct" or normalize it; or whether, instead, to enforce a strict, no-tolerance input format).

Moreover, valid markup allows for the free use of other tools which can pre-process your web pages. For example, HTML Tidy can remove whitespace and optional ending tags; however, it will refuse to run on a page with serious markup errors.

Chunk your contentSection
Tables for layouts are a legacy method that should not be used anymore. Layouts utilizing floats, positioning, flexbox, or grids should be used instead.

Tables are still considered valid markup but should be used for displaying tabular data. To help the browser render your page quicker, you should avoid nesting your tables.

Rather than deeply nesting tables as in:

<table>
  <table>
    <table>
          ...
    </table>
  </table>
</table>
use non-nested tables or divs as in

<table>...</table>
<table>...</table>
<table>...</table>
See also: CSS Flexible Box Layout and CSS Grid Layout specifications.

Minify and compress SVG assetsSection
SVG produced by most drawing applications often contains unnecessary metadata which can be removed. Configure your servers, apply gzip compression for SVG assets.

Minify and compress your imagesSection
Large images cause your page to take more time to load. Consider compressing your images before adding them to your page. Online tools like Compress Jpeg, Tiny PNG and many more tools are available online. You can use offline tools too like photoshop and others.

Specify sizes for images and tablesSection
If the browser can immediately determine the height and/or width of your images and tables, it will be able to display a web page without having to reflow the content. This not only speeds the display of the page but prevents annoying changes in a page's layout when the page completes loading. For this reason, height and width should be specified for images, whenever possible.

Tables should use the CSS selector: property combination:

table-layout: fixed;
and should specify widths of columns using the <col> and the <colgroup> elements.

Choose your user-agent requirements wiselySection
To achieve the greatest improvements in page design, make sure that reasonable user-agent requirements are specified for projects. Do not require your content to appear pixel-perfect in all browsers, especially not in down-version browsers.

Ideally, your basic minimum requirements should be based on the consideration of modern browsers that support the relevant standards. This can include recent versions of Firefox, Internet Explorer, Google Chrome, Opera, and Safari.

Note, however, that many of the tips listed in this article are common-sense techniques which apply to any user agent, and can be applied to any web page, regardless of browser-support requirements.

Use async and defer, if possibleSection
Make the JavaScript scripts such that they are compatible with both the async and the defer and use async whenever possible, especially if you have multiple script tags.

With that, the page can stop rendering while JavaScript is still loading. Otherwise, the browser will not render anything that is after the script tags that do not have these attributes.

Note: Even though these attributes do help a lot the first time a page is loaded, you should use them but not assume they will work in all browsers. If you already follow all JavaScript best practices, there is no need to change your code.

Example page structureEditSection
· HTML

· HEAD
· LINK ...
CSS files required for page appearance. Minimize the number of files for performance while keeping unrelated CSS in separate files for maintenance.
· SCRIPT ...
JavaScript files for functions required during the loading of the page, but not any DHTML that can only run after page loads.
Minimize the number of files for performance while keeping unrelated JavaScript in separate files for maintenance.
· BODY
· User visible page content in small chunks (tables/divs) that can be displayed without waiting for the full page to download.
· SCRIPT ...
Any scripts which will be used to perform DHTML. DHTML script typically can only run after the page has completely loaded and all necessary objects have been initialized. There is no need to load these scripts before the page content. That only slows down the initial appearance of the page load.
Minimize the number of files for performance while keeping unrelated JavaScript in separate files for maintenance.
If any images are used for rollover effects, you should preload them here after the page content has downloaded.
Related LinksEditSection
Book: "Speed Up Your Site" by Andy King
The excellent and very complete Best Practices for Speeding Up Your Web Site (Yahoo!)
Tools for analyzing and optimizing performance: Google PageSpeed Tools
Paint Flashing Tool
Document Tags and Contributors
 Tags:  Advanced Guide HTML NeedsUpdate Performance Web
 Contributors to this page: SphinxKnight, chrisdavidmills, ziyadElon, Harinderpreet, stuartharvie, RafeyIqbalRahman, ishan123456789, abt8601, xfq, andygongea, rfc791, fscholz, Jeremie, kscarfone, Sheppy, dbs, gmerencio, gbrown, haboqueferus, brunoais, teoli, ethertank, tolbon, leo89, tw2113, inma_610, xaky, Shz, JaredWBurt, alicethomas222, peterson.victor222, Mgjbot, Carrie zhxj, Ptak82, Satyr-wayfarer, NickolayBot, Dria, Yworfg, cbiesinger, Nerf, Grauw, CitizenK, Jens.B
 Last updated by: SphinxKnight, Dec 11, 2018, 11:05:04 PM
Learn the best of web development
Get the latest and greatest from MDN delivered straight to your inbox.

E-mail
you@example.com
 Sign up now
Hide Newsletter Sign-up
MDN Web Docs
Web Technologies
Learn Web Development
About MDN
Feedback
 
Mozilla
About
Contact Us
Firefox
  
Other languages:  
Terms Privacy Cookies
© 2005-2019 Mozilla and individual contributors. Content is available under these licenses.
