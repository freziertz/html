Habari

Jina langu naitwa Yahaya Frezier

# Who is this book for

If you can answer “yes” to all of these:

1. Do you have access to a computer with a Web browser and a text editor?
2. Do you want to learn, understand, and remember how to create Web pages using the best techniques and the most recent standards

this book is for you.

# Who should probably back away from this book?
1. Are you completely new to computers?
(You don’t need to be advanced, but you should understand folders and files, simple text editing applications, and how to use a Web browser.)
2. Are you a kick-butt Web developer looking for a reference book?
3. Are you afraid to try something different? Would you rather have a root canal than mix stripes with plaid? Do you believe that a technical book can’t be serious if HTML tags are anthropomorphized?

this book is not for you.

# We don’t cover every single HTML element or attribute ever created.
There are a lot of HTML elements and a lot of attributes. we don’t cover them all here. Our focus is on the core HTML elements that matter to you, the beginner, and making sure that you really, truly, deeply understand how and when to use them.

# How the Web Works
May be you ask yourself where is this information come from
how web worked 

When you visit a website, the web server hosting that site could be anywhere in the
world. In order for you to find the location of the web server, your browser will first connect
to a Domain Name System (DNS) server.

# Web Server
Web servers are computers which runs web server software that are constantly connected to the Internet, and are optimized to send web pages out to people who request them. Big company have their own web server but most companies use service from web hosting company for fee which nomally they pay monthly or annually.

Web servers have a full time job on the Internet, tirelessly waiting for requests from Web browsers. What kinds of requests? Requests for Web pages, images, sounds, or maybe even a movie. When a server gets a request for any of these resources, the server finds the resource, and then sends it back to the browser

# Internet service provider


# Browser / Web browser
A web browser (commonly referred to as a browser) is a software application for accessing information on the World Wide Web. Each individual web page, image, and video is identified by a distinct URL, enabling browsers to retrieve and display them on the user's device.



# What does the Web browser do?
You already know how a browser works: you’re surfing around the Web and you click on a linkto visit a page. That click causes your browser to request an HTML page from a Web server, retrieve it, and display the page in your browser window.

But, how does the browser know how to display a page? That’s where HTML comes in. HTML tells the
browser all about the content and structure of the page. Let’s see how that works

Some common **web browser** are Firefox, Internet Explorer, Safari, Chrome, and Opera.


# The Internet Versus the Web

# Network
A network is a collection of computing devices connected to one another to allow the sharing of data. An excellent example of a network is the Internet, which connects millions of people all over the world. 

# IP address
Every computer and device (modem, router, smartphone, cars, etc.) connected
to the Internet is assigned a unique numeric IP address (IP stands
for Internet Protocol). For example, the computer that hosts oreilly.com
has the IP address 208.201.239.100.

# Domain Name System (DNS)
It is the DNS servers that tell your
browser how to find the website.


All those numbers can be dizzying, so
fortunately, the Domain Name System (DNS) was developed to allow us to
refer to that server by its domain name, “oreilly.com”, as well. The numeric
IP address is useful for computer software, while the domain name is more
accessible to humans. Matching the text domain names to their respective
numeric IP addresses is the job of a separate DNS server

the browser in Cambridge contacts
a DNS server in London. The
DNS server then tells the
browser the location of the web
server hosting the site in Paris.

When you connect to the web,
you do so via an Internet Service
Provider (ISP). You type a
domain name or web address
into your browser to visit a site;
for example:
.com,
google.
.uk,
.com.
bbc.co.
microsoft


Your computer contacts a
network of servers called
Domain Name System (DNS)
servers. These act like phone
books; they tell your computer
the IP address associated with
the requested domain name.
An IP address is a number
of up to 12 digits separated
by periods / full stops. Every
device connected to the web
has a unique IP address; it is
like the phone number for that
computer.

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


# Open Source
Open source software is developed as
a collaborative effort with the intent
to make its source code available
to other programmers for use and
modification. Open source programs
are usually available for free.

# IP 4 or IP 6
The IANA, the organization that assigns IP numbers, handed out its last bundle of IP
addresses on February 3, 2011. That’s right, no more ###.###.###.###-style IPs. That
format of IP address (called IPv4) is able to produce 4.3 billion unique addresses,
which seemed like plenty when the Internet “experiment” was first conceived in 1977.
There was no way the creators could anticipate that one day every phone, television,
and object on store shelves would be clamoring for one.
The solution is a new IP format (IPv6, already in the works) that allows for trillions
and trillions of unique IP numbers, with the slight snag that it is incompatible with
our current IPv4-based network, so IPv6 will operate as a sort of parallel Internet to
the one we have today. Eventually, IPv4 will be phased out, but some say it will take
decades.


# Protocal
These standardized methods for
transferring data or documents over a network


# Internet
 is a network of connected computers. The purpose of connecting computers together, of course, is to share
information. There are many ways information can be passed between
computers, including email, file transfer (FTP), and many more specialized
modes upon which the Internet is built. These standardized methods for
transferring data or documents over a network are known as protocols

# web
The Web is a subset of the Internet. It is just one of many ways information can be transferred overnetworked computers

The Web (originally called the World Wide Web, thus the “www” in
site addresses) is just one of the ways information can be shared over the
Internet. It is unique in that it allows documents to be linked to one another
using hypertext links—thus forming a huge “web” of connected information.
The Web uses a protocol called HTTP (HyperText Transfer Protocol).
That acronym should look familiar because it is the first four letters of nearly
all website addresses, as we’ll discuss in an upcoming section

# why computer need to be connected to the network
The purpose of connecting computers together, of course, is to share
information





# HTML

What is HTML
The Language of the Web
HTML is markup language for creating Web pages
HTML stands for Hyper Text Markup Language
HTML is the World Wide Web’s core markup language
HTML describes the structure of a web page
Hypertext Markup Language (HTML) is the standard markup language for creating web pages and web applications.



A basic HTML document looks like this:



<!DOCTYPE html>
<html>
  <head>
    <title>Sample page</title>
  </head>
  <body>
    <h1>Sample page</h1>
    <p>This is a <a href="demo.html">simple</a> sample.</p>
    <!-- this is a comment -->
  </body>
</html>

