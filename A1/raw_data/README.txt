The purpose of this assignment is to best implement reproductive practices as detailed in the "Assessing Reproducibility" and The "Basic
Reproducible Workflow Template" articles. For this project, we'll be plotting the timeseries for the viewcounts on a wikipedia page from
December 2007 to September of 2021. While this project will include precise implementation of data acquisiton, curation, and analysis of
these viewcounts over time, it will emphasize proper techniques regarding making a data project more reproducible and open to other 
data scientists.

Wikimedia Liscense: Creative Commons Attribution-ShareAlike 3.0 Unported License (CC-BY-SA). GNU Free Documentation License (“GFDL”)

Wikimedia Terms of Use: https://foundation.wikimedia.org/wiki/Terms_of_Use/en#Our_Terms_of_Use

PageCount API Documentation: https://wikitech.wikimedia.org/wiki/Analytics/AQS/Legacy_Pagecounts

PageViews API Documentation: https://wikimedia.org/api/rest_v1/#/Pageviews%20data/get_metrics_pageviews_top_by_country__project___access___year___month_

Final CSV Variables:

Year - Year in which the view traffic occurred
Month - Month in which the view traffic occurred
pagecount_all_views - Both the desktop and mobile views for the wikipedia page via the PageCount API
pagecount_desktop_views - the desktop views for the wikipedia page via the PageCount API
pagecount_mobile_views - the mobile views for the wikipedia page via the PageCount API
pageview_all_views - Both the desktop and mobile views for the wikipedia page via the PageView API
pageview_desktop_views - the desktop views for the wikipedia page via the PageView API
pageview_mobile_views - the mobile views for the wikipedia page via the PageView API
