---
theme: default
background: https://source.unsplash.com/NzERTNpnaDw/1920x1080/
class: text-center
highlighter: shiki
lineNumbers: false
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
drawings:
  persist: false
transition: slide-left
title: A history of front-end
mdc: true
---

# A short history of front-end

<div class="text-3xl">
Or, what has changed while I've been building web sites
</div>

---
preload: false
---
# There was so much we didn't have


<div class="flex flex-wrap justify-between w-8/12 mt-20 gap-y-6">
  <div
    v-motion
    :initial="{ x: 3000, y: 3000 }"
    :enter="{
      x: 0,
      y: 0,
      transition: {
        delay: 500,
        type: 'spring',
        damping: 15,
        mass: 0.5,
      },
    }"
    class="basis-1/3">
    <pre class="text-sm">border-radius</pre>
  </div>

  <div
    v-motion
    :initial="{ x: 3000, y: 3000 }"
    :enter="{
      x: 0,
      y: 0,
      transition: {
        delay: 1000,
        type: 'spring',
        damping: 15,
        mass: 0.5,
      },
    }"
    class="basis-1/3">
    <pre class="text-sm">flexbox</pre>
  </div>

  <div
    v-motion
    :initial="{ x: 3000, y: 3000 }"
    :enter="{
      x: 0,
      y: 0,
      transition: {
        delay: 1500,
        type: 'spring',
        damping: 15,
        mass: 0.5,
      },
    }" class="basis-1/3">
    <pre class="text-sm">grid</pre>
  </div>

  <div
    v-motion
    :initial="{ x: 3000, y: 3000 }"
    :enter="{
      x: 0,
      y: 0,
      transition: {
        delay: 2000,
        type: 'spring',
        damping: 15,
        mass: 0.5,
      },
    }" class="basis-1/3">
    <pre class="text-sm">calc()</pre>
  </div>

  <div
    v-motion
    :initial="{ x: 3000, y: 3000 }"
    :enter="{
      x: 0,
      y: 0,
      transition: {
        delay: 2100,
        type: 'spring',
        damping: 15,
        mass: 0.5,
      },
    }" class="basis-1/3">
    <pre class="text-sm">@keyframe</pre>
  </div>
  <div
    v-motion
    :initial="{ x: 3000, y: 3000 }"
    :enter="{
      x: 0,
      y: 0,
      transition: {
        delay: 2200,
        type: 'spring',
        damping: 15,
        mass: 0.5,
      },
    }" class="basis-1/3">
    <pre class="text-sm">height: 80vw</pre>
  </div>
  <div
    v-motion
    :initial="{ x: 3000, y: 3000 }"
    :enter="{
      x: 0,
      y: 0,
      transition: {
        delay: 2300,
        type: 'spring',
        damping: 15,
        mass: 0.5,
      },
    }" class="basis-1/3">
    <pre class="text-sm">box-shadow</pre>
  </div>
  <div
    v-motion
    :initial="{ x: 3000, y: 3000 }"
    :enter="{
      x: 0,
      y: 0,
      transition: {
        delay: 2400,
        type: 'spring',
        damping: 15,
        mass: 0.5,
      },
    }" class="basis-1/3">
    <pre class="text-sm">@font-face</pre>
  </div>
  <div
    v-motion
    :initial="{ x: 3000, y: 3000 }"
    :enter="{
      x: 0,
      y: 0,
      transition: {
        delay: 2500,
        type: 'spring',
        damping: 15,
        mass: 0.5,
      },
    }" class="basis-1/3">
    <pre class="text-sm">&lt;video&gt;</pre>
  </div>
  <div
    v-motion
    :initial="{ x: 3000, y: 3000 }"
    :enter="{
      x: 0,
      y: 0,
      transition: {
        delay: 2550,
        type: 'spring',
        damping: 15,
        mass: 0.5,
      },
    }" class="basis-1/3">
    <pre class="text-sm">&lt;dialog&gt;</pre>
  </div>
  <div
    v-motion
    :initial="{ x: 3000, y: 3000 }"
    :enter="{
      x: 0,
      y: 0,
      transition: {
        delay: 2560,
        type: 'spring',
        damping: 15,
        mass: 0.5,
      },
    }" class="basis-1/3">
    <pre class="text-sm">&lt;svg&gt;</pre>
  </div>
  <div
    v-motion
    :initial="{ x: 3000, y: 3000 }"
    :enter="{
      x: 0,
      y: 0,
      transition: {
        delay: 2570,
        type: 'spring',
        damping: 15,
        mass: 0.5,
      },
    }" class="basis-1/3">
    <pre class="text-sm">&lt;details&gt;</pre>
  </div>
  <div
    v-motion
    :initial="{ x: 3000, y: 3000 }"
    :enter="{
      x: 0,
      y: 0,
      transition: {
        delay: 2580,
        type: 'spring',
        damping: 15,
        mass: 0.5,
      },
    }" class="basis-1/3">
    <pre class="text-sm">&lt;input type="tel"&gt;</pre>
  </div>
  <div
    v-motion
    :initial="{ x: 3000, y: 3000 }"
    :enter="{
      x: 0,
      y: 0,
      transition: {
        delay: 2590,
        type: 'spring',
        damping: 15,
        mass: 0.5,
      },
    }" class="basis-1/2">
    <pre class="text-sm">background:linear-gradient</pre>
  </div>
</div>
<div
    v-motion
    :initial="{ opacity:0 }"
    :enter="{
      opacity:1,
      transition: {
        delay: 3000,
      },
    }" class="mt-6 text-red-800 font-bold">
    And a lot more...
  </div>

<!--
Before CSS3 and HTML5, much of the code we use today - and take for granted - wasn't available. I'm going to talk to you about some of the ways we used to build sites and lay out pages back in the olden days.
-->

---

<div class="flex justify-center">
<img src="/four-yorkshiremen.gif" style="width:60%">
</div>

<!--
I realised when writing this talk that I'd basically become Monty Python's 4 yorkshiremen who can't believe the cushy life of the youth of today.
-->

---

# Frames
<div class="text-l mb-6">
(no <b>not</b> iframes)
</div>

frames.html
<div class="mb-6">
```html {all|2|3|all}
<html>
  <frameset rows ="20%,80%">
    <frame src ="nav.html">
    <frame src = "frame-1.html" name="showframe">
    <frame src="frame-2.html" name="showframe">
  </frameset>
</html>
```
</div>

nav.html
```html {all|1|2}
<a href = "frame-1.html" target="showframe">frame 1</a><br>
<a href = "frame-2.html" target="showframe">frame 2</a>
```

<!--
First of all let's have a chat about frames.

I wrote my first line of html when I was an english literature student who ought not to have been seen dead in the underground college computer room. I made a website on geocities about kids tv programmes - long since lost sadly - but I do remember using frames for my layout. 

it was a way of using just one file for navigation items but without any serverside code.

So we had the frameset element which declared a layout with rows or cols, a bit like the textarea element.

Then inside we could create frame elements which had a src pointing to a different file.

In the navigation file we create links to the other frame files using href and target.
-->

---

<video controls class="w-[700px]">
  <source src="/frames.mp4" type="video/mp4">
</video>

<!--
Here's a quick screencast of what that code looks like in chrome - you can see the ugly border between the frames that we can't override with our css.
-->

---

# Don't try this at home

![Local Image](/deprecated-frames.png)

---

# Table layout

<video controls class="w-[700px]">
  <source src="/lhi-tables.mp4" type="video/mp4">
</video>

<!--
Long before flexbox, and even before float began to be widely available, developers often used tables for layout.
When I first started at Torchbox in 2004 we were moving towards always using CSS (i.e. floats) for layout, but we still had sites that had been built with tables. An example was the local heritage initiative site, which you can see here in the internet archive.

Obviously not at all semantic and terrible for screen readers.
-->

---

# Flash

```html
<OBJECT classid="clsid:D27CDB6E-AE6D-11cf-96B8-444553540000"
 codebase="http://download.macromedia.com/pub/shockwave/cabs/flash/swflash.cab#version=5,0,0,0"
WIDTH=550 HEIGHT=400>
 <PARAM NAME=movie VALUE="intro.swf"> <PARAM NAME=loop VALUE=false> <PARAM NAME=quality VALUE=high> <PARAM NAME=scale VALUE=noborder> <PARAM NAME=bgcolor VALUE=#FFFFFF> <EMBED src="intro.swf" loop=false quality=high scale=noborder bgcolor=#FFFFFF  WIDTH=550 HEIGHT=400 TYPE="application/x-shockwave-flash" PLUGINSPAGE="http://www.macromedia.com/shockwave/download/index.cgi?P1_Prod_Version=ShockwaveFlash"></EMBED>
</OBJECT>
```

<!--
These days there is a whole world of options for animating on the web - simple CSS transitions, keyframes, and more complex JavaScript animations using libraries like Greensock.

When I had my first job in web development, if you wanted any animated elements on your website you used flash, which was also often used for very rich interactive content like online games. You created your files in Macromedia Flash and then published them as .swf files which the browser would display.

Above is some code from an old portfolio site where I had a splash page that used flash - unedited. I can't remember why the markup is all capitalised.
-->

---

# Flash demo

<video controls class="w-[500px]">
  <source src="/flash.mp4" type="video/mp4">
</video>

<!--
HTML5 was designed to do away with the need for third pary plugins like flash, and now all browsers will block flash content by default as it is insecure. However, there are browser extensions you can still find to play old flash files, so you can have the treat of seeing the intro to my portfolio website from 2000.
-->

---

# Before border-radius

<video controls class="w-[700px]">
  <source src="/asthma.mp4" type="video/mp4">
</video>

<!--
The border-radius property was part of the CSS3 spec which was released in 2005 - but as with all CSS there was a significant lag between the time it was released, and when it was widely supported enough to use. As an aside, cross browser support was generally a much harder job in the early 2000s, as the differences between Internet Explorer and Netscape, and later Mozilla, were much more significant. Here's another old Torchbox website - Asthma UK, from 2006.

You can see from this screencast that they love their elements with rounded corners, but without border-radius we had to use background images to create each and every single one.
-->

---

# Before Sass and BEM

```css {all|3|38|26|all} {maxHeight:'300px'}
/* 
page layout
Nick Lee
2005-09-20
*/

#wrapper {
	position: relative;
	width: 776px;
	text-align: center;
	margin: 0 auto;
}

/* HEADER */

#header {
	padding: 0px 20px 0px 23px;
	min-height:104px;
	width: 733px;
	background: url(/web/20070709155110im_/http://www.asthma.org.uk/display_images/header_bg_root.gif) no-repeat;
	text-align: left;
	/*overflow:hidden;*/
}

#header-content {
	float:left;
	margin-bottom: 0px !important;
}

#logo {
	position:relative;
	float: right;
	margin: 23px 5px 0px 0px !important;
	padding:0px !important;
	list-style-type: none;
	list-style-image: none;
}
#logo-image li{
	list-style-type: none;
	list-style-image: none;	
}
#logo ul {
	list-style-image: none;
	margin: 0px !important;
	padding:0px !important;
}

#helpline {
	float: left;
	margin: 4px 0px 0px 0px;
}

.header_column {
	float: left;
	border-left: 1px dotted #a7a7a7;
	padding: 0px 10px 0px 8px;
	margin: 20px 0px 0px 0px;
	font-size: 0.9em;
	font-weight: bold;
	line-height: 1.6em;
	width: 125px;
}

#search {
	background: url(/web/20070709155110im_/http://www.asthma.org.uk/display_images/nav/search2.gif) no-repeat 21px 0;
	height: 32px;
	float:left;
	padding-top:0px;
}

#nav-bar form {
	position: relative;
	top: 3px;
	padding: 0px 0px 0px 13px;
}

#nav-bar input {
	margin-top:3px;
	margin-bottom:0px;
	width:100px;
}

#breadcrumb { 
	font-size: 0.9em;
	text-align: left;
	margin: 5px 0px 0px 20px;
}

/* MAIN CONTENT AREA */

#content {
	margin: 0px;
	padding: 0px 18px 2px 18px;
	text-align: left;
	background: url(/web/20070709155110im_/http://www.asthma.org.uk/display_images/main_bg_root.gif);
}

#content_theme {
	padding: 17px 0px 0px 0px;
	height: 100%;
	margin: 0px;
}

#left-column{
	float: left;
	width: 150px;
	padding: 0px 0px 0px 16px;
	margin: 0 0 0 0;
	border-right: 1px dotted #a7a7a7;
}

.left-column-content {
	padding:10px 10px 0px 10px;
}

#main-column {
	float: left;
	width: 362px;
	margin: 10px 20px 0px 20px;
}

#main-column-wide {
	float: left;
	width: 532px;
	margin: 10px 0px 0px 20px;
}

#main-column-wide #main-column {
	width: 358px;
}

#main-column-full {
	float: left;
	width: 682px;
	margin: 10px 0px 0px 20px;
}

#right-col {
	float: left;
	width: 150px;
	padding: 0px;
	margin: 80px 0px 0px 0px;
}

/*FOOTER*/

#footer {
	background-image: url(/web/20070709155110im_/http://www.asthma.org.uk/display_images/main_bg_root.gif);
	padding: 0px 18px 0px 18px;
	text-align: left;
	color: #999999;
	position: relative;
	margin: 0px; 
} 

#footer_inner { 
	background: url(/web/20070709155110im_/http://www.asthma.org.uk/display_images/footer_logo_root.gif) no-repeat top left;
	padding: 49px 13px 0px 13px;
	margin: 0px;
}

#footer_inner_bottom {
	background: url(/web/20070709155110im_/http://www.asthma.org.uk/display_images/main_bg_root.gif) -13pt 0pt;
	padding: 10px 0px;
}

#footer-updated {
	float:left;
	position:relative;
	padding: 0px 0px 0px 13px;
}



#copyright {
	float:right;
	position:relative;
	padding: 0px 13px 0px 0px;
}

#footer-close {
	clear:both;
	height: 35px;
	background: url(/web/20070709155110im_/http://www.asthma.org.uk/display_images/footer_main_bg_root.gif) 0% 100%;
	margin: 0px 0px 15px 0px;
	padding:0px;
}

#footer_logo { 
	clear: both;
	text-align: right;
	width: 100%;
	margin: 0px;
}

.footer-icon {
	vertical-align: middle;
}
```

<!--
We started using Sass widely at Torchbox in about 2011 - I remember because I had to learn it on returning from maternity leave after my second son was born. Sass gave us a componentised approach to our CSS files, using imports. But before Sass, we tended to have separate CSS files for just a few key areas of the site: generic html definitions, the site structure, the navigation, and one for each page.

Here you can see some structural code from asthma uk. (look who wrote it!). You can it has id selectors and nested code which we'd never use these days, but overall it's actually not horrible at all to read.

You can see that our layout is done using 'floats'.
-->

---

# A tangled web

But before BEM our code could quickly get quite complex

```css {all} {maxHeight:'300px'}
header[role="banner"] {
    position: relative;
    width: 92%;
    background: rgba(255, 255, 255, 0.6);
    font-family: sans-serif;
    font-size: 0.9375em;
    border-top: 6px solid #21B259;
    margin: 0 auto;
    padding: 1em 0 1.5em 0; }
    @media screen and (min-width: 768px) {
      header[role="banner"] {
        padding-top: 1.2em;
        padding-bottom: 2.9em;   }
}
      @media screen and (min-width: 980px) {
        header[role="banner"] {
          width: 980px;
          border-top-width: 10px;   }
}
        header[role="banner"] img {
          height: 40px; }
          @media screen and (min-width: 768px) {
            header[role="banner"] img {
              height: 68px;
              float: left;   }
}
    header[role="banner"] nav a {
      color: #8E9190;
      text-decoration: none; }
      header[role="banner"] nav a:hover {
        border-bottom: 2px solid #8E9190; }
    header[role="banner"] h1 {
      margin-left: 2.04082%; }
      @media screen and (min-width: 1024px) {
        header[role="banner"] h1 {
          margin-left: 8.16327%;   }
}
    header[role="banner"] nav {
      margin-left: 2.04082%; }
      @media screen and (min-width: 768px) {
        header[role="banner"] nav {
          float: left;
          margin-left: 3em;   }
}
        header[role="banner"] nav ul {
          margin-top: 0.4em; }
          header[role="banner"] nav li {
            display: inline-block;
            margin-right: 1em; }
            @media screen and (min-width: 768px) {
              header[role="banner"] nav li {
                margin-right: 1.7em;   }
}
              header[role="banner"] nav li:first-child {
                display: none; }
                @media screen and (min-width: 768px) {
                  header[role="banner"] nav li:first-child {
                    display: inline-block;   }
}
            header[role="banner"] nav li:nth-child(4),
            header[role="banner"] nav li:nth-child(5),
            header[role="banner"] nav li:nth-child(6) {
              position: absolute;
              right: 0;
              margin-right: 2.04082%; }
              header[role="banner"] nav li:nth-child(4) {
                top: 2.4em; }
                header[role="banner"] nav li:nth-child(6) {
                  top: 1.2em; }
                  header[role="banner"] nav li:nth-child(5) {
                    top: 3.6em; }
                    @media screen and (min-width: 980px) {
                      header[role="banner"] nav li:nth-child(4),
                      header[role="banner"] nav li:nth-child(5),
                      header[role="banner"] nav li:nth-child(6) {
                        position: relative;
                        margin-right: 1.7em;
                        top: 0;   }
}
```

<!--

Here's a sample of some CSS from Upshot in 2014. We are now using media queries to support different screen sizes. But it's a complex app and there are lots of nested CSS rules. The code quickly becomes much harder to edit without overriding lots of other rules and using the !important modifier. Notice how we used the convention of indenting code to show how rules become more specific.

-->

---

# Upshot code today

```css {all} {maxHeight:'300px'}
.badge {
    $root: &;
    background-color: $color--grey-mid;
    color: $color--grey-darkest;
    border-radius: $default-border-radius;
    display: inline-block;
    padding: 0.25em 0.5em;
    text-transform: uppercase;
    vertical-align: middle;

    &--primary {
        @include font-size(s);
        background-color: $color--primary;
        color: $color--white;
    }

    &--secondary {
        @include font-size(s);
        background-color: $color--secondary;
        color: $color--white;
    }

    &--tertiary {
        @include font-size(s);
        background-color: $color--tertiary;
        color: $color--white;
    }

    &--small,
    .list-item__heading &--small {
        @include font-size(xs);
    }
}

```

<!--
It certainly makes you realise just how much BEM (and other css methodologies) have revolutionised our work. I can't tell you how many times easier it is to edit someone else's BEM code, than it was to figure out what was going on in code like that Upshot example.
-->

---

# calc()

<div class="mb-4">
```css

.sidebar {
  float: left;
  width: 300px;
}

.main {
  float: left;
  width: calc(100% - 300px);
}

```
</div>

```css {all} {maxHeight:'200px'}

/* CSS for fixed-fluid layout */

.fixed {
    width: 150px;  /* the fixed width required */
    float: left;
}

.fixed + div {
     margin-left: 150px;  /* must match the fixed width in the .fixed class */
     overflow: hidden;
}


/* CSS to ensure sidebar and content are same height (optional) */

html, body {
    height: 100%;
}

.fill { 
    min-height: 100%;
    position: relative;
}

.filler:after{
    background-color:inherit;
    bottom: 0;
    content: "";
    height: auto;
    min-height: 100%;
    left: 0;
    margin:inherit;
    right: 0;
    position: absolute;
    top: 0;
    width: inherit;
    z-index: -1;  
}

```

<!--
We often use calc() in css to figure out sizes that combine percentate widths with pixel sizes. For example, for a fluid-width site, how would you have a fixed width sidebar, and a main page area that fills the rest of the space? This is also assuming a float-based layout.

With calc() it is easy

Here's the solution suggested in a stack-overflow post in 2012, using margin-left and overflow.

Calc was also brilliant for creating a card layout where your cards needed to be a flexible width but have a fixed gap between - before we had the gap property. We could calculate the width of the card as calc(33% - 15px).

-->

---

# order

```ts {all} {maxHeight:'300px'}
Harvey.attach(breakpoints.mobile, {
  setup: function(){},
  on: function(){
    $('nav').addClass('dl-menuwrapper').dlmenu({
      animationClasses : {
        classin : 'dl-animate-in-2',
        classout : 'dl-animate-out-2'
      }
    });
  },
  off: function(){
    $('nav').removeClass('dl-menuwrapper').removeData();
    $('nav *').removeClass('dl-subview dl-subviewopen');
    $('nav .dl-back').remove();

    // remove width from page content which is needed to keep it constant when showing the mobile menu
    $("body").removeClass("show-mobile-menu");
    $("body, .mobile-content-wrapper").removeAttr("style");
  }
});
Harvey.attach(breakpoints.desktopSmall, {
  setup: function(){},
  on: function(){
    /* Duplicate anything added to this function, into the ".lt-ie9" section below */

    //enable desktop dropdown nav
    desktopNav.apply();
  },
  off: function(){
    //kill desktop dropdown nav
    desktopNav.revoke();
  }
});
```

<!--
The order property in CSS allows us to change the order that flex or grid elements appear on the screen - this can be really handy if we want a display at mobile that has a different ordering of elements to desktop.

Before that we had to use JavaScript to rearrange elements at mobile and deskop - we sometimes used a tool called Harvey that allowed us to run JS code at different media queries. I wasn't able to find an example that was specifically rearranging elements, but here's a little extract of the navigation code in an early iteration of the RCA site. You can see how you might use Harvey to remove an element from one part of the DOM and add it to another.

-->

---
layout: cover
background: https://source.unsplash.com/NzERTNpnaDw/1920x1080/
---

# Conclusion

<div class="text-2xl font-semibold">
<ul>
<li v-click>In many ways front-end development is so much easier than it used to be.</li>
<li v-click>And in others... not so much</li>
</ul>
</div>

<!--
Things that are simple to do now, like a complex layout, or re-ordering items at different screen sizes, that would have entailed lots of head scratching, are just so much easier now. I still pinch myself sometimes at how easy things are compared to when I started out.

But on the other hand, we've created complicated toolchains, single page apps, whole libraries for rending sites with JavaScript alone, which can take several years to master. From that point of view - life used to me so much simpler.
-->
---
align: center
---

![Local Image](/youth-of-today.gif)

<!--
I hope you've enjoyed a little foray into front-end history.
Thanks for listening!
-->

---
