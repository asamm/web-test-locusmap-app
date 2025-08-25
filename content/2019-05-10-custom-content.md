+++
title = "Custom content"
+++

Page with predefined samples of custom dynamic links system.  
This is based on links pointing to `link.locusmap.eu` web page or any custom `locus-actions` system.

<!-- more -->

---

**Link to a file**

- [Simple importable file (GPX, track)](https://link.locusmap.eu?link=https%3A%2F%2Ftest.locusmap.app%2Fassets%2Fdata%2Fsimple_track.gpx)

---

**Locus-actions system (Bretaň trip)**  

Possible options how to point on certain locus-actions prepared content.

1. [Dynamic link (link.locusmap.eu)](https://link.locusmap.eu?link=https%3A%2F%2Ftest.locusmap.app%2Fassets%2Fdata%2Factions%2Fbretan%2Faction.xml)  
2.  
   <form action="locus-actions://https/test.locusmap.app/assets/data/actions/bretan/action.xml">
     <input type="submit" value="Custom protocol (method 1)">
   </form>
3.  
   <form action="intent://https/test.locusmap.app/assets/data/actions/bretan/action.xml#Intent;scheme=locus-actions;end">
     <input type="submit" value="Android intent (method 2)">
   </form>
4.  
   <a href="locus-actions://https/test.locusmap.app/assets/data/actions/bretan/action.xml">
     <img src="/assets/data/actions/bretan/qr_code.jpg" width="128px">
   </a>

---

**Locus Store**

- [Live tracking premium (old link to Store)](http://link.locusmap.eu?link=https%3A%2F%2Flocus-map.appspot.com%2Fstore%2Fproducts%2F6007409243848704)  
- [Live tracking premium (new link to Store)](http://link.locusmap.eu?link=https%3A%2F%2Fstore.locusmap.eu%2Fproducts%2F6007409243848704)  
- [LoMap, Czech Republic](http://link.locusmap.eu?link=https%3A%2F%2Fstore.locusmap.eu%2Fproducts%2Fsearch%2F%3Flabelid%3D20%26regionid%3D41)  
- [LoMaps, all](http://link.locusmap.eu?link=https%3A%2F%2Fstore.locusmap.eu%2Fproducts%2Fsearch%2F%3Flabelid%3D20)  