# CodePens

<p>There are a lot of good problems I have solved in my career that didn't result in a full-fledged, fully functional app.  In fact, most of my use cases as a data analyst require putting in small, succint, but smart functions which can get in and get out before anyone knows we were there.  In that spirit here are a few code pens demonstrating quick, powerful solutions that weren't necessarily full-fledged apps</p>
<br/>

---

<img align="left" alt="HTML5" width="26px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/html/html.png" />
<img align="left" alt="CSS3" width="26px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/css/css.png" />
<img align="left" alt="JavaScript" width="26px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/javascript/javascript.png" />
<img align="left" alt="Git" width="26px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/git/git.png" />
<img align="left" alt="GitHub" width="26px" src="https://raw.githubusercontent.com/github/explore/78df643247d429f6cc873026c0622819ad797942/topics/github/github.png" />
<img align="left" alt="Terminal" width="26px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/terminal/terminal.png" />

<br>
<br>

---

### "How to Find the src URL for a Photo"


<iframe height="700" style="width: 1280px;" scrolling="no" title="How to find the src URL for a photo" src="https://codepen.io/trevor-rapp/embed/powOxgw?default-tab=html%2Cresult&theme-id=dark" frameborder="no" loading="lazy" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href="https://codepen.io/trevor-rapp/pen/powOxgw">
  How to find the src URL for a photo</a> by Trevor Rapp (<a href="https://codepen.io/trevor-rapp">@trevor-rapp</a>)
  on <a href="https://codepen.io">CodePen</a>.
</iframe>

<br/>
<br/>

### CodePen context:

This CodePen was made to answer a StackOverflow question -- [How to get URL of an image in JavaScript](https://stackoverflow.com/questions/32828681/how-to-get-url-of-an-image-in-javascript).  

The specific question was: 

> I'm developing a Chrome extension, and I'm adding an onmouseover handler to each of the images on a page. When the user mouses over an image, it's URL should be stored in a >variable. I know I can easily get the value of the src attribute of the image, but I want the full URL. The src attribute stores the path of the image on the server. For >example, when you right click an image in Google Chrome, you get the "Copy Image URL" option, which copies the image's URL to the clipboard.
>
>Is there any way to achieve this? Thanks.

<br/>

### Project published at: 

[Find the Source URL of a Photo](https://codepen.io/trevor-rapp/pen/powOxgw)

### "Various Regex problems I've had to solve"

<iframe height="700" style="width: 1280px;" scrolling="no" title="" src="https://codepen.io/trevor-rapp/embed/XWgLKWW?default-tab=html%2Cresult&theme-id=dark" frameborder="no" loading="lazy" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href="https://codepen.io/trevor-rapp/pen/XWgLKWW">
  </a> by Trevor Rapp (<a href="https://codepen.io/trevor-rapp">@trevor-rapp</a>)
  on <a href="https://codepen.io">CodePen</a>.
</iframe>

<br/>
<br/>

### CodePen context:

While working as a data-analyst I have had to do a lot of retrieving information from urls.  These are various problems I have had to solve based on my experience.

Country Code: often times different countries have entirely different markets, different web-pages, different promotions, and even different laws that regulate them.  Capturing a change in the country code, often provided in the url, can be used as an event to trigger off of. 

Camel Case: when transporting information from one program to another, especially when dealing with legacy code on an enterprise scale, you can run into different naming conventions (i.e. Sentence Case vs. camelCase vs snake_case).  My particular issue dealt with changing camel cased variables into sentence case.  But to do that I had to be able to tell the computer which character to splice on.  Enter this regex.

File Name: this one was an interesting issue.  I was dealing with code from a third party vendor that I didn't have the option to change. Instead of them creating a button semantically with a `<button></button>` tag they had nested an `<img>` tag (which visibly served as the button...including the words on it...I know :( :( :( ).  The image tag was placed inside a `<div>` tag which was inside an `<a>` tag.  A horrible mess.  Not to mention how was I supposed to select text that actually existed in an image?  Or even better question, how would a blind individual using a screen reader know what the button said?  Ugghhh...  So anyway, to get the information I was able to see the src file had the name of the button as the very last file name in it's file path.  So I used this to select that name so I could pass that as a variable to GTM when some clicked on it.

The specific question was: 

> I'm developing a Chrome extension, and I'm adding an onmouseover handler to each of the images on a page. When the user mouses over an image, it's URL should be stored in a >variable. I know I can easily get the value of the src attribute of the image, but I want the full URL. The src attribute stores the path of the image on the server. For >example, when you right click an image in Google Chrome, you get the "Copy Image URL" option, which copies the image's URL to the clipboard.
>
>Is there any way to achieve this? Thanks.

<br/>




### More Information:
---

\**For more information see my [LinkedIn](https://www.linkedin.com/in/trevor-rapp-042a1037) or return to my [Github](https://github.com/trrapp12)*


