---
title: Alice's Method
permalink: /docs/alice-method/
---

## Alice's Method of Extracting Location Tagged Passages:

1. Open location tagged file in a text editor (Sublime Text Editor).
2. Find and replace \n\n with @
3. Then replace \n with a space
4. Finally replace @ with \n
5. Import text file into excel or google sheets as tsv file (not csv)
6. Conditional format: Highlight text containing "<location>"
7. Custom sort: Sort by cell color
8. Copy and paste the ones with color onto separate spread sheet
9. Sentiment analysis time!

<img src="{{site.baseurl}}/img/alice-method.png">

