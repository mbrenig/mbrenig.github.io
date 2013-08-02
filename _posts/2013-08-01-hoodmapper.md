---
layout: post
title: Where do you live?
---
<h1><a href="{{page.url}}">{{ page.title }}</a></h1>
{{ page.date | date_to_string }}


<a href="http://hoodmapper.appspot.com"><img style="border:1px solid grey;" src="/images/hoodmapper.png" /></a>

I live in San Francisco, and I hate searching for parking spaces. 

So in 2011, when I was buying a car, I knew I'd need to find a permanent garage
to keep it. Most garage spaces in this city are listed on
[craigslist](http://sfbay.craigslist.org/sfc/prk/). Back in 2011, there was no map to search the city. So I did what any self-respecting geek would
do and wrote a scraper to automatically read the posts, plot them on a map, and
let me know when something near my house became available. This worked really
well, and after two months I found a great spot 20 yards from my front door!

Now several months of crawling craigslist posts generates a lot of data, about 24,000
posts to be precise. Each post has a price, a description and an address but it
also has a neighborhood, selected by the poster from a drop down list when they
submit the ad. I used this information to show where craigslist users think the San Francisco neighborhoods are, and came up with this:

[hoodmapper.appspot.com](http://hoodmapper.appspot.com)

Explore a bit and you'll notice some quirks:

 * There is no Tenderloin. Famous for being dirty and crime-ridden area, no one wants
   to put that on their ad.
 * People are really confused about NOPA.. Is it Alamo Square? Lower Haight?
   Haigh-Ashbury? Pan Handle? or Western Addition?
 * Tweet me @mbrenig if you spot something else.

Thanks for reading!
