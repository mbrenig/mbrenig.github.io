Where do you live?
================================

I live in San Francisco, and I hate searching for parking spaces. 

So in 2011, when I was buying a car, I knew I'd need to find a permanent garage
to keep it in. Most garage spaces in this city are listed on
[craigslist](http://sfbay.craigslist.org/sfc/prk/). Back in 2011, there was no map to search the city. So I did what any self-respecting geek would
do and wrote a scraper to automatically read the posts, plot them on a map, and
let me know when something near my house became available. This worked really
well, and after 2 months running the search I found the perfect space, about 20 yards from my
front door!

Now several months of crawling craigslist posts generates a lot of data, about 24,000
posts to be precise. As well as a price, a description and an address each post also has a
neighborhood, selected by the poster from a drop down list when they submit the ad. I wondered if you could use this information, combined with the address to reveal where
craigslist users think the San Francisco neighborhoods are. I came up with
this:

[hoodmapper.appspot.com](http://hoodmapper.appspot.com)

I hope you like it. Explore a bit and you'll notice some quirks:
 - There is no Tenderloin. Famous for being dirty and crime-ridden area, no one wants
   to put that on their ad.
 - People are really confused about NOPA.. Is it Alamo Square? Lower Haight?
   Haigh-Ashbury? Pan Handle? or Western Addition?

