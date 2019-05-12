---
layout: post
title:  "Custom content"
---
Page with predefined samples of custom dynamic links system.
This is based on links pointing to `link.locusmap.eu` web page or any custom locus-actions system.

<b>Link to a file</b>
<ul>
  <li><a href="https://link.locusmap.eu?link=https%3A%2F%2Ftest.locusmap.app%2Fassets%2Fdata%2Fsimple_track.gpx">Simple importable file (GPX, track)</a></li>
</ul>

<b>Locus-actions system (Bretaň trip)</b>
<p>Possible options how to point on certain locus-actions prepared content.</p>
<ol>
  <li><a href="https://link.locusmap.eu?link=https%3A%2F%2Ftest.locusmap.app%2Fassets%2Fdata%2Factions%2Fbretan%2Faction.xml">Dynamic link (link.locusmap.eu)</a></li>
  <li>
    <form action="locus-actions://https/test.locusmap.app/assets/data/actions/bretan/action.xml">
	  <input type="submit" value="Custom protocol (method 1)">
    </form>
  </li>
  <li>
    <form action="intent://https/test.locusmap.app/assets/data/actions/bretan/action.xml#Intent;scheme=locus-actions;end">
	  <input type="submit" value="Android intent (method 2)">
    </form>
  </li>
  <li>
    <a href="locus-actions://https/test.locusmap.app/assets/data/actions/bretan/action.xml">
	  <img src="/assets/data/actions/bretan/qr_code.jpg" width="128px">
    </a>
  </li>
</ol>

<b>Locus Store</b>
<ul>
  <li><a href="http://link.locusmap.eu?link=https%3A%2F%2Flocus-map.appspot.com%2Fstore%2Fproducts%2F6007409243848704">Live tracking premium (old link to Store)</a></li>
  <li><a href="http://link.locusmap.eu?link=https%3A%2F%2Fstore.locusmap.eu%2Fproducts%2F6007409243848704">Live tracking premium (new link to Store)</a></li>
  <li><a href="http://link.locusmap.eu?link=https%3A%2F%2Fstore.locusmap.eu%2Fproducts%2Fsearch%2F%3Flabelid%3D20%26regionid%3D41">LoMap, Czech Republic</a></li>
  <li><a href="http://link.locusmap.eu?link=https%3A%2F%2Fstore.locusmap.eu%2Fproducts%2Fsearch%2F%3Flabelid%3D20">LoMaps, all</a></li>
</ul>
