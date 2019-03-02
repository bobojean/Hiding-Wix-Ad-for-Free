# Before:
![Before](https://raw.githubusercontent.com/CorbsEditor/Hiding-Ads-on-Wix-for-Free/master/Preview/Before.png)
# After:
![After](https://raw.githubusercontent.com/CorbsEditor/Hiding-Ads-on-Wix-for-Free/master/Preview/After.png)

# How to Hide Ads on your Wixsite for Free
First, we need to create an HTML file, what is a HTML file:
HTML is a HyperText Markup Language file format used as the basis of a web page. HTML is a file extension used interchangeably with HTM. HTML is consists of tags surrounded by angle brackets. The HTML tags can be used to define headings, paragraphs, lists, links, quotes, and interactive forms.
But where to put it? You'll need to host your own site somewhere like [Glitch](https://glitch.com/), [Github](https://github.com/), or [creating your own home server](https://www.cloudwards.net/how-to-host-your-own-website/).
If you're already familiar with how hosting works, please move on pass this next section.
# Hosting 

# Setting up your HTML file for your Wixsite
Create `index.html` file if you haven't already. For mobile, make sure to also create a file named `mobile.html`.
Put the following code in the `index.html` file, more will be explained below it: 

```

</head><body>
  <title>My Wix Site</title>


<body>
  <iframe src="https://username.wixsite.com/name" style="position:fixed; top:-50px; left:0px; bottom:0px; right:0px; width:100%; height:105%; border:none; margin:0; padding:0; overflow:hidden; z-index:999999;">
</iframe>  
   
  </body>
    <script type="text/javascript">
<!--
if (screen.width <= 900) {
document.location = "/Mobile.html";
}
//-->
</script>
  


</body></html>
```

Where <title> is, please put the name of your site. <title> is what displays the name in the tab of a web browser.
where <iframe> is, we're going to edit the link that is in the iFrame. Change the username to your Wix username and change the name to what your site is called on Wix. Everything in the iFrame should remain as it is, the coding next to style is what helps remove the ads. 
Please do the same for `mobile.html`:
  
```
<html>
  <title>My Wix Site</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">

  <body>
  
     <iframe src="https://username.wixsite.com/name" style="    position: fixed;    left: 0px;    top: -51px;    width: 100%;    height: 108%;}">
</iframe>  
    
  </body>
</html>
```

After that, you should be done. But how will people get to the site that doesn't show the ad, we need to setup a domain.
# Setting up your own Domain
Setting up a free domain: `.cf .tk .ml .ga .gq`
If you're planning on getting a free domain, you get only get .cf .tk .ml .ga and a .gq domain, .com domains are not free.
To get a free domain, [Freenom](https://www.freenom.com/) offers this.
Setting up a paid domain: `.com .net .org .edu .studio .blog .entertainment` etc...
To get a paid domain, I recommend something like [Namecheap](https://www.namecheap.com/), [GoDaddy](https://www.godaddy.com/), or maybe [Freenom](https://www.freenom.com/).
# Getting Free SSL for your Domain
To get free SSL for your domain, [CloudFlare](https://www.cloudflare.com/partners/getting-started/) is the best choice.
Go [here](https://www.cloudflare.com/partners/getting-started/) to learn how to set it up!


This might be unfinished ._.
