---
layout: base.njk
title: Home
description: Mission and other resource links!
featured_image: favicon.png
eleventyNavigation:
  key: Home
  order: 1
---
# welcome to socal fgc!

hello! this project is intended to be a resource providing tournament information and discord links for southern california fighting game communities. i am a strive player so that's what we have right now!

please check out our <a href="https://github.com/spinningvaliant/socal-fgc">github project</a> if you would like to contribute, or simply to look under the hood. if you don't code (no problem!) but have something you want to add, feel free to reach out to me at <b>spinningvaliant</b> on discord or <a href="mailto:lmohan0@proton.me">email me</a>.

## other resources:

- [SuperCombo Wiki's Regional Discord List (look for USA (California (South))](https://srk.shib.live/w/SuperCombo_Wiki:Community_portal/Discords/Region#North_America)
- [start.gg search](https://www.start.gg/search/near_me?query=&indices%5Bindex_id_hub%5D%5Bpage%5D=1&indices%5Bindex_id_hub%5D%5BrefinementList%5D%5Bpage%5D=1&indices%5Bindex_id_hub%5D%5Brange%5D%5Bpage%5D=1&configure%5BhitsPerPage%5D=10&configure%5Bfilters%5D=profileType%3Atournament&configure%5BaroundLatLngViaIP%5D=false&configure%5BaroundRadius%5D=160934&configure%5BaroundLatLng%5D=33.6845673%2C%20-117.8265049&refinementList%5Bstate%5D%5B0%5D=1&page=1&range%5BstartAt%5D%5Bmin%5D=1752105600&range%5BstartAt%5D%5Bmax%5D=1768003200")
- [FGC Locals Spreadsheet](https://docs.google.com/spreadsheets/u/0/d/1rJdulqidZY_Cdw1S30aLXMFWzttaelxIKyaK-_uZbuc/htmlview#gid=0")
- [SoCal Tekken Locals](https://www.socaltekkenlocals.com")
- [FGC at UCLA](https://fgcatucla.com")
- [San Diego FGC - dates and results for San Diego locals](https://x.com/SanDiego_FGC")

## inspirations:

- [SocalSmash.net](https://www.socalsmash.net/")
- [Michigan Fighting Game Community](https://michiganfgc.com/")
- [Ohio Fighting Game Community](https://ohiofgc.com/")



--- 
<!-- This next part will show your top three most recent posts. You can change how readableDate looks in your .eleventy.js file-->
## recent blog posts:

<div id="recentPostList">
  <ul>
  {% assign top_posts = collections.posts | reverse %}
  {%- for post in top_posts limit:3 -%}
    <li><a href="{{ post.url }}">{{ post.date | readableDate }} » {{ post.data.title }}</a></li>
  {% endfor %}
</div>