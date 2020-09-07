# Search-Bookmarklets

A collection of a few useful Search Bookmarklets for use in web browsers to make life easier. These bookmarklets use JS Prompt Boxes for gettingthe user-input.

Installation

Make a new bookmark in your browser (right-click on the [bookmarks bar](https://support.google.com/chrome/answer/95745?hl=en) and click `Add Page...`)
  - For the "Name" you might put anything you like.
  - Copy each code block below for each functionality you need and paste these codes into the "Location" of a new bookmark.
  - Final Step after adding the Code: Navigate to Bookmarks Bar of your browser (supports Chrome and Firefox mainly) and click the bookmarklet. Voila!
  
  
For performing a  Google Search:
```
javascript:(function(){var search=prompt(%22Type your query%22,%22example%22);if(search!=null){window.open('http://www.google.com/search?q='+search+'','_blank');}})();
```

For looking up meaning on dictionary.reference.com:
```
javascript:(function(){var word=prompt(%22Enter the word%22,%22example%22);if(word!=null){window.open('http://dictionary.reference.com/browse/'+word+'','_blank');}})();
```

For looking up Synonyms on thesaurus.com.
```
javascript:(function(){var word=prompt(%22Enter the word%22,%22example%22);if(word!=null){window.open('http://thesaurus.com/browse/'+word+'?s=t','_blank');}})();
```

For performing a Domain Whois check on Whois.sc by inputting the domain name:
```
javascript:(function(){var dname=prompt(%22Enter domain name%22,%22example.com%22);if(dname!=null){window.open('http://who.is/whois/'+dname,'_blank');}})();
```

For performing a Domain Whois check on Whois.sc for the currently open website:

```
javascript:(function(){var dname=location.host+'';dname=dname.split('.');dname.shift();dname=dname.join('.');if(dname!=null){window.open('http://who.is/whois/'+dname,'_blank');}})();
```
