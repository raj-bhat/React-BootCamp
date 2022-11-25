1) Why React is Known As React? 
React is known with name React because this library has very effeective way of constantly changing data.
For ex: if we are working on web page consisting of different component , if data changes in some of the component ,it will be rendered in UI immediately by using internal mechanism. This reaction for constanly changing data is provided as name for this libray.

2. What is Emmet?
Its an essential tool kit of for developers. Which helps to write faster code.
if we take example of Vs code editor which will have this emmet inbuit,provides many shortcut using which we can generate some biler templates.

3.Importance of Doctype
It shows what type of document we are using.
It controls whether the browsers uses "standards" or "quirks" mode to render the document.
All browsers need the doctype.It will work in many browser without this but some will fail. Without the DOCTYPE you are forcing the browsers to render in Quirks Mode.

4.CDN
It refers to content delivery Network.
It helps website on performence (load time)
It caches content in proxy server which are nearer to end user and inturn reduces latency.
Because of this whenever user requests, it can be checked in cdn first and then if its availble we can serve or otherwise can call to server.

5.crossorigin Attribute

It helps us to share the resources from one domain to another domain and also protect end user.
Its comes into picture when you are requesting some thing from different domain.

-values what we have is annoymous and use-credential.

<script src="" crossorigin="annonymous">
* when its annonymous -session, cookies or any browser data are not sent .
* using use-credential: request is sent using some identified data so that you can receive some identified data from browser.

6. Async and defer:
These are the parsing types for script tag under HTML file.Its used for efeeciently load external file.
<script src="script.js"></script>
-Html is started parsing:<\n>
- It encunter script, then here it will start fetching script by blocking html parsing.after fecthing it will even execute the same.
- Only after this Html parsing continues

<script src="script.js" async></script>
async means asynchornusly script will be fetched along with HTML andscript will start executing immediatley.
But in this when script is starting execute Html parsing will be halted. 
It will only continues after script execution is done.


<script src="script.js" defer></script>
here Html parsing is started and along with this script also getting fetched.
Script execution only happen after full Html is parsed.
Because of this script execution will never fail, since Html is parsed completely.


