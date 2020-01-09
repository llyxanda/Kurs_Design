---
---
Popular food blogs in Sweden - laddningstid
=======================

In this research, I am analyzing 3 of the three popular food blogs to understand the page speed, the reasons behind the good or bad performances of the websites and what can be areas of improvement. the three websites are:

1. [https://linneasskafferi.se/](https://linneasskafferi.se/),
2. [https://zeinaskitchen.se/](https://zeinaskitchen.se/),
3. [https://www.jennysmatblogg.nu/](https://www.jennysmatblogg.nu/)

Sample
-----------------------

I have chosen these types of blogs because they usually include lots of pictures and I want to understand how this aspect is dealt with. 

Method
-----------------------
For this analysis, I am looking at each website score on Google's Page Insights as well as using the dev tools tab network tab where once can check the total page size, time to load and resources and then comparing between the websites and trying to understand what types of resources take a long time to load and what can be improved.


Resultat
-----------------------
[Excel file with results](kmom05_laddningstider.xlsx)


###linneasskafferi.se:

[FIGURE src="image/kmom05/rapport/linneasskafferi.png&w=500&q=40" class="center" caption="linneasskafferi.se"]

####Page speed performance:

Lineasskafferi.se has a low page speed score for mobile (20) and a moderate score for desktop (68) mainly due to the large number of pictures and the fact that some of them are very expensive for the page speed (over 900kb), as these are trying to load when opening the page. 
The most obvious improvements that can be made for this page is to process the pictures in order to get a proper size or compress them using other next-gen formats. 
According to PageInsigths, other improvements are to use lazy loading for offscreen images and better use of the cache memory for static resources.

###zeinaskitchen.se:

[FIGURE src="image/kmom05/rapport/zeinaskitchen.png&w=500&q=40" class="center" caption="zeinaskitchen.se"]

####Page speed performance:
zeinaskitchen.se also has a low mobile score of 13 and a moderate desktop page speed score of 64 when testing the website on PageInsights.
These scores are also due to the large size of the webpage and mainly large number of images loaded. 
Here however the images seem to be better compressed and most of them are in the webp format, except for the logo image on the top of the page which is costing the website a lot and it's not needed to be in the best quality. This affects the FCP and speed index quite a lot.
The webpage performs well on loading time comparing to the other 2 blogs (when checking the speed in dev tools network tab) and the most obvious improvement I can see is also to compress all the pictures and better size them. 
PageInsights recommends also eliminating render-blocking resources.



###jennysmatblogg.nu:

[FIGURE src="image/kmom05/rapport/jennysmatblogg.png&w=500&q=40" class="center" caption="jennysmatblogg.nu"]

####Page speed performance:
jennysmatblogg.nu scores also low for mobile (20) and moderate for desktop (59) because of the huge webpage size and number of requests.
The page has a high load time and the pictures are quite heavy, with many over 1 mb, all in jpeg format. So one of the main improvements that can be done for this page is to also properly size the images by using processing them and using other formats.
Here also PageInsights recommends serving static assets with an efficient cache policy.


Analysis
-----------------------

All the 3 websites have in common a large number of images and each would benefit from improvements in properly sizing them. Out of the 3, zeisnaskitchen.se is the one dealing the best with the images, most of them being in webp format. Also, this blog has the fastest loading time when analyzing it with dev tools network tab despite its relatively large size. However, it has the lowest mobile score out of the three when testing with PageInsghts. the desktop versions of these blogs get quite similar page speed scores on PageInsights, with lineasskafferi having the highest (68) and zeinaskitchen following slightly after (64).
Other improvements that PageInsights recommends for all the 3 websites are to serve static assets with an efficient cache policy, efficiently encode images and avoid enormous network payloads.

Ranking
-----------------------
Based on PageInsights and measuring the page speed with the network tab, I think the best performing website is zeinaskitchen.se, not considering the very low mobile score on PageInsights. With some improvements here for the few images loading on the top of the page which are very big, I think the score would improve considerably. The next blog based on bot measures seems to be linneasskaferiet.se and on the last place jennysmatblogg.nu
However, all three websites seem to be quite similar in terms of performance, with some things to be improved.

Discussion
-----------------------

I think the loading acceptable time limit is around 7 seconds, but it depends on the website content and general design, maybe for some websites a user may want the information faster otherwise they may go to competing websites, while for others it may be worth spending a bit more time waiting. 
All 3 of the chosen websites have quite a long loading time, the best performing being zeinaskitchen.se.
However, I didn't find it very frustrating to wait for this type of website, maybe because I already had low expectations since these websites have many pictures.


-----------------------
Written by Alexandra Berivoe
