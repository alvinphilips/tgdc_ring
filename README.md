# Toronto Game Developer Web Ring.
A simple static site used as a web ring to discover and connect memebers of the Toronto Game Developer community.

If you know how to make a website but have never made a blog, template based [static site generators](https://jamstack.org/generators/) are popular choices, ([Hugo](https://gohugo.io/) is my recomendation), although writing your own custom static site generator can be [dead simple](https://github.com/JUB-Yoush/mywebsite). Static pages can be hosted for free on github.


If you've never done any programming but still want to make a site, [neocities](https://neocities.org/) is very accessible platform to get started with and provides free hosting as well.

## How to join:
### 1. Make sure you qualify:
To qualify to join this webring you:
- Are in or from Toronto or the Greater Toronto Area.
- Are a Game developer or someone who works in Games.
- Have a personal blogs/portfoilio you host (or at least can write arbirary HTML within). This ring isn't for your product/game/company. You can link to those things withtin your site, but the site included has to be about you.

### 2. Fork this repo and add your website:
```js
{
  "name": "Your Name",
  "website": "https://your-website.com",
  "rss": "https://your-website.com/rss.xml", // if your site has one
}
```
### 3. Make a Pull Request 
and wait for me to merge it.
### 4. Add links for the ring in your site:
- Once you're in, include anchor tags on your website to ``https://webring.jaydenpb.net`` with your site's domain as the tag and url params for the next, previous, or random site:
- here's a div you can use as a reference, make sure to replace your site here with your domain (not including the https://).
```html
<div style="display: flex; align-items: center; gap: 8px;">
        <a href="https://webring.jaydenpb.net/#your-site-here?nav=prev">←</a>
        <a href="https://webring.jaydenpb.net/#your-site-here?nav=random" target="_blank">
            <div style="border: 1px solid black;
           display: flex; flex-direction: row;  
            ">
                <img style="width: 65px;" src="https://webring.jaydenpb.net/img/cntower.svg" alt="CS Webring"
                    style="width: 24px; height: auto; opacity: 0.8;" />
                <p style="max-width: 50px; font-size: 16px; font-family:monospace;">
                    TOR GDC RING
                </p>
            </div>
        </a>
        <a href="https://webring.jaydenpb.net/#your-site-here?nav=next">→</a>
    </div>
```
- If you have any specific questions you can [reach out](https://jaydenpb.net/contact/).
