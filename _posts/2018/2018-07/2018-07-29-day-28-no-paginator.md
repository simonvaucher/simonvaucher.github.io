---
layout: post
title:  "Day 28 - static to the rescue"
date:   2018-07-29 08:00:00 +0200
categories: blog
---

Well, it appears that I cannot paginate using `jekyll-paginator` in `github.io` unless using some hack to install the updated gem. It's not a bad hack but still, I prefer not to start tampering things over here unless utterly necessary. The irony is that even an index page holding 365 post excerpts would never bypass a single modern javascript-driven site in size. For the current ~30 pages, the html+css size is 25+9kb - meaning a full year won't exceed even 500kb. Absurd. There are some embedded images, iframes and various javascript junk, but that's left for the browser to optimize.

More `jekyll` goodies [can be found in this cheat sheet](https://devhints.io/jekyll) - not 100% compatible with the github's particular setup, but good enough.

<a data-flickr-embed="true"  href="https://www.flickr.com/photos/137491954@N07/31924371266/" title="Untitled"><img src="https://farm1.staticflickr.com/282/31924371266_59a982616f_k.jpg" alt="Untitled"></a><script async src="//embedr.flickr.com/assets/client-code.js" charset="utf-8"></script>
