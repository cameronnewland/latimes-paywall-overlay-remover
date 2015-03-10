# latimes-paywall-overlay-remover

Bypasses the Los Angeles Times' paywall overlay and allows the user to scroll the window again.

To use this bookmarklet, save the HTML file to your computer, view the HTML file in a web browser, drag the link text to your Bookmarks bar,
then navigate to a paywalled page on the Los Angeles Times' website, and then click the Bookmarklet in your Bookmarks bar.

```javascript
javascript:(function(){document.getElementById("reg-overlay").parentNode.removeChild(overlay);document.getElementsByTagName("BODY")[0].style.overflow="auto";document.getElementsByTagName("HTML")[0].style.overflow="auto";})();
```