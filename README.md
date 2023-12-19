# Search-Bookmarklets

A collection of a few useful Search Bookmarklets for use in web browsers to make life easier. These bookmarklets use JS Prompt Boxes for gettingthe user-input.

Usage & Installation

- To run Bookmarklet, click on the button provided
- To add the Bookmarklet, to our browser's Bookmarks bar, drag the Bookmarlet button to your browser's Bookmark bar
  
For performing a  Google Search:
```
<a href="javascript:(function(){var search=prompt(%22Type your query%22,%22example%22);if(search!=null){window.open('http://www.google.com/search?q='+search+'','_blank');}})();" style="border: 2px solid #999; padding: 2px; background: #cacaca; font-weight: bold;text-decoration:none;color:#000000;">Google Search Bookmarklet</a>
```

For looking up meaning on dictionary.reference.com:
```
<a href="javascript:(function(){var word=prompt(%22Enter the word%22,%22example%22);if(word!=null){window.open('http://dictionary.reference.com/browse/'+word+'','_blank');}})();
" style="border: 2px solid #999; padding: 2px; background: #cacaca; font-weight: bold;text-decoration:none;color:#000000;">See Definition</a>

```

For looking up Synonyms on thesaurus.com.
```
<a href="javascript:(function(){var word=prompt(%22Enter the word%22,%22example%22);if(word!=null){window.open('http://thesaurus.com/browse/'+word+'?s=t','_blank');}})();" style="border: 2px solid #999; padding: 2px; background: #cacaca; font-weight: bold;text-decoration:none;color:#000000;">Find Synonyms</a>
```

For performing a Domain Whois check on Whois.com by inputting the domain name:
```
<a href="javascript:(function(){var dname=prompt(%22Enter domain name%22,%22example.com%22);if(dname!=null){window.open('http://whois.com/whois/'+dname,'_blank');}})();" style="border: 2px solid #999; padding: 2px; background: #cacaca; font-weight: bold;text-decoration:none;color:#000000;">Perform Whois check</a>
```
