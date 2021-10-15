---
title: Rise of Data Scientist 'Janitors' and the need for Data Wranglers
date: 2018-10-01T00:00:00.000+08:00
description: Data Wranglers
author: You

---
# Rise of Data Scientist ‘Janitors’ and the need for Data Wranglers

  
A recent article on the need for data wrangling is not an eye-opener, but definitely paves way for serious thought into tools and techniques one should employ to ensure that your highly-paid talent is spending more time giving you the value out of data, rather than just preparing it.

“It’s an absolute myth that you can send an algorithm over raw data and have insights pop up,” said Jeffrey Heer, a professor of computer science at the University of Washington

via [For Big-Data Scientists, ‘Janitor Work’ Is Key Hurdle to Insights — NYTimes.com](http://www.nytimes.com/2014/08/18/technology/for-big-data-scientists-hurdle-to-insights-is-janitor-work.html?hpw&action=click&pgtype=Homepage&version=HpHedThumbWell&module=well-region&region=bottom-well&WT.nav=bottom-well).

While working on numerous assignments related to data science, be it real-time analytics in sports, actionable insights on consumer behavior or mining data in order to create learning models, I have spent a big chunk of time just prepping the data. This is not just to build/train models, but many a times preparing the continuous/discrete flow of output to the next system that would consume it (another model ,reporting system or call-to-action on a dashboard). Given post-processing is often handled by the developers, but for analytics that feed into a “live” application requires handshakes between different stakeholders which can be time consuming.

The tricky part is, very often, these aspects cannot be well defined in advance if the nature of work is new or experimental. With the rise of [Polyglot Persistence](http://martinfowler.com/bliki/PolyglotPersistence.html), which ensures performance or in some case even feasibility of the actual processing, the “Data Handshake” becomes a non-trivial challenge.

In my future post, I will try to shine some light into current practices in this area and how they are addressed.
