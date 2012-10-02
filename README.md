
======================
>>> url = 'http://en.wiktionary.org/w/api.php?action=query&list=categorymembers&cmtitle=Category:English_uncountable_nouns&cmlimit=3000'
>>> import urllib
>>> text = urllib.urlopen(url).read()
>>> from xml.dom.minidom import parse
>>> text