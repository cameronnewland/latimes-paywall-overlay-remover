# latimes-paywall-overlay-remover

##Description

Bypasses the Los Angeles Times' paywall overlay and allows the user to scroll the window again.

##Usage

Save the HTML file to your computer, view the HTML file in a web browser, drag the link text to your Bookmarks bar,
then navigate to a paywalled page on the Los Angeles Times' website, and then click the Bookmarklet in your Bookmarks bar.

```javascript
javascript:(function()%7Bvar overlay%3Ddocument.getElementById("reg-overlay")%3Bvar bodyElement%3Ddocument.getElementsByTagName("BODY")%5B0%5D%3Bvar htmlElement%3Ddocument.getElementsByTagName("HTML")%5B0%5D%3Boverlay.parentNode.removeChild(overlay)%3BbodyElement.style.overflow%3D"auto"%3BhtmlElement.style.overflow%3D"auto"%3B%7D)()%3B;
```

Alternately, copy the above code, hit CTRL+D (or &#8984;+D if you're running Mac OS X), click 'Edit', title the bookmark, and paste the above code into the URL field, then click 'Save'.

##Works In

- Chrome

##To Do

- Add support for Firefox
- Test in Firefox

##Legal

Author is in no way associated with the Los Angeles Times or any of its affiliates. The author and the above code are not endorsed by The Los Angeles Times, latimes.com, or the city of L.A., or the Queen of England. Any confusion that might indicate association or endorsement is unintended, and, frankly, quite silly. The marks "LA Times", "Los Angeles Times", and "LATimes" are the property of Tribune Publishing and are used here purely nominatively.